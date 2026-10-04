# Ledger Status

**Project:** `K_SAFERLHF`  
**Tier:** TIER_5_WORLD_NEURO_EMBODIED  
**Identity:** Upstream `PKU-Alignment/safe-rlhf` @ `e8cca16665ef` (Apache-2.0)

## Chain state

| Fact | Value |
| --- | --- |
| Upstream | `PKU-Alignment/safe-rlhf` |
| Commit | `e8cca16665ef2340ac92c6514f05519310251581` |
| Upstream licence | Apache-2.0 |
| Licence class | permissive |
| Clone size | 5.48 MB |
| Ledger | 0 blocks, chain verified |
| Current TRL | NOT YET MEASURED |
| Post-optimisation TRL | NOT YET MEASURED |
| II budget cap | 1000.0 IIU |
| Verified upstream edits | 1 |

- Blocks: **0**
- Head digest: `None`
- Chain verification: **verified**

## Independent verification

The chain is verifiable without trusting this project's tooling:

```
anticloud ledger verify
anticloud ledger export > ledger.jsonl
```

Each block carries the previous block's digest, so removing or reordering an
entry invalidates every block after it. That property is the reason the
ledger can stand in for a claim of what happened.
