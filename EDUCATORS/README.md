# Educators — OPENSESAME

**Project:** OPENSESAME  
**Category:** PSYCHOLOGY  
**Upstream:** see BENCH.json  
**Pinned commit:** `1026629d6f6a13dd610d146b015d27ec3888fd2c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9b8493cab7f62698805a9e7cbe3b3f054d36433ad0cf9b002ac1715c0d41df7b`  
**Date:** October 2026

## Teaching with OPENSESAME

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `9b8493cab7f62698805a9e7cbe3b3f054d36433ad0cf9b002ac1715c0d41df7b` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
