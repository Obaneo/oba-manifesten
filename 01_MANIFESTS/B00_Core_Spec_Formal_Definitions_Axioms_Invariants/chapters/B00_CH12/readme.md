| id              | book | chapter | type   | status |
|-----------------|------|---------|--------|--------|
| B00.CH12.README | B00  | CH12    | readme | draft  |

# B00.CH12 — Evidence and measurement standards: observability, auditability, reproducibility, uncertainty

This chapter defines the **evidence and measurement standards** required to make any OBA claim **testable, auditable, and enforceable**.
It specifies minimum requirements for **observability**, **method registration**, **audit lineage**, **reproducibility**, and **uncertainty reporting**.
The core rule is an order invariant: **without evidence there is no compatibility claim**. Any claim that depends on black-box methods,
non-traceable data, or unverifiable metrics is treated as **non-conform**.

The chapter also defines governance against **measurement-washing** (dashboards without traceable data), **black-box decisioning**,
and **metric gaming** (Goodhart). It establishes minimum publication and dispute procedures so that measurements and claims can be
contested and corrected without semantic drift.

## How to use this chapter

- If you are **publishing an OBA-compatible implementation**: ensure your measurement system meets the minimum **observables** and
  **auditability** requirements; register methods with definition-set ID + version and publish uncertainty bands.
- If you are **auditing or certifying**: apply the end-to-end lineage checks (claim → data → transformation → metric → decision);
  reject proprietary or non-reproducible methods for critical decisions.
- If you are **making causal or effect claims** (“this improves R/B”, “this reduces E”): use counterfactual discipline and publish
  mechanism chains and confounding checks; narrative without testing is non-conform.
- If you are **governing metrics**: enforce triangulation, rotation, and anti-gaming monitoring; prohibit single-metric decisions.
- If you are **handling disputes**: use the dispute protocol to challenge measurements, force restatements, and suspend status when
  reproducibility or lineage is lost (fail-closed).

## Structure

P01 — Purpose, scope and normative status of evidence and measurement standards  
P02 — Observability: what must be measurable (minimum observables)  
P03 — Measurement methods: definitions, procedures and minimum metadata  
P04 — Auditability: traceability and controllable chains  
P05 — Reproducibility and replication  
P06 — Uncertainty: intervals, error margins and conservatism  
P07 — Attribution and causality (claims about effects)  
P08 — Publication requirements and transparency  
P09 — Dispute protocol: contesting measurements and claims  
P10 — Anti-Goodhart: metric governance  
P11 — Tooling and model standards (incl. AI)  
P12 — Failure modes and hard stops  

## Status

This chapter is **normative** for evidence, measurement, and publication requirements in OBA. Any compatibility label that cannot
meet these standards MUST be treated as **non-conform** until evidence, lineage, and reproducibility are restored.

