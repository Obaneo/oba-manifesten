| id            | book | chapter  | type   | status |
|---------------|------|----------|--------|--------|
| B01.CH02.README | B01  | B01.CH02 | readme | draft  |

# B01.CH02 — The flow model (P/E/C)

This chapter defines the economic **flow model** used in Book 1: how the economy is represented as a network of flows, how flows are decomposed into **P/E/C**, and how attribution, consolidation, measurability, and audit controls are handled.

It is the **classification kernel** for the economic layer: without a working P/E/C model, the rest of Book 1 (R/B, caps, commons, ΔM routing) cannot be enforced.

---

## What this chapter is

- A **representation layer**: nodes, edges, claims, rights, ownership vs access.
- A **classification layer**: operational definitions and split rules for P/E/C, including mixed flows.
- An **attribution layer**: actor vs position, ultimate control/block power, consolidation through vehicles, chain attribution.
- A **measurement layer**: minimum observation set, proxies/uncertainty, audit logic, and publishable indicators.

---

## What this chapter is not

- Not a sector-specific policy catalog (that belongs primarily in CH09).
- Not a full data dictionary or implementation spec (that belongs in Book X / Codex).
- Not an ethics narrative about “good” and “bad” actors; classification is functional and evidence-based.

---

## Binding and constraints

- **Kernel precedence:** terms used here inherit meaning from the Kernel Spec; this chapter does not redefine the canon.
- **Fail-closed:** if a flow cannot be made auditable (missing disclosure, black-box pricing, blocked ownership/control), it cannot be certified as “non-extractive” by assertion.
- **Substance over form:** legal labels are subordinate to economic reality; consolidation and ultimate control govern attribution.

---

## Chapter structure

- **P01 — Flow network:** nodes/edges, claims, and the ownership vs access layer.
- **P02 — P/E/C definitions:** criteria and split rules, including negative/zero components.
- **P03 — Attribution and accounting:** actor vs position, ultimate control, consolidation, chain attribution, anti-double-counting.
- **P04 — Node types:** households, firms, financial entities, state, commons institutions.
- **P05 — Edge cases:** IP, credit/interest, rent/land, platforms, public/private hybrids.
- **P06 — Measurement and audit:** minimum observation set, proxies, red flags, publishable indicators, version control.

See **[index.md](./index.md)** for the paragraph map.

---

## Outputs expected from this chapter

When implemented (via Codex artifacts), this chapter should enable:

- A **flow decomposition procedure** that yields P/E/C components per flow (including chain attribution).
- A **sector-level E share indicator** that is publishable and versioned.
- A **set of red flags** (fee-stack depth, markup extremes, lock-in indicators) that triggers audits.
- A **consolidation rule set** that maps flows to ultimate beneficial control where relevant.

---

## Interfaces

- **CH03 (R/B):** household burdens (L) and residual space depend on classifying toll layers (E) in essentials.
- **CH04 (caps):** consolidation and ultimate control are reused for W/I bases.
- **CH06 (commons):** C measurement and commons contribution classification must align.
- **CH07 (ΔM):** channel classification depends on flow definitions and forbidden-route detection.
- **Book X (Codex):** schemas, validators, and audit packs operationalize all measurement and attribution rules in this chapter.

---

## Status and editing constraints

- Status: **draft**.
- Edits must preserve:
  - ID grammar (`B01.CH02.Pxx.Sxx`)
  - Link integrity (lowercase filenames)
  - Separation between conceptual rules (here) and implementation artifacts (Codex)
  - Auditability and fail-closed discipline
