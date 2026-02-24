| id            | book | chapter  | type   | status |
|---------------|------|----------|--------|--------|
| B01.CH03.README | B01  | B01.CH03 | readme | draft  |

# B01.CH03 — GROSS≈NET (R/B ≥ α)

This chapter defines **GROSS≈NET** as the primary household-facing order indicator in the economic layer: the chained relation **B → T → N → L → R** and the threshold form **R/B ≥ α**.

It specifies how residual space is defined, how “mandatory burdens” (L) are bounded to prevent drift, how distribution profiles must be reported, and how Goodhart-style manipulation is prevented through audit and publication discipline.

---

## What this chapter is

- A **definition and measurement module** for B, T, N, L, R and the derived indicator R/B.
- A **drift-control module** for the L-minimum set, reference budgets, and revision procedures.
- A **reporting module** that enforces distribution-first publication (medians, percentiles, tails).
- A **manipulation-resistance module**: explicit mitigations for relabeling, off-book shifting, and cosmetic subsidies.

---

## What this chapter is not

- Not a cost-of-living narrative or a political framing tool.
- Not a welfare ideology chapter; it is an order variable definition and audit discipline.
- Not a substitute for sector design (see CH09) or commons regime design (see CH06).

---

## Binding and constraints

- **Kernel precedence:** definitions inherit meaning from the Kernel Spec; this chapter operationalizes them for the economic layer.
- **Distribution-first:** averages are insufficient; tails are primary.
- **Fail-closed:** if L definitions, α rules, or required observables are missing, compatibility claims cannot be issued.
- **No identity labeling:** segmentation is by region/sector/household type as defined, not by identity categories.

---

## Chapter structure

- **P01 — Definitions:** B, T, N, L, R and computation frames.
- **P02 — Threshold form:** why R/B, what α means, allowed bands, and indexation rules.
- **P03 — L classification:** what counts as mandatory, reference budgets, drift prevention, abuse/avoidance handling.
- **P04 — Distribution profiles:** why percentiles matter and what must be published.
- **P05 — Policy levers:** which variables move R/B directly and how they link to E, caps, and commons.
- **P06 — Goodhart mitigations:** definition hardening, audit strategy, public reporting discipline, fail-closed rules.

See **[index.md](./index.md)** for the paragraph map.

---

## Outputs expected from this chapter

When implemented (via Codex artifacts), this chapter should enable:

- A **standardized R/B calculation** with versioned definitions for B, T, L and household equivalisation.
- A **publishable dashboard**: median R/B, p10/p25/p75, share below α, time trends, and uncertainty notes.
- A **versioned L-minimum specification** with reference budgets and revision/restatement procedures.
- An **anti-manipulation control set**: anomaly checks for relabeling, off-book shifting, and subsidy cosmetics.

---

## Interfaces

- **CH02 (P/E/C):** defines toll layers and fee-stacks that often constitute L burdens; classification informs L boundaries.
- **CH04 (caps):** fiscal redesign and cap enforcement shape T and income/wealth distribution, affecting R/B.
- **CH05 (E reduction):** reducing E lowers L and/or T through fee/interest/rent compression.
- **CH06 (commons):** commons substitution reduces L directly in essentials and stabilizes R/B tails.
- **CH10 (audit):** measurement, uncertainty handling, revisions/restatements, and privacy rules are implemented via Codex.

---

## Status and editing constraints

- Status: **draft**.
- Edits must preserve:
  - ID grammar (`B01.CH03.Pxx.Sxx`)
  - Link integrity (lowercase filenames)
  - Drift prevention for L and α (no informal expansion)
  - Distribution-first reporting discipline
