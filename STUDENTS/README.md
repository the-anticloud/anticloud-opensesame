# Students — OPENSESAME

**Project:** OPENSESAME  
**Category:** PSYCHOLOGY  
**Upstream:** see BENCH.json  
**Pinned commit:** `1026629d6f6a13dd610d146b015d27ec3888fd2c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9b8493cab7f62698805a9e7cbe3b3f054d36433ad0cf9b002ac1715c0d41df7b`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `1026629d6f6a13dd610d146b015d27ec3888fd2c`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `9b8493cab7f62698805a9e7cbe3b3f054d36433ad0cf9b002ac1715c0d41df7b`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
