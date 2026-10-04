# 3-Seed Simulation — K_SAFERLHF

**Seeds:** `56253` · `87590` · `21789`

**Seed method:** `sha256("K_SAFERLHF")[:8]` as hex→int, offsets +0 / +31337 / +65536

> These seeds are deterministic and documented. Any researcher can reproduce this simulation exactly by running `write_three_seed_simulation.py` with project name `K_SAFERLHF`.

## Confidence Intervals (mean ± σ across 3 seeds)

| Metric | Mean | σ | 95% CI |
|--------|------|---|--------|
| trl_score | 7.0417 | 0.1106 | ±0.2168 |
| throughput_tokens_per_sec | 484.2333 | 33.3619 | ±65.3893 |
| p50_latency_ms | 44.84 | 2.6384 | ±5.1713 |
| p99_latency_ms | 109.1967 | 6.409 | ±12.5616 |
| ttft_ms | 24.9067 | 1.2422 | ±2.4347 |
| mmlu_proxy | 0.6954 | 0.0262 | ±0.0514 |
| hellaswag_proxy | 0.781 | 0.0254 | ±0.0498 |
| truthfulqa_proxy | 0.5811 | 0.0205 | ±0.0402 |
| arc_proxy | 0.6887 | 0.0388 | ±0.076 |
| complexity_cyclomatic | 3.8967 | 0.6539 | ±1.2816 |
| maintainability_index | 72.3333 | 4.1201 | ±8.0754 |
| security_issues_high | 1.0 | 0.8165 | ±1.6003 |
| dependency_freshness_pct | 82.0333 | 2.2647 | ±4.4388 |
| test_coverage_pct | 46.2667 | 3.7748 | ±7.3986 |
| doc_coverage_pct | 65.7667 | 6.4789 | ±12.6986 |
| memory_mb | 50.0 | 0.0 | ±0.0 |
| gpu_util_pct | 68.3667 | 5.4908 | ±10.762 |
| openssf_score | 6.64 | 0.6375 | ±1.2495 |
| eu_ai_act_compliance_pct | 76.6667 | 0.7134 | ±1.3983 |
| slsa_level | 1.3333 | 0.4714 | ±0.9239 |

## Per-Seed Raw Results

| Metric | Seed 56253 | Seed 87590 | Seed 21789 |
|--------|------------|------------|------------|
| trl_score | 6.948 | 6.98 | 7.197 |
| throughput_tokens_per_sec | 437.4 | 502.7 | 512.6 |
| p50_latency_ms | 41.13 | 46.35 | 47.04 |
| p99_latency_ms | 103.16 | 106.36 | 118.07 |
| ttft_ms | 23.53 | 26.54 | 24.65 |
| mmlu_proxy | 0.6769 | 0.6769 | 0.7324 |
| hellaswag_proxy | 0.7842 | 0.7484 | 0.8103 |
| truthfulqa_proxy | 0.6079 | 0.577 | 0.5583 |
| arc_proxy | 0.634 | 0.7203 | 0.7118 |
| complexity_cyclomatic | 3.48 | 3.39 | 4.82 |
| maintainability_index | 69.39 | 78.16 | 69.45 |
| security_issues_high | 0 | 2 | 1 |
| dependency_freshness_pct | 79.7 | 85.1 | 81.3 |
| test_coverage_pct | 43.8 | 43.4 | 51.6 |
| doc_coverage_pct | 59.0 | 63.8 | 74.5 |
| memory_mb | 50 | 50 | 50 |
| gpu_util_pct | 67.7 | 62.0 | 75.4 |
| openssf_score | 7.4 | 6.68 | 5.84 |
| eu_ai_act_compliance_pct | 75.7 | 76.9 | 77.4 |
| slsa_level | 1 | 1 | 2 |

---
_Anticloud 3-Seed Simulation — 2026-09-30T16:01:40.704491+00:00_
_Citation: Lois-Kleinner. (2026). The Anticloud. DOI: pending._