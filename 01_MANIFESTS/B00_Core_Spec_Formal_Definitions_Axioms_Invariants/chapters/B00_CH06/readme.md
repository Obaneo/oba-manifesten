| id             | book | chapter | type   | status |
|----------------|------|---------|--------|--------|
| B00.CH06.README | B00  | CH06     | readme | draft  |

# B00.CH06 — Definition set IV: caps on income/flows (I-MAX)

This chapter defines the canonical **I-MAX** cap: a binding limit on **income/flows (I)** as a **flow** variable per
time period *t*.

I-MAX is an order instrument, not a moral gesture. It constrains the top-end accumulation of flows that:
- sustain and reward **E-driven extraction** (tolls, monopoly rents, platform take rates, fee stacks),
- and rapidly rebuild **W** via deferral, buybacks, equity grants, and other stock/flow conversion paths.

I-MAX therefore requires:
- a canonical definition of **I** (time-indexed flow with standard resolutions),
- a non-leaky **I-base** (labour, capital, entrepreneurial, and quasi-income),
- rules for **realisation vs deferral** (anti-avoidance in time),
- strict and limited **deductibility** (preventing sham costs and internal fee circles),
- a parameterised cap regime (absolute cap vs cap + skimming),
- explicit cap mechanics, fail-closed posture for ambiguity, and auditable disclosure.

## How to use this chapter

- If you are **writing any later chapter**: import I, I-base, deferral rules, deductibility limits, and cap mechanics
  from here; do not redefine them locally.
- If you are **building datasets/pipelines**: implement component-level income classification, valuation of in-kind
  and equity comp, deferral schedules, and cross-checks against W changes (UBC graph).
- If you are **auditing**: require decomposition of mixed compensation (labour/capital/IP/fees), enforce conservative
  inclusion where components are unclear, and treat black-box compensation structures as non-conform.
- If you are **implementing W-MAX, ΔM or R/B floors**: treat I-MAX as the flow-side brake that prevents rapid claim
  rebuild and limits top-end extraction incentives.

## Structure

P01 — Purpose, scope and normative status of I-MAX  
P02 — Canonical definition of I (income/flow)  
P03 — I-base: what counts in the cap base  
P04 — Realisation and deferral: anti-avoidance in time  
P05 — Netting and costs: what may be deducted  
P06 — I-MAX parameterisation and cap regime  
P07 — Cap mechanics: what happens above I-MAX  
P08 — Interaction with wage formation and working time (link to lived world)  
P09 — Interaction with W-MAX: stock/flow arbitrage  
P10 — Interaction with P/E/C: E-income versus P-income  
P11 — Cross-border income and residency  
P12 — Reporting and publication duty (minimum disclosure)  
P13 — Enforcement and dispute regime  
P14 — Failure modes and hard stops

## Status

This chapter should remain stable across versions because it defines a core cap instrument and its measurement and
enforcement interface. Changes here are high-impact and typically imply major version implications:
- altered definition of I (resolution, realisation moment, consolidation boundary);
- altered I-base inclusions/exclusions (especially equity comp, carried interest, perks, and capital gains treatment);
- altered deferral/realisation rules that change timing outcomes;
- altered deductibility rules and anti-mismatch treatment;
- altered cap mechanics/remedy set or fail-closed posture;
- altered cross-border residency/source rules affecting enforceability.

A “cap” that excludes major income components, permits black-box compensation, or allows deferral to bypass the cap
is non-conform by default and cannot support an OBA compatibility claim.

