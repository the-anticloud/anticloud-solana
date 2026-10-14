# Ethics — SOLANA

**Project:** SOLANA  
**Category:** CRYPTOCURRENCY  
**Upstream:** https://github.com/solana-labs/solana  
**Pinned commit:** `7700cb3128c1f19820de67b81aa45d18f73d2ac0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8459879dae1808375ba30a25f92117ccb14017492e16ad56ddf8430a46638a79`  
**Date:** October 2026

## Position

SOLANA is packaged for offline deployment with a verifiable audit trail. The
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
