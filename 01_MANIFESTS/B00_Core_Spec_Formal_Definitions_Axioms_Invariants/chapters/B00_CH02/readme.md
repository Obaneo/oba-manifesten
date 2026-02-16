---
id: B00.CH02.README
book: B00
chapter: CH02
type: readme
status: draft
---

# B00.CH02 — Canonical notation and object model

This chapter defines the **canonical notation** and the **object model** used throughout the B00 Core Spec. It provides the shared “grammar” required for semantic closure: symbols, indices, object types, attribution rules, and the minimum conventions needed for auditability and reconciliation.

The chapter is intentionally *formal*: it specifies naming discipline, typing and units, time indexing, stock/flow conventions, and the core object schemas that later chapters rely on (P/E/C, B–T–N–L–R, W-MAX/I-MAX, ΔM, commons, and UBC relations).

## How to use this chapter

- If you are **writing** any later chapter: import notation from here; do not redefine it locally.
- If you are **building datasets or pipelines**: treat the object schemas (actors, positions, flows, contracts, channels) as the minimum interoperable model.
- If you are **auditing**: use the typing/unit/time and reconciliation rules to test whether claims are measurable and consistent across micro→macro levels.
- If you are **implementing caps, ΔM rules, commons programs, or UBC consolidation**: use the canonical bases and relation tests specified here as the entry point.

## Structure

- **P01 — Notation principles and symbol registry**: canonical symbols, typing, and operator semantics.
- **P02 — Time, resolution and aggregation**: index conventions, aggregation discipline, stock/flow separation, and reconciliation identities.
- **P03 — Actor, position and role model**: actors vs entities, positions, role attributes (control/benefit/block/duty), and look-through relations.
- **P04 — Flow and contract objects**: transaction model primitives, contract metadata, chain attribution, and double-counting prevention.
- **P05 — Core variables B,T,N,L,R**: remainder-space algebra and identities for receipts, transfers, burdens, and buffer.
- **P06 — P/E/C classification**: canonical decomposition of flows into production, extraction, and commons contribution (including chain splitting).
- **P07 — Cap objects W-MAX and I-MAX**: base definitions, cap functions, and valuation conventions under conservatism.
- **P08 — ΔM as allocation interface**: channel object model, prohibited channels, and traceability requirements.
- **P09 — Commons object model**: access/maintenance regime, ΔG metrics, minimum governance, public option/hybrid layering.
- **P10 — Control/benefit/block tests**: canonical relation tests and composite UBC consolidation via graph evaluation.

## Status

This chapter should remain stable across versions because it is the shared interface for the rest of the canon. Changes here are high-impact and typically imply **major** version implications (new symbols, altered object schemas, changed reconciliation rules, or modified relational tests).
