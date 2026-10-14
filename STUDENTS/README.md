# Students — VLLM

**Project:** VLLM  
**Category:** FRONTIER_HARNESSES  
**Upstream:** see BENCH.json  
**Pinned commit:** `242e4213fc9845ff6fe607af1aee626fd8acc990`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `817d0fc4ab0a14961d7998747c85b4365170245746aba63cd161b704d7df1658`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `242e4213fc9845ff6fe607af1aee626fd8acc990`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `817d0fc4ab0a14961d7998747c85b4365170245746aba63cd161b704d7df1658`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
