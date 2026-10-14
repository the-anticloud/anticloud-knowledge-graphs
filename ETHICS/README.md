# Ethics — KNOWLEDGE_GRAPHS

**Project:** KNOWLEDGE_GRAPHS  
**Category:** PHILOSOPHY_SEMANTICS  
**Upstream:** see BENCH.json  
**Pinned commit:** `86f1c941bea7bf53fa45fe4e08c03244b4990eee`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b77800a0deec5286a131e382cdca90c7280c730d94bf7f27ce80f6d0b395d113`  
**Date:** October 2026

## Position

KNOWLEDGE_GRAPHS is packaged for offline deployment with a verifiable audit trail. The
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
