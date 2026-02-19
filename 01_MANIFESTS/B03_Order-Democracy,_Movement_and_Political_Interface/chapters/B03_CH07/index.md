| id            | book | chapter | type       | status |
|---------------|------|---------|------------|--------|
| B03.CH07.INDEX | B03  | CH07    | chapter-index | draft  |

# B03.CH07 — Forks and compatibility: variants, name usage, and the OBA compatibility test

This chapter outlines the principles surrounding **forks** and **variants** in the context of **OBA** (Order-Based Architecture). It defines when deviations from core OBA rails are acceptable (i.e., forks and variants) and establishes guidelines for maintaining **compatibility** within the OBA framework. The **OBA compatibility test** is central to ensuring that variations do not erode the foundational principles of OBA. Furthermore, this chapter discusses the importance of **naming conventions**, the rules against **semantic drift**, and the processes for formalizing forks through the **fork protocol**.

---

## Paragraphs

- [B03.CH07.P01 — Purpose and delimitation: forks as necessary plurality without losing the core](./P01.md)
  - [B03.CH07.P01.S01 — Why variants are inevitable (context, culture, shocks)](./P01.md#b03ch07p01s01)
  - [B03.CH07.P01.S02 — Why name usage is not optional (prevent semantic drift)](./P01.md#b03ch07p01s02)
  - [B03.CH07.P01.S03 — Delimitation: economic definitions remain canonical in the Kernel Spec / Book 1](./P01.md#b03ch07p01s03)
  - [B03.CH07.P01.S04 — Output: formal fork protocol + compatibility test + registries](./P01.md#b03ch07p01s04)

- [B03.CH07.P02 — Conceptual framework: fork, variant, extension, and incompatibility](./P02.md)
  - [B03.CH07.P02.S01 — Fork: deviation on constitutive rails (non-negotiables or definitions)](./P02.md#b03ch07p02s01)
  - [B03.CH07.P02.S02 — Variant: parametric deviation within rails (thresholds, pace, priorities)](./P02.md#b03ch07p02s02)
  - [B03.CH07.P02.S03 — Extension: additional modules without changing the core (add-on, optional)](./P02.md#b03ch07p02s03)
  - [B03.CH07.P02.S04 — Incompatibility: break in measurability/auditability/contestability](./P02.md#b03ch07p02s04)
  - [B03.CH07.P02.S05 — Naming conventions: labels for compatible, partial, non-compatible](./P02.md#b03ch07p02s05)

- [B03.CH07.P03 — Name usage: rules against semantic regression and washing](./P03.md)
  - [B03.CH07.P03.S01 — “OBA” as a reserved label: conditions for use](./P03.md#b03ch07p03s01)
  - [B03.CH07.P03.S02 — Prohibited misrepresentation: OBA language applied to OOA practice (washing)](./P03.md#b03ch07p03s02)
  - [B03.CH07.P03.S03 — “OBA-compatible” versus “OBA-inspired”: status labels](./P03.md#b03ch07p03s03)
  - [B03.CH07.P03.S04 — Public disclosure: which rails deviate and why](./P03.md#b03ch07p03s04)
  - [B03.CH07.P03.S05 — Enforcement: sanctions for mislabeling in policy / commons / governance](./P03.md#b03ch07p03s05)

- [B03.CH07.P04 — Compatibility test: minimum criteria (pass/fail)](./P04.md)
  - [B03.CH07.P04.S01 — E: measurable reduction of toll/claim extraction (function-over-label)](./P04.md#b03ch07p04s01)
  - [B03.CH07.P04.S02 — Caps: binding, no structural carve-outs, no threshold tricks](./P04.md#b03ch07p04s02)
  - [B03.CH07.P04.S03 — Commons/ΔG: open access within boundary rules + maintenance discipline](./P04.md#b03ch07p04s03)
  - [B03.CH07.P04.S04 — R/B: lower bounds and distributive improvement (p10/p25/median)](./P04.md#b03ch07p04s04)
  - [B03.CH07.P04.S05 — ΔM: channel allocation testable, allocation contestable, no black boxes](./P04.md#b03ch07p04s05)
  - [B03.CH07.P04.S06 — Auditability: open definitions, logging, replicability, restatements](./P04.md#b03ch07p04s06)

- [B03.CH07.P05 — Process: how a fork/variant is formally established](./P05.md)
  - [B03.CH07.P05.S01 — Initiation: proposal with delta on rails, rationale, and impact analysis](./P05.md#b03ch07p05s01)
  - [B03.CH07.P05.S02 — Evidence: measurement plan, audit plan, uncertainty bands, “unknown” discipline](./P05.md#b03ch07p05s02)
  - [B03.CH07.P05.S03 — Review: independent audit + public consultation (where appropriate)](./P05.md#b03ch07p05s03)
  - [B03.CH07.P05.S04 — Decision: classification (variant/extension/fork) + name label](./P05.md#b03ch07p05s04)
  - [B03.CH07.P05.S05 — Publication: changelog, definition set, compatibility scorecard](./P05.md#b03ch07p05s05)

- [B03.CH07.P06 — Registries and version control: traceability over time and jurisdictions](./P06.md)
  - [B03.CH07.P06.S01 — Fork registry: unique IDs, scope, status, date, rationale](./P06.md#b03ch07p06s01)
  - [B03.CH07.P06.S02 — Definition sets: version pinning and backward compatibility rules](./P06.md#b03ch07p06s02)
  - [B03.CH07.P06.S03 — Bridging: mapping between variants for comparison and migration](./P06.md#b03ch07p06s03)
  - [B03.CH07.P06.S04 — Deprecation: sunset of failed forks/variants, migration paths](./P06.md#b03ch07p06s04)
  - [B03.CH07.P06.S05 — Interoperability: minimum cross-border compatibility metadata](./P06.md#b03ch07p06s05)

- [B03.CH07.P07 — Governance implications: pluralism without fragmentation](./P07.md)
  - [B03.CH07.P07.S01 — Federated governance: local variants with central invariants](./P07.md#b03ch07p07s01)
  - [B03.CH07.P07.S02 — Conflict arbitration: who decides in a compatibility dispute](./P07.md#b03ch07p07s02)
  - [B03.CH07.P07.S03 — Prevention of “fork shopping”: incentives and enforcement](./P07.md#b03ch07p07s03)
  - [B03.CH07.P07.S04 — Reintegration: conditions for return to compatible rails](./P07.md#b03ch07p07s04)
  - [B03.CH07.P07.S05 — Break management: when separation is better than sham unity](./P07.md#b03ch07p07s05)

- [B03.CH07.P08 — Abuse patterns: strategic forks and façade variants](./P08.md)
  - [B03.CH07.P08.S01 — Token forks: rhetoric only, no measurable changes in E/RB/caps/ΔG/ΔM](./P08.md#b03ch07p08s01)
  - [B03.CH07.P08.S02 — Capture forks: exceptions built in for insiders](./P08.md#b03ch07p08s02)
  - [B03.CH07.P08.S03 — Authoritarian forks: overreach, surveillance, selective enforcement](./P08.md#b03ch07p08s03)
  - [B03.CH07.P08.S04 — Vendor forks: black-box allocation and proprietary measurement regimes](./P08.md#b03ch07p08s04)
  - [B03.CH07.P08.S05 — Detection: exception ratio↑, sanction rate↓, reproducibility↓, E↑](./P08.md#b03ch07p08s05)

- [B03.CH07.P09 — Correction mechanisms: what to do under incompatibility or mislabeling](./P09.md)
  - [B03.CH07.P09.S01 — Semantic correction: enforce relabeling and public rectification](./P09.md#b03ch07p09s01)
  - [B03.CH07.P09.S02 — Institutional correction: audit escalation, hard stops, governance reset](./P09.md#b03ch07p09s02)
  - [B03.CH07.P09.S03 — Legal correction: sanctions, withdrawal of label, remedial measures](./P09.md#b03ch07p09s03)
  - [B03.CH07.P09.S04 — Economic correction: neutralisation of extraction and contract rollback](./P09.md#b03ch07p09s04)
  - [B03.CH07.P09.S05 — Exit criteria: when formally “no longer OBA” (link to B03.CH12)](./P09.md#b03ch07p09s05)

- [B03.CH07.P10 — Integration with tests: compatibility as an input for democratic consistency](./P10.md)
  - [B03.CH07.P10.S01 — Compatibility status as a parameter in policy mandates](./P10.md#b03ch07p10s01)
  - [B03.CH07.P10.S02 — Public scorecards per variant/fork](./P10.md#b03ch07p10s02)
  - [B03.CH07.P10.S03 — Audit requirements per status (compatible vs partial vs non-compatible)](./P10.md#b03ch07p10s03)
  - [B03.CH07.P10.S04 — Scenario and shock stress: forks under crisis pressure](./P10.md#b03ch07p10s04)
  - [B03.CH07.P10.S05 — Version control: lessons learned without core break (traceable changelog)](./P10.md#b03ch07p10s05)

---
