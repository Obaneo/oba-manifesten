| id             | book | chapter | type          | status |
|----------------|------|---------|---------------|--------|
| B05.CH01.INDEX | B05  | CH01    | chapter-index | draft  |

# B05.CH01 — Kernel: the lifeworld layer as a test (from macro-invariants to experienced GROSS/NET/BURDENS)

This chapter defines the **lifeworld layer** as a **formal validation interface** for OBA: it translates macro-invariants (P/E/C, B/T/N/L/R, caps W/I, ΔM rails, commons ΔG) into **experienced quantities** and testable observables, and it treats “day-in-the-life” and sector cases as **regression tests** against clamp dynamics, fee stacks, and drift.  
Nothing here introduces new canonical definitions: B05.CH01 only specifies **translation rules, measurement rails, contestability requirements, and fail-closed conditions** for lifeworld compatibility.

---

## Paragraphs

- [B05.CH01.P01 — Purpose and status of the lifeworld layer](./P01.md)
  - [B05.CH01.P01.S01 — Lifeworld layer as a test layer: not narrative, but a validation interface](./P01.md#b05ch01p01s01)
  - [B05.CH01.P01.S02 — Relation to Kernel Spec and Codex: derived claims, no new definitions](./P01.md#b05ch01p01s02)
  - [B05.CH01.P01.S03 — Why this is not optional: legitimacy, detection of washing, resistance to framing](./P01.md#b05ch01p01s03)
  - [B05.CH01.P01.S04 — Fail-closed principle: if the lifeworld test cannot be executed, the implementation is incomplete](./P01.md#b05ch01p01s04)

- [B05.CH01.P02 — Translation function: from macro-invariants to experienced quantities](./P02.md)
  - [B05.CH01.P02.S01 — Map: P/E/C → households, contracts, prices, access, maintenance](./P02.md#b05ch01p02s01)
  - [B05.CH01.P02.S02 — Map: B,T,N,L,R → “agenda reality” (what can I pay/do without being clamped)](./P02.md#b05ch01p02s02)
  - [B05.CH01.P02.S03 — Map: caps (W/I) → status incentives, career paths, everyday circumvention routes](./P02.md#b05ch01p02s03)
  - [B05.CH01.P02.S04 — Map: ΔM → visible channel effects (essentials, commons, prohibited asset/claim support)](./P02.md#b05ch01p02s04)

- [B05.CH01.P03 — The minimal “experience set” per household (testable observables)](./P03.md)
  - [B05.CH01.P03.S01 — Minimum: GROSS (B) and composition (labour/capital/transfers/in-kind)](./P03.md#b05ch01p03s01)
  - [B05.CH01.P03.S02 — Minimum: NET (N) and levies (T), including timing and predictability](./P03.md#b05ch01p03s02)
  - [B05.CH01.P03.S03 — Minimum: BURDENS (L) essentials basket with lock-in/exit-friction markers](./P03.md#b05ch01p03s03)
  - [B05.CH01.P03.S04 — Minimum: RESIDUAL SPACE (R) and R/B profile (incl. volatility and tail-risk)](./P03.md#b05ch01p03s04)

- [B05.CH01.P04 — Lifeworld test as a “contract clamp test”](./P04.md)
  - [B05.CH01.P04.S01 — Lock-in detection: exit fees, exclusivity, portability, switching-cost proxies](./P04.md#b05ch01p04s01)
  - [B05.CH01.P04.S02 — Toll-layer detection: fee stacks in essentials (housing/energy/care/digital)](./P04.md#b05ch01p04s02)
  - [B05.CH01.P04.S03 — Block-power detection: choke points (platform/rail/identity/logistics) in daily routines](./P04.md#b05ch01p04s03)
  - [B05.CH01.P04.S04 — Remedy implication: unbundling, public option, procurement rails, reclassification](./P04.md#b05ch01p04s04)

- [B05.CH01.P05 — Signal → analysis → norming → intervention as a lifeworld implementation pattern](./P05.md)
  - [B05.CH01.P05.S01 — Signal discipline: which lived signals count (without data maximalism)](./P05.md#b05ch01p05s01)
  - [B05.CH01.P05.S02 — Analysis: make the causal chain explicit (ΔM→commons→L→R/B) with uncertainty](./P05.md#b05ch01p05s02)
  - [B05.CH01.P05.S03 — Norming: thresholds (α, baseline access, lock-in caps) and conflict rules](./P05.md#b05ch01p05s03)
  - [B05.CH01.P05.S04 — Intervention templates: repeatable interventions (no ad-hoc deals), with measurement and rollback path](./P05.md#b05ch01p05s04)

- [B05.CH01.P06 — CSA as a public correction loop (Collective Situation Audit)](./P06.md)
  - [B05.CH01.P06.S01 — CSA output: periodic public dashboards from public tables (no “dashboard-only”)](./P06.md#b05ch01p06s01)
  - [B05.CH01.P06.S02 — CSA cadence: periodic + event-driven (shocks, price breaks, governance incidents)](./P06.md#b05ch01p06s02)
  - [B05.CH01.P06.S03 — CSA contestability: citizens/organisations can challenge claims via dispute flow](./P06.md#b05ch01p06s03)
  - [B05.CH01.P06.S04 — CSA anti-capture: audit the guardian, rotation, transparency on exceptions](./P06.md#b05ch01p06s04)

- [B05.CH01.P07 — Non-reductive measurement rails: autonomy, privacy, and contestability](./P07.md)
  - [B05.CH01.P07.S01 — Ban on reduction: wellbeing/agency is not a single KPI; metrics are bounded signals](./P07.md#b05ch01p07s01)
  - [B05.CH01.P07.S02 — Autonomy rails: measurement duty must not become behavioural coercion or surveillance rent](./P07.md#b05ch01p07s02)
  - [B05.CH01.P07.S03 — Experience evidence: qualitative signals as formal input (with a testable procedure, not “anecdote”)](./P07.md#b05ch01p07s03)
  - [B05.CH01.P07.S04 — Risk: cognitive capture via “well-intended” optimisation; mitigation via plurality and contestability](./P07.md#b05ch01p07s04)

- [B05.CH01.P08 — Evolutionary infrastructure: institutions that can correct without drift](./P08.md)
  - [B05.CH01.P08.S01 — Modular change: patches, pilots, rollback, deprecation (no semantic break)](./P08.md#b05ch01p08s01)
  - [B05.CH01.P08.S02 — Maintenance-first in institutions: execution capacity as a commons (ΔG of governance)](./P08.md#b05ch01p08s02)
  - [B05.CH01.P08.S03 — Learning systems: feedback into Codex/benchmarks with version control and restatements](./P08.md#b05ch01p08s03)
  - [B05.CH01.P08.S04 — Stability versus adaptation: what is invariant (kernel) and what evolves parametrically (practice)](./P08.md#b05ch01p08s04)

- [B05.CH01.P09 — Lifeworld compatibility: minimum criteria for “OBA works for people”](./P09.md)
  - [B05.CH01.P09.S01 — Criterion 1: L declines or becomes contestable (exit without clamp) in essentials](./P09.md#b05ch01p09s01)
  - [B05.CH01.P09.S02 — Criterion 2: share_below_alpha declines and tails stabilise (not just median gain)](./P09.md#b05ch01p09s02)
  - [B05.CH01.P09.S03 — Criterion 3: commons access and maintenance visibly improve (ΔG positive and auditable)](./P09.md#b05ch01p09s03)
  - [B05.CH01.P09.S04 — Criterion 4: circumvention is functionally recognised and sanctioned (no sham compliance)](./P09.md#b05ch01p09s04)

- [B05.CH01.P10 — Measurement and publication requirements specific to the lifeworld layer](./P10.md)
  - [B05.CH01.P10.S01 — Public tables: cohort profiles, essentials indices, lock-in proxies, incidents (aggregated)](./P10.md#b05ch01p10s01)
  - [B05.CH01.P10.S02 — Privacy minimalism: no person tracking; join safety; suppression for small-n](./P10.md#b05ch01p10s02)
  - [B05.CH01.P10.S03 — Reproducibility: method_id, definition-set ID, uncertainty bands, revision policy](./P10.md#b05ch01p10s03)
  - [B05.CH01.P10.S04 — Hard stop: unobservable claims (“trust me”) → no lifeworld-compatibility label](./P10.md#b05ch01p10s04)

- [B05.CH01.P11 — Interface with sector cases and day-in-the-life chapters](./P11.md)
  - [B05.CH01.P11.S01 — Templates: applying the same test logic to housing/energy/care/digital](./P11.md#b05ch01p11s01)
  - [B05.CH01.P11.S02 — Case structure: before/after, clamps, exit paths, institutional interventions, measurement outputs](./P11.md#b05ch01p11s02)
  - [B05.CH01.P11.S03 — Link to sector canvas: bottlenecks, E sources, commons option, cap compatibility, R/B effect](./P11.md#b05ch01p11s03)
  - [B05.CH01.P11.S04 — Link to Codex: which schemas, validators, and audit packs are mandatory per case](./P11.md#b05ch01p11s04)

- [B05.CH01.P12 — Failure modes of the lifeworld layer (and why they are systemic)](./P12.md)
  - [B05.CH01.P12.S01 — Technocratic drift: KPIs defeat agency; mitigation via CSA + contestability](./P12.md#b05ch01p12s01)
  - [B05.CH01.P12.S02 — Bureaucratic over-measurement: data maximalism → surveillance and execution failure (non-conforming)](./P12.md#b05ch01p12s02)
  - [B05.CH01.P12.S03 — Narrative capture: cosmetic “day-in-the-life” without measurement linkage → washing](./P12.md#b05ch01p12s03)
  - [B05.CH01.P12.S04 — Selective execution: differences by region/class without transparency → legitimacy breach and sabotage risk](./P12.md#b05ch01p12s04)
