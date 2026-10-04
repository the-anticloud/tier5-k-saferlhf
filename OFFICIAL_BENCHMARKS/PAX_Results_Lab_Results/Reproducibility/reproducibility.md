# Reproducibility Record: PAX_Results_Lab_Results

**Project:** `K_SAFERLHF`  
**Benchmark:** `PAX_Results_Lab_Results`  
**Run:** `2026-09-30T15:11:19.033679+00:00`  
**Based on:** [HELM reproducibility principles](https://github.com/stanford-crfm/helm)

## Environment

| Field | Value |
| ----- | ----- |
| Platform | `win32` |
| Python | `3.12.10` |
| OS | `nt` |

## Inputs

| Field | Value |
| ----- | ----- |
| Slug | `PKU-Alignment/safe-rlhf` |
| Commit | `e8cca16665ef` |
| Tracked files | `150` |
| Source lines | `15007` |
| Licence | `Apache-2.0` |
| Inputs SHA256 | `295156e6ef86bfb7...` |

## Outputs

| Field | Value |
| ----- | ----- |
| Results file | `TIER_5_WORLD_NEURO_EMBODIED\K_SAFERLHF\OFFICIAL_BENCHMARKS\PAX_Results_Lab_Results\results.json` |
| Results SHA256 | `ce969d15d810b8e5...` |

## Reproduction Steps

- 1. Clone Anticloud at commit HEAD
- 2. Ensure E:\fenta\Downloads\The Anticloud is present
- 3. Run: python run_benchmarks_comprehensive.py
- 4. Run: python write_benchmark_subfolders.py
- 5. Run: python write_ledgers_repro_extra_benchmarks.py
- 6. Verify results_sha256 matches sha256(OFFICIAL_BENCHMARKS/PAX_Results_Lab_Results/results.json)

## Notes

TRL/OSINT/OWASP/SOC2/ISO27001/MITRE/NIST use static code analysis. HF uses live CPU inference.

---
_Anticloud Reproducibility Standard v1 — 2026-09-30T15:11:19.033679+00:00_