| id             | book | chapter | type   | status |
|----------------|------|---------|--------|--------|
| B03.CH02.README | B03  | CH02    | readme | draft  |

# B03.CH02 — Order-democracy: what is decided, what is invariant, and why

This chapter defines **order-democracy** as the democratic regime compatible with OBA: ordinary politics operates within a set
of **constitutive rails** (non-negotiables), enforced through **procedure**, **evidence discipline**, and **contestability**.

Order-democracy is **not technocracy**. It does not replace political choice with expert rule. It constrains *how* decisions are
made and *what cannot be decided* under ordinary politics, because democratic mechanisms can otherwise be used as an **attack
vector** to erode caps, commons, auditability, and E-reduction via **semantic drift**, **exception stacking**, or **black-box
allocation**.

## How to use this chapter

- Use **P02 (Decision space)** to classify decisions by order impact. The classification determines the required mandate type,
  procedure, evidence standards, and whether a **fork decision** is required.
- Use **P03 (Invariants)** as a fail-closed checklist: if a proposal weakens caps, E-reduction, commons access/maintenance,
  measurability/auditability, or contestability, it must not proceed under ordinary politics.
- Use **P06–P07 (Procedural architecture + no-go zones)** to design institutions and workflows that prevent drift: versioned
  definition sets, public changelogs, exception registers, hard stops, and non-sabotage defaults.
- Use **P08 (Conflict and pluralism)** to distinguish legitimate conflict *within rails* from illegitimate conflict aimed at
  breaking rails, and to route escalation to fork/compatibility procedures when needed.

## Structure

P01 — Problem statement: democracy without order invariants is capture-prone  
P02 — Decision space: classification of decisions by order impact  
P03 — Invariants: what cannot be hollowed out by ordinary politics  
P04 — Why these invariants are democratically justified  
P05 — Mandate structure: how legitimacy is tied to order criteria  
P06 — Procedural architecture: decision-making with built-in anti-drift  
P07 — Limits of democratic choice: forbidden routes and “no-go zones”  
P08 — Conflict and pluralism within order-democracy  

## Interfaces

- **Kernel Spec**: canonical definitions and calculation rules (refer; do not redefine).
- **B03.CH03**: legitimacy criteria and mandate operationalisation.
- **B03.CH05 / B03.CH10**: institutional design and anti-capture mechanisms implementing the rails.
- **B03.CH07**: fork classification and compatibility/name usage when constitutive rails are changed.
- **B03.CH12**: democratic consistency test and governance metrics evaluating drift/capture over time.

## Status

This chapter is **normative** for the governance layer of Book 3. Any implementation claiming OBA status must preserve the
decision-type distinctions, invariants, and procedural rails defined here; deviations must be treated as **forks/variants**
and labeled accordingly under the compatibility regime.

