# Students — SOLANA

**Project:** SOLANA  
**Category:** CRYPTOCURRENCY  
**Upstream:** https://github.com/solana-labs/solana  
**Pinned commit:** `7700cb3128c1f19820de67b81aa45d18f73d2ac0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8459879dae1808375ba30a25f92117ccb14017492e16ad56ddf8430a46638a79`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `7700cb3128c1f19820de67b81aa45d18f73d2ac0`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `8459879dae1808375ba30a25f92117ccb14017492e16ad56ddf8430a46638a79`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
