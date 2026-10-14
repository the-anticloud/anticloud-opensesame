# Ethics — OPENSESAME

**Project:** OPENSESAME  
**Category:** PSYCHOLOGY  
**Upstream:** see BENCH.json  
**Pinned commit:** `1026629d6f6a13dd610d146b015d27ec3888fd2c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9b8493cab7f62698805a9e7cbe3b3f054d36433ad0cf9b002ac1715c0d41df7b`  
**Date:** October 2026

## Position

OPENSESAME is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
