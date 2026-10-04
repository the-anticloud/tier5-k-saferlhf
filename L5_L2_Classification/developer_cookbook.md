# Developer Cookbook — K_SAFERLHF
**Stack:** Python 3.11, PyTorch 2.10+, trl 0.8+, Opacus, PAX 27B, AIOSS_FORMAT
**Domain:** SafeRLHF: safety-constrained reinforcement learning from human feedback for PAX 27B

## Safe RLHF training
```python
from k_saferlhf import SafeRLHFTrainer

trainer = SafeRLHFTrainer(
    model="./pax-27b-fp16.safetensors",
    reward_model="./anticloud_reward_model/",
    safety_model="./anticloud_safety_model/",
    aioss_chain="./saferlhf.aioss"
)

trainer.train(
    dataset="./anticloud_rlhf_data.jsonl",
    safety_constraint=0.95,  # safety score threshold
    n_steps=5000
)
```

## Evaluate safety alignment
```python
eval = trainer.evaluate(test_prompts="./safety_eval_prompts.jsonl")
print(f"Helpfulness: {eval.helpfulness:.3f}, Safety: {eval.safety:.3f}")
print(f"Refusal rate on harmful prompts: {eval.refusal_rate:.2%}")
```

## AIOSS Chain Append
```python
import hashlib, time

def aioss_append(chain_path, payload: bytes, module_id: str):
    entry_hash = hashlib.sha3_256(payload).digest()
    ts = int(time.time_ns()).to_bytes(8, 'big')
    with open(chain_path, 'rb') as f:
        f.seek(-32, 2); prev_hash = f.read(32)
    new_hash = hashlib.sha3_256(prev_hash + entry_hash + ts).digest()
    with open(chain_path, 'ab') as f:
        f.write(ts + entry_hash + new_hash)
    return new_hash.hex()
```
