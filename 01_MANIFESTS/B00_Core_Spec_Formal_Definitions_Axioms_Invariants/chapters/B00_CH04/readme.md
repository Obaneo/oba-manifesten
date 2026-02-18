| id            | book | chapter | type   | status |
|---------------|------|---------|--------|--------|
| B00.CH04.README | B00  | CH04     | readme | draft  |

# B00.CH04 — Definition set II: GROSS→NET→ESSENTIALS→REMAINING SPACE (B,T,N,L,R) and R/B≥α

This chapter defines the canonical remainder-space decomposition:
**B → T → N → L → R** and the order-floor condition **R/B ≥ α**.

It specifies:
- the canonical quantities **B, T, N, L, R** and their base identities;
- strict classification rules for **T** (mandatory transfer-out) and **L** (essentials / claim layers);
- **R/B** as a life-world order indicator (buffer, autonomy, shock resilience);
- the **α** threshold regime (meaning, allowed variation, and change procedure);
- the distribution requirement: **R/B is a cohort profile, not a macro average**;
- linkages to **P/E/C**, **caps (W-MAX, I-MAX)**, and **ΔM**;
- measurement standards, auditability requirements, and hard stops against R/B-washing and black-box indices.

This chapter is the canonical interface between:
- micro life-world conditions (household remainder and buffer),
- macro aggregates (national accounts and sector totals),
- and OBA enforcement levers (P/E/C, caps, and ΔM channel rules).

## How to use this chapter

- If you are **writing any later chapter**: import B/T/N/L/R and R/B≥α conventions from here; do not redefine them locally.
- If you are **building datasets or pipelines**: implement the canonical decomposition, strict T/L classification, and cohort-profile reporting (median, tails, share below α).
- If you are **auditing**: test whether B/T/N/L/R are reproducible from declared inputs, and whether cohort profiles reconcile micro→macro without masking (Simpson’s paradox controls).
- If you are **implementing P/E/C, caps, or ΔM**: use R/B profiles as the primary life-world outcome constraint; interventions must show traceable improvement or stabilisation of R/B.

## Structure

P01 — Purpose and scope of Definition set II  
P02 — Canonical quantities and base identities (B,T,N,L,R)  
P03 — Strict classification rules for T (what counts as T)  
P04 — Strict classification rules for L (burdens/essentials/claim layers)  
P05 — Distribution requirement: R/B is a profile, not an average  
P06 — Definition of α (order threshold) and parameter regime  
P07 — Attribution of B (gross) at micro level  
P08 — R/B as order indicator: interpretation rules and edge cases  
P09 — Relation to P/E/C: how E materialises as L and R pressure  
P10 — Relation to caps: W-MAX/I-MAX and the R/B floor  
P11 — Relation to ΔM: channel rules and macro stability via R/B  
P12 — Measurement standards and minimum data layer  
P13 — Auditability and reproducibility  
P14 — Failure modes and hard stops

## Status

This chapter should remain stable across versions because it defines the canonical remainder-space algebra used by
later chapters and by any OBA-grade evaluation pipeline. Changes here are high-impact and typically imply major
version implications:
- altered definitions of B/T/N/L/R or their identities;
- changed strict classification rules for T or L (especially the essentials set and lock-in rules);
- changes to the α regime (meaning, allowed variation, change procedure);
- changed cohort-profile requirements or reconciliation constraints.

Black-box burden indices, non-reproducible cohort profiles, or definitions that allow L inflation or B inflation
to “pass” an R/B target are non-conform by default.

