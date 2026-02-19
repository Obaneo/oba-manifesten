| id              | book | chapter | type   | status |
|-----------------|------|---------|--------|--------|
| B03.CH05.README | B03  | CH05    | readme | draft  |

# B03.CH05 — Institutional design: separation of powers, audit, transparency, and sanctions

This chapter defines the **institutional machinery** required to keep OBA governance stable under political pressure, market
adaptation, and endogenous capture dynamics. Its focus is not “good government” in the abstract, but **anti-capture infrastructure**:
clear separation of functions, enforceable evidence discipline, contestability without paralysis, and a sanctions/exception regime
that prevents semantic drift and permanent carve-outs.

Institutions operationalise the order: they transform **norms and rails** into **repeatable behaviour**, with logging, audits, and
remedies that neutralise extraction rather than merely condemning it. The chapter also specifies the transparency surface (public
definitions, registers, dashboards), hard stops under measurement or black-box failure, and procurement/vendor governance to prevent
tooling lock-in from becoming a hidden veto layer.

## How to use this chapter

- If you are **designing governance**: use CH05 as the blueprint for minimum institutional roles (execution, audit, oversight,
  judicial review) and the separation rails that prevent role mixing and revolving-door capture.
- If you are **writing mandates or laws**: import the transparency, auditability, exception, and sanctions requirements here;
  do not improvise bespoke regimes that create loopholes.
- If you are **building systems and tooling**: implement logging, version pinning, reproducibility and register outputs as specified
  here; “closed computation” is treated as a governance failure mode.
- If you are **auditing an OBA implementation**: use the failure modes and early-warning indicators to structure audit plans,
  escalation ladders, and hard-stop triggers.

## Structure

P01 — Purpose and delimitation: institutional design as anti-capture infrastructure  
P02 — Separation of functions: execution, audit, oversight, and judicial review  
P03 — Powers and checks: who may do what, under which conditions  
P04 — Transparency architecture: public definitions, registers, and dashboards  
P05 — Audit design: assurance, sampling, triggers, and hard stops  
P06 — Enforcement: detection → qualification → remedy (function over label)  
P07 — Sanctions architecture: escalation ladder and neutralisation of extraction  
P08 — Exception regime: governance, sunsets, and rollback as an anti-drift mechanism  
P09 — Procurement and vendor governance: preventing lock-in and black-box institutions  
P10 — Financial and organisational independence: budget, staffing, and mandates  
P11 — Escalation and intervention: when institutions must correct themselves  

## Status

This chapter is **normative** for any governance design that claims OBA compatibility. The minimum institutional set, transparency
surface, auditability requirements, exception discipline, and vendor/lock-in rails are treated as **constitutive** for Book 3: if
they are weakened (or replaced by black-box discretion), the implementation must be treated as drifting toward incompatibility and
must trigger escalation paths (including potential fork classification and relabeling where applicable).

