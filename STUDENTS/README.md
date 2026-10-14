# Students — KNOWLEDGE_GRAPHS

**Project:** KNOWLEDGE_GRAPHS  
**Category:** PHILOSOPHY_SEMANTICS  
**Upstream:** see BENCH.json  
**Pinned commit:** `86f1c941bea7bf53fa45fe4e08c03244b4990eee`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b77800a0deec5286a131e382cdca90c7280c730d94bf7f27ce80f6d0b395d113`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `86f1c941bea7bf53fa45fe4e08c03244b4990eee`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `b77800a0deec5286a131e382cdca90c7280c730d94bf7f27ce80f6d0b395d113`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
