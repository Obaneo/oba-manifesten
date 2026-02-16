# B00.CH02 — Canonical notation and object model

This chapter defines the canonical notation and the minimal object model used throughout the Core Spec.  
It fixes the semantics of symbols, time indexing, aggregation conventions, entity/role graphs, and the
standard objects used to represent flows, contracts, caps, commons, and ΔM channels.

**Normative intent.** CH02 is *foundational*: later chapters may reference these constructs but must not
redefine them. Any implementation claiming OBA compatibility must be able to parse and operationalize
CH02 objects and conventions without local deviations.

**Scope.** The chapter covers:
- Canonical symbol discipline and a minimal symbol registry
- Time indexing, resolution, and aggregation rules (including stock/flow conventions)
- Actor/entity/position/role modeling and look-through consolidation as a graph problem
- Flow and contract object schemas and rules to prevent double counting
- Canonical variables **B, T, N, L, R** and their identities
- Canonical classification **P/E/C** at flow level and along chains
- Canonical cap objects **W-MAX** and **I-MAX** (bases, valuation, enforcement interfaces)
- **ΔM** as a traceable allocation interface via channel objects
- Commons as an order regime (access, boundary rules, maintenance) with **ΔG** as state variable
- Canonical relational tests: **control / benefit / block**, and composite **UBC** evaluation

**How to read.** Each paragraph file (P01…P10) is a canonical reference unit. Implementations should
reference paragraph IDs (e.g., `B00.CH02.P06.S02`) rather than paraphrasing definitions, to minimize drift.

For the normative list of paragraph units, see `index.md`.

