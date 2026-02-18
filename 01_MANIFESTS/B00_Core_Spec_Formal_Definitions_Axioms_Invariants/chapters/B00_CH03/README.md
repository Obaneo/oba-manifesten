id: B00.CH03.README
book: B00
chapter: CH03
type: readme
status: draft

# B00.CH03 — Definition set I: production, extraction and commons (P/E/C)

This chapter defines the canonical P/E/C classification used throughout OBA:
**P** (production & maintenance), **E** (extraction), and **C** (commons contribution).

P/E/C is not a rhetorical taxonomy. It is a **functional classification**: a flow is classified by its
**effect on order properties** (power, lock-in, claim layers, capacity maintenance), not by labels,
intent narratives, or ownership form.

The chapter provides:
- the **constitutive definitions** of P, E, and C;
- the **flow-level classification rule** (including minimum metadata);
- the **decomposition rule** (a single payment may contain P+E and sometimes C);
- **power as a structural parameter** (cause of E);
- canonical **edge/border decision rules**;
- linkages to **R/B**, **caps (W-MAX, I-MAX)**, and **ΔM**;
- **measurement/audit standards** and **hard stops** against OBA-washing and black-boxing.

This is a high-impact chapter: later chapters inherit these definitions and MUST NOT redefine them.

## Purpose, scope, normative status

- **Purpose:** provide semantic closure for “productive vs extractive vs commons” at the flow level,
  so that OBA claims are **auditable, reproducible, and contestable**.
- **Scope:** households, firms, state, platforms, finance; micro flows and macro aggregates.
- **Normative status:** constitutive for OBA classification. Deviations are non-conform unless a
  formally defined extension (versioned, with compatibility notes) is explicitly adopted.

## How to use this chapter

If you are writing later chapters:
- Treat P/E/C terms here as **canonical**. Do not redefine them locally.
- Use the edge/border rules when you introduce sector cases, instruments, or reforms.

If you are building datasets or pipelines:
- Implement the **minimum metadata set** and the decomposition logic.
- Ensure classifications are reproducible from recorded inputs (no opaque classifiers).

If you are auditing:
- Require an **audit trail per flow/contract** and reconciliation micro→macro.
- Apply conservative escalation rules where data is missing or controllability is weak.

If you are implementing caps, ΔM rules, commons programs, or consolidation:
- Use P/E/C outputs as inputs: E as a signal for claim-layer pressure and cap relevance;
  C as a constrained destination for reallocation (only under explicit conditions).

## Structure

P01 — Purpose, scope and normative status of P/E/C  
P02 — Definition of P: production and maintenance (productive)  
P03 — Definition of E: extraction (parasitic component)  
P04 — Definition of C: commons contribution (build and maintenance)  
P05 — P/E/C at flow level: classification rule and minimum metadata  
P06 — Decomposition: a single payment can contain P+E (and sometimes C)  
P07 — Power as classification parameter (structural cause of E)  
P08 — Edge cases and border cases (canonical decision rules)  
P09 — Relation to R/B: how E translates into L and remainder space  
P10 — Relation to caps (W-MAX/I-MAX): E as input, caps as brake  
P11 — Measurement and audit standards for P/E/C  
P12 — Failure modes and hard stops

## Status

This chapter should remain stable across versions because it is a core definition set.
Changes here are high-impact and typically imply major version implications:
- altered definitions of P/E/C;
- changed decomposition or escalation rules;
- changed minimum metadata / audit requirements;
- altered edge/border decision rules affecting classification outcomes.

Non-auditable or black-box classification is non-conform by default.

