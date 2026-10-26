# Tier 1 Protocol

**A forensic reconciliation engine for personal archives — retrieval you can verify, from records that never leave home.**

Anyone who has to prove something from a large personal record — a legal case, an insurance fight, a family archive — hits the same wall: keyword search can't find meaning across hundreds of thousands of messages, emails, filings, and statements, and pasting evidence into a cloud chatbot breaks privacy and chain of custody.

Tier 1 Protocol is the retrieval half of the solution. Every record is encoded into a fixed-dimension algebraic field (Evolved Structural Algebra, D=4096), sealed with SHA-256, and queried algebraically — so every readout is reproducible and verifiable against the sealed corpus. It runs locally and offline. An MCP door (search / fetch / verify) lets an AI agent work the corpus under a provenance discipline: prepared queries, reading that starts at the hit, and refusal when the field has no answer.

## Why there is no public code here

The engine processes sealed evidence. Source and corpora stay private by design — the same reason a law firm doesn't publish its case files. Verification in this system does not come from reading code; it comes from recomputation: any readout can be re-derived from the sealed records and checked, by anyone holding them, at any time. Records stay home. Readouts travel.

## What is public

- **Live product & demo:** https://tier-1-protocol-kfn8.bolt.host — a working PWA with the MCP endpoint live and verifiable from an external client.
- **The reference instance:** 581,368 sealed records from a real, documented case — one person's messages, email, filings, and financial records, reconciled end to end.
- **The demonstrated result:** a paired-signature reconciliation of a documented device-intrusion dataset — odds ratio 270, Fisher p ≈ 5×10⁻²⁶, fragility of 27 membership flips, E-values 539.5 / 80.5 — written up with full derivations as a 473-page technical volume.
- **The security layer:** a post-quantum sealed archive — XMSS-SHA-512 anchors countersigned with SLH-DSA (FIPS 205), threshold-custodied secrets, scheduled re-anchoring.
- **Patents:** two U.S. provisional applications on the construction (63/967,537 · 63/967,845, January 2026).

## Who builds it

Solo: Tyler Brassel — Santa Rosa, California.
Personal profile: https://github.com/tbrassel · https://www.linkedin.com/in/tyler-brassel
