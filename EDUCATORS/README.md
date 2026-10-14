# Educators — KNOWLEDGE_GRAPHS

**Project:** KNOWLEDGE_GRAPHS  
**Category:** PHILOSOPHY_SEMANTICS  
**Upstream:** see BENCH.json  
**Pinned commit:** `86f1c941bea7bf53fa45fe4e08c03244b4990eee`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b77800a0deec5286a131e382cdca90c7280c730d94bf7f27ce80f6d0b395d113`  
**Date:** October 2026

## Teaching with KNOWLEDGE_GRAPHS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `b77800a0deec5286a131e382cdca90c7280c730d94bf7f27ce80f6d0b395d113` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
