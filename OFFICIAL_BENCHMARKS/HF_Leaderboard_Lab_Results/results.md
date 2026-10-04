# HF_Leaderboard_Lab_Results

**Project:** `K_SAFERLHF`  
**Tier:** `TIER_5_WORLD_NEURO_EMBODIED`  
**Slug:** `PKU-Alignment/safe-rlhf`  
**Commit:** `e8cca16665ef`  
**Run:** `2026-09-30T15:07:07.146295+00:00`  

## Isolation Environment

| Field | Value |
| ----- | ----- |
| Platform | `win32` |
| Python | `3.12.10` |
| HF model | `distilbert-base-uncased` |
| HF load time | `4.42s` |
| Inference device | `cpu` |

## Results

**Framework:** [HuggingFace Open LLM Leaderboard (proxy via distilbert-base-uncased)](https://huggingface.co/docs/leaderboards/en/open_llm_leaderboard/archive)

**Model used:** `distilbert-base-uncased`

### Inference Latency (Classification)

| Metric | Value |
| ------ | ----- |
| Avg latency | **46.63 ms** |
| Min latency | 40.08 ms |
| Max latency | 49.58 ms |
| Samples | 5 |

### Real Tokenization Results

| Field | Value |
| ----- | ----- |
| Token count | **44** |
| Tokenization latency | 0.0 ms |
| Classification label | `LABEL_0` |
| Classification score | 0.5878 |
| Classification latency | 134.0 ms |
| Status | **PASS** |

**Input text tokenized:**
```
K_SAFERLHF (PKU-Alignment/safe-rlhf) — 150 files, 15007 source lines, licence Apache-2.0, primary language ['Python']
```

**First 20 tokens:**
```
['[CLS]', 'k', '_', 'safer', '##l', '##h', '##f', '(', 'p', '##ku', '-', 'alignment', '/', 'safe', '-', 'r', '##l', '##h', '##f', ')']
```

> Full MMLU/HellaSwag/TruthfulQA/ARC/Winogrande/GSM8K require dedicated GPU.
> These results are CPU inference proxy metrics using distilbert-base-uncased.

---
_Anticloud Benchmark Suite — isolation log — 2026-09-30T15:07:07.146295+00:00_