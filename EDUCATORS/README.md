# Educators — VLLM

**Project:** VLLM  
**Category:** FRONTIER_HARNESSES  
**Upstream:** see BENCH.json  
**Pinned commit:** `242e4213fc9845ff6fe607af1aee626fd8acc990`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `817d0fc4ab0a14961d7998747c85b4365170245746aba63cd161b704d7df1658`  
**Date:** October 2026

## Teaching with VLLM

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `817d0fc4ab0a14961d7998747c85b4365170245746aba63cd161b704d7df1658` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
