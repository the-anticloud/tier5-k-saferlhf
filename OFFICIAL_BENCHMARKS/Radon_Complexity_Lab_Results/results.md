# Radon_Complexity_Lab_Results
**Project:** `K_SAFERLHF` | **Status:** `PASS` | **Run:** `2026-09-30T17:14:20.030944+00:00`

**Framework:** [Radon — Cyclomatic Complexity & Maintainability Index](https://radon.readthedocs.io/)

## Key Metrics

- **files_analyzed:** `10`
- **average_complexity:** `{'grade': 'A', 'score': 3.933333333333333}`
- **complexity_grade:** `A`
- **complexity_score:** `3.933333333333333`
- **mi_output:** `E:\fenta\Downloads\The Anticloud\TIER_5_WORLD_NEURO_EMBODIED\K_SAFERLHF\UPSTREAM\setup.py - A (88.67)
E:\fenta\Downloads`

## Raw Output (first 50 lines)
```
E:\fenta\Downloads\The Anticloud\TIER_5_WORLD_NEURO_EMBODIED\K_SAFERLHF\UPSTREAM\safe_rlhf\logger.py
    M 72:4 Logger.__new__ - C (11)
    M 184:4 Logger.print_table - C (11)
    C 65:0 Logger - B (7)
    M 150:4 Logger.log - B (6)
    F 47:0 set_logger_level - A (4)
    M 161:4 Logger.close - A (3)
    M 171:4 Logger.print - A (2)
E:\fenta\Downloads\The Anticloud\TIER_5_WORLD_NEURO_EMBODIED\K_SAFERLHF\UPSTREAM\safe_rlhf\utils.py
    F 246:0 get_optimizer_grouped_parameters - B (10)
    F 79:0 get_subclasses - A (4)
    F 97:0 __initialize_pytree_registry_once - A (4)
    F 70:0 str2bool - A (3)
    F 136:0 to_device - A (3)
    F 145:0 batch_retokenize - A (3)
    F 173:0 is_same_tokenizer - A (3)
    F 184:0 is_main_process - A (2)
    F 201:0 masked_mean - A (2)
    F 225:0 get_all_reduce_mean - A (2)
    F 232:0 get_all_reduce_sum - A (2)
    F 239:0 get_all_reduce_max - A (2)
    F 60:0 seed_everything - A (1)
    F 189:0 rank_zero_only - A (1)
    F 211:0 gather_log_probabilities - A (1)
    F 280:0 split_prompt_response - A (1)
E:\fenta\Downloads\The Anticloud\TIER_5_WORLD_NEURO_EMBODIED\K_SAFERLHF\UPSTREAM\safe_rlhf\_anticloud_egress.py
    F 38:0 _is_frontier - A (4)
    F 43:0 guarded_connect - A (4)
    F 61:0 install - A (3)
    F 33:0 is_offline - A (1)
    C 29:0 EgressDenied - A (1)
E:\fenta\Downloads\The Anticloud\TIER_5_WORLD_NEURO_EMBODIED\K_SAFERLHF\UPSTREAM\safe_rlhf\configs\deepspeed_config.py
    F 34:0 get_deepspeed_train_config - B (9)
    F 91:0 get_
```

---
_Anticloud Independent Benchmark — 2026-09-30T17:14:20.030944+00:00_