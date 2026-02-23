| id             | book | chapter | type          | status |
|----------------|------|---------|---------------|--------|
| B05.CH18.INDEX | B05  | CH18    | chapter-index | draft  |

<a id="b05ch18index"></a>
# B05.CH18 — Failure modes in the lifeworld: resentment, sabotage, evasion, bureaucratic drift, capture

This chapter specifies **lifeworld failure modes** as a normative early-warning and stop-rule system for OBA implementations. It targets
a recurrent pattern: systems that “formally comply” with written rules while **breaking the lifeworld** through friction, opacity,
selective execution, or extraction shifts. CH18 therefore defines a failure-mode taxonomy, detection indicators, escalation paths, and
FAIL-CLOSED stop rules that block scaling and force remediation.

CH18 binds directly to the lifeworld test (**B,T,N,L,R + tails + time friction**), and to OBA’s rails for **contestability, auditability,
anti-evasion, and crisis handling**. It functions as the enforcement layer that prevents Book 5 from degrading into narrative.

---

## Conformance summary (chapter-level gates)

A conform OBA implementation **MUST**:
- Run lifeworld tests continuously (B,T,N,L,R + tails + time friction) and publish early-warning dashboards in aggregated form.
- Treat repeated breach indicators as stop conditions (FAIL-CLOSED): scaling blocked until remediation passes re-test.
- Maintain contestability (appeals, interim relief, anti-retaliation), auditability (tamper-evident logs), and anti-evasion (shift taxonomy,
  channel controls) as constitutive rails.
- Prevent drift/capture via audit-on-the-auditor, procurement discipline, privacy rails, and exception controls.

A conform OBA implementation **MUST NOT**:
- Substitute comms/narrative management for material L/tail improvements and repair paths.
- Use data maximalism/surveillance as “measurement”; microdata publication is prohibited.
- Allow carve-outs, shadow regimes, selective enforcement, or silent rule drift.

---

## Paragraphs

- [B05.CH18.P01 — Purpose, scope, and normative status of lifeworld failure modes](./P01.md)
  - [B05.CH18.P01.S01 — Purpose: systematic early-warning and stop rules for implementations that “formally comply” but break the lifeworld](./P01.md#b05ch18p01s01)
  - [B05.CH18.P01.S02 — Scope: resentment, sabotage, evasion, bureaucratic drift, capture (local/national/sector)](./P01.md#b05ch18p01s02)
  - [B05.CH18.P01.S03 — Binding: lifeworld test (B,T,N,L,R + tails), contestability, auditability, anti-evasion, and crisis rails](./P01.md#b05ch18p01s03)
  - [B05.CH18.P01.S04 — Fail-closed: when breach indicators repeat, scaling is blocked and remediation is mandatory](./P01.md#b05ch18p01s04)

- [B05.CH18.P02 — Failure-mode taxonomy: five classes and their causal logic](./P02.md)
  - [B05.CH18.P02.S01 — Resentment: experienced injustice/friction despite macro claims (perception ≠ propaganda, but a signal)](./P02.md#b05ch18p02s01)
  - [B05.CH18.P02.S02 — Sabotage: active interference via non-compliance, strikes, understaffing, slow-roll, vandalism](./P02.md#b05ch18p02s02)
  - [B05.CH18.P02.S03 — Evasion: extraction shifts into new forms/channels (legal/technical/financial/international)](./P02.md#b05ch18p02s03)
  - [B05.CH18.P02.S04 — Drift/capture: institutions shift toward self-preservation, data maximalism, vendor lock-in, exception culture](./P02.md#b05ch18p02s04)

- [B05.CH18.P03 — Resentment: mechanism (why it emerges)](./P03.md)
  - [B05.CH18.P03.S01 — L stays high or unpredictable: essentials costs do not visibly fall, or volatility/tails rise](./P03.md#b05ch18p03s01)
  - [B05.CH18.P03.S02 — Administrative friction: “rights” exist, but access requires time, shame, or digital hurdles](./P03.md#b05ch18p03s02)
  - [B05.CH18.P03.S03 — Symbolism > materiality: narratives/rituals without measurable improvement (ΔG/L/RB)](./P03.md#b05ch18p03s03)
  - [B05.CH18.P03.S04 — Status shock: old status pathways vanish without new legitimate arenas (link to CH13)](./P03.md#b05ch18p03s04)

- [B05.CH18.P04 — Resentment: detection and indicators (early warning)](./P04.md)
  - [B05.CH18.P04.S01 — Cohort fractures: certain regions/occupations see L rise or tails worsen relative to median gains](./P04.md#b05ch18p04s01)
  - [B05.CH18.P04.S02 — Friction indicators: cycle times, drop-off, appeal rates, wait-time spikes, erroneous decisions](./P04.md#b05ch18p04s02)
  - [B05.CH18.P04.S03 — “Non-belief” as a signal: mismatch between dashboards and experience reporting (procedurally collected)](./P04.md#b05ch18p04s03)
  - [B05.CH18.P04.S04 — Media/platform signals: rising misinformation susceptibility at concrete friction points (no moralizing)](./P04.md#b05ch18p04s04)

- [B05.CH18.P05 — Resentment: mitigation (what works structurally)](./P05.md)
  - [B05.CH18.P05.S01 — L-first correction: accelerate essentials price rails/commons exits before additional redistribution narratives](./P05.md#b05ch18p05s01)
  - [B05.CH18.P05.S02 — Friction reduction: one-stop shop, standard procedures, minimal evidentiary burden, fast interim relief](./P05.md#b05ch18p05s02)
  - [B05.CH18.P05.S03 — Transparency with repair: public incident logs + restatements + visible repair path (not “PR”)](./P05.md#b05ch18p05s03)
  - [B05.CH18.P05.S04 — Plurality and contestability: strengthen dissent/challenge infrastructure rather than communications management](./P05.md#b05ch18p05s04)

- [B05.CH18.P06 — Sabotage: mechanism and forms](./P06.md)
  - [B05.CH18.P06.S01 — Operational sabotage: paper compliance, deliberate degradation of data quality, execution delays](./P06.md#b05ch18p06s01)
  - [B05.CH18.P06.S02 — Labor conflict: failures in key capacities (healthcare, grid ops, administration) in response to overload or status loss](./P06.md#b05ch18p06s02)
  - [B05.CH18.P06.S03 — Political sabotage: carve-outs, exceptions, maintenance budget hollowing, vetoes on interop/standards](./P06.md#b05ch18p06s03)
  - [B05.CH18.P06.S04 — Market sabotage: price manipulation, supply withholding, intensified lock-in by dominant providers](./P06.md#b05ch18p06s04)

- [B05.CH18.P07 — Sabotage: detection and escalation](./P07.md)
  - [B05.CH18.P07.S01 — Integrity indicators: logging anomalies, missing lineage, signature mismatches, “silent edits”](./P07.md#b05ch18p07s01)
  - [B05.CH18.P07.S02 — Performance fractures: sudden increases in cycle times/backlogs without an external shock](./P07.md#b05ch18p07s02)
  - [B05.CH18.P07.S03 — Concentration/market signals: collusion indicators, margin spikes, deeper fee stacks](./P07.md#b05ch18p07s03)
  - [B05.CH18.P07.S04 — Escalation path: anomaly → forensic audit → governance reset/remedies → (if needed) temporary intervention](./P07.md#b05ch18p07s04)

- [B05.CH18.P08 — Sabotage: mitigation and hard stops](./P08.md)
  - [B05.CH18.P08.S01 — Capacity-first: ringfence execution capacity and maintenance budgets (ΔG of governance)](./P08.md#b05ch18p08s01)
  - [B05.CH18.P08.S02 — Separation of powers: strictly separate decision/execution/oversight/appeal; rotate key roles](./P08.md#b05ch18p08s02)
  - [B05.CH18.P08.S03 — Procurement rails: standardize vendor lock-in triggers (escrow/open standards) and exit assistance](./P08.md#b05ch18p08s03)
  - [B05.CH18.P08.S04 — Hard stop: proven selective enforcement or integrity breach → immediate suspension of conformance claims](./P08.md#b05ch18p08s04)

- [B05.CH18.P09 — Evasion: core logic (why it is systemic)](./P09.md)
  - [B05.CH18.P09.S01 — Incentives shift: caps/rails change payoffs; actors search for new claim routes](./P09.md#b05ch18p09s01)
  - [B05.CH18.P09.S02 — Semantic arbitrage: new labels and contract forms attempt to bypass definitions](./P09.md#b05ch18p09s02)
  - [B05.CH18.P09.S03 — Channel innovation: new rails (fintech/crypto), new intermediation, new bundles](./P09.md#b05ch18p09s03)
  - [B05.CH18.P09.S04 — International arbitrage: treaty mismatch, re-domiciliation, transfer pricing, IP structures](./P09.md#b05ch18p09s04)

- [B05.CH18.P10 — Evasion: detection (shift taxonomy in a lifeworld context)](./P10.md)
  - [B05.CH18.P10.S01 — Legal shifts: reclassification into services/licenses/consultancy; franchise and royalty stacks](./P10.md#b05ch18p10s01)
  - [B05.CH18.P10.S02 — Technical shifts: bundling, dark patterns, API gating, pay-to-unlock, identity as a clamp](./P10.md#b05ch18p10s02)
  - [B05.CH18.P10.S03 — Financial shifts: securitization, fee stacks, synthetics, leverage as hidden exposure](./P10.md#b05ch18p10s03)
  - [B05.CH18.P10.S04 — International shifts: treaty shopping, IP-box, nominee ownership, offshore conduits (UBC graphs)](./P10.md#b05ch18p10s04)

- [B05.CH18.P11 — Evasion: remedies (reclassification and channel control)](./P11.md)
  - [B05.CH18.P11.S01 — Reclassification: substance-over-form, look-through, presumptions under opacity (fail-closed)](./P11.md#b05ch18p11s01)
  - [B05.CH18.P11.S02 — Contract remedies: prohibited clauses, standard templates, unbundling, take-rate caps, portability mandates](./P11.md#b05ch18p11s02)
  - [B05.CH18.P11.S03 — Channel remedies: tagging, leakage tests, forbidden channels, rail governance with due process](./P11.md#b05ch18p11s03)
  - [B05.CH18.P11.S04 — Versioning: rapid updates via Codex + transparent precedent registry (without core break)](./P11.md#b05ch18p11s04)

- [B05.CH18.P12 — Bureaucratic drift: mechanism (how “good intentions” fail)](./P12.md)
  - [B05.CH18.P12.S01 — Metric drift: measurement becomes the goal; Goodhart shifts behavior toward scores instead of lifeworld gains](./P12.md#b05ch18p12s01)
  - [B05.CH18.P12.S02 — Over-measurement and data maximalism: privacy breach + execution load (administrative L) rises](./P12.md#b05ch18p12s02)
  - [B05.CH18.P12.S03 — Procedure inflation: exceptions, counters, evidentiary burden grow; access becomes a gatekeeping ecosystem](./P12.md#b05ch18p12s03)
  - [B05.CH18.P12.S04 — Tooling capture: systems become complex and vendor-dependent; contestability disappears](./P12.md#b05ch18p12s04)

- [B05.CH18.P13 — Bureaucratic drift: detection and correction](./P13.md)
  - [B05.CH18.P13.S01 — L via administration: rising cycle time, paperwork burden, drop-off, appeal backlog](./P13.md#b05ch18p13s01)
  - [B05.CH18.P13.S02 — “Dashboard without remedy”: lots of reporting, little redesign, few restatements](./P13.md#b05ch18p13s02)
  - [B05.CH18.P13.S03 — Privacy incidents: scope creep, secondary use, identity-linkage without necessity](./P13.md#b05ch18p13s03)
  - [B05.CH18.P13.S04 — Correction: simplification sprints, data-minimalism audits, deprecate procedures, tooling unbundling](./P13.md#b05ch18p13s04)

- [B05.CH18.P14 — Capture: forms (economic, political, epistemic)](./P14.md)
  - [B05.CH18.P14.S01 — Economic capture: vendors/sectors steer procurement, standards, exceptions (carve-outs)](./P14.md#b05ch18p14s01)
  - [B05.CH18.P14.S02 — Political capture: emergency regimes without sunsets, selective enforcement, maintenance budget hollowing](./P14.md#b05ch18p14s02)
  - [B05.CH18.P14.S03 — Epistemic capture: “experts” monopolize definitions/benchmarks; dissent becomes impossible](./P14.md#b05ch18p14s03)
  - [B05.CH18.P14.S04 — Cultural capture: status networks replace money caps via gatekeeping (link to CH13)](./P14.md#b05ch18p14s04)

- [B05.CH18.P15 — Capture: detection, evidence, and hard stops](./P15.md)
  - [B05.CH18.P15.S01 — Red flags: repeated exceptions for the same positions, revolving-door patterns, vendor dominance graphs](./P15.md#b05ch18p15s01)
  - [B05.CH18.P15.S02 — Audit signals: skewed audit coverage, suppressed findings, missing incident disclosure](./P15.md#b05ch18p15s02)
  - [B05.CH18.P15.S03 — Public accountability: conformance downgrade + forensic audit + governance reset protocol](./P15.md#b05ch18p15s03)
  - [B05.CH18.P15.S04 — Hard stop: proven capture → immediate suspension of discretionary powers and template reset](./P15.md#b05ch18p15s04)

- [B05.CH18.P16 — Human agency: why failure modes cannot be “measured away”](./P16.md)
  - [B05.CH18.P16.S01 — Agency as a constraint: people react to clamps, shame, uncertainty; that is causality, not noise](./P16.md#b05ch18p16s01)
  - [B05.CH18.P16.S02 — Limits on nudging/scoring: behavioral steering via monitoring creates new E axes and legitimacy fracture](./P16.md#b05ch18p16s02)
  - [B05.CH18.P16.S03 — Experience signals: procedurally embedded qualitative input is required alongside quantitative metrics](./P16.md#b05ch18p16s03)
  - [B05.CH18.P16.S04 — Implication: design must expand choice/exit; do not attempt to “optimize” behavior via totalization](./P16.md#b05ch18p16s04)

- [B05.CH18.P17 — Evolutionary infrastructure: failure modes as fuel for controlled iteration](./P17.md)
  - [B05.CH18.P17.S01 — Patch cycle: detect → hypothesis → intervention → audit → public restatement → deprecation](./P17.md#b05ch18p17s01)
  - [B05.CH18.P17.S02 — Backward compatibility: changes improve the lifeworld without a semantic core break](./P17.md#b05ch18p17s02)
  - [B05.CH18.P17.S03 — Rollback discipline: harm to L/tails/privacy/integrity triggers immediate rollback](./P17.md#b05ch18p17s03)
  - [B05.CH18.P17.S04 — Speed vs stability: fast Codex updates, slow core updates (Kernspec remains canonical)](./P17.md#b05ch18p17s04)

- [B05.CH18.P18 — Integration: how CH18 makes the rest of Book 5 enforceable](./P18.md)
  - [B05.CH18.P18.S01 — Link to sector cases (CH17): every sector case includes explicit failure-mode checks and stop rules](./P18.md#b05ch18p18s01)
  - [B05.CH18.P18.S02 — Link to day-in-the-life (CH14–CH16): cases act as policy regression tests](./P18.md#b05ch18p18s02)
  - [B05.CH18.P18.S03 — Link to local institutions (CH12): contestability/auditability are primary, not optional](./P18.md#b05ch18p18s03)
  - [B05.CH18.P18.S04 — Link to transition conflict (Book 2): sabotage/retaliation scenarios and mitigations are predefined](./P18.md#b05ch18p18s04)

- [B05.CH18.P19 — Measurement and publication requirements (early-warning dashboard)](./P19.md)
  - [B05.CH18.P19.S01 — Resentment proxies: friction indices, appeal volumes, drop-off, wait times, cohort fractures](./P19.md#b05ch18p19s01)
  - [B05.CH18.P19.S02 — Sabotage proxies: integrity alerts, execution anomalies, incident rates, capacity collapses](./P19.md#b05ch18p19s02)
  - [B05.CH18.P19.S03 — Evasion proxies: shift indicators, fee-stack depth, offshore/synthetic exposure (aggregated)](./P19.md#b05ch18p19s03)
  - [B05.CH18.P19.S04 — Capture proxies: exceptions register, vendor dominance, audit coverage anomalies, revolving-door stats](./P19.md#b05ch18p19s04)

- [B05.CH18.P20 — Close: stop rules and minimal repair paths](./P20.md)
  - [B05.CH18.P20.S01 — Stop rule A: rising essentials-L or worsening tails without an external shock → halt scaling](./P20.md#b05ch18p20s01)
  - [B05.CH18.P20.S02 — Stop rule B: privacy/integrity breach (silent edits, unsigned changes, scope creep) → immediate rollback](./P20.md#b05ch18p20s02)
  - [B05.CH18.P20.S03 — Stop rule C: proven selective enforcement or capture → governance reset + conformance suspension](./P20.md#b05ch18p20s03)
  - [B05.CH18.P20.S04 — Repair path: forensic audit → restatement → template redesign → recertification (no “muddling through”)](./P20.md#b05ch18p20s04)
