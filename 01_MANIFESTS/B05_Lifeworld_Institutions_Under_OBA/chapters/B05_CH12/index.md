| id             | book | chapter | type          | status |
|----------------|------|---------|---------------|--------|
| B05.CH12.INDEX | B05  | CH12    | chapter-index | draft  |

# B05.CH12 — Local institutions and governance: municipalities, executors, quasi-public bodies, contestability, and audit

This chapter specifies **local institutions** under OBA as the execution layer where policy becomes lifeworld reality. Local
institutions (municipalities/regions, executing agencies, quasi-public bodies, and local commons operators) hold practical block power:
they allocate housing access, enforce rules, manage procurement, operate service desks, and decide exceptions. Without rails, local
discretion drifts into arbitrariness, postcode lotteries, vendor capture, and bureaucratic tolls (administrative L). OBA therefore
treats local governance as infrastructure: execution capacity is measurable (ΔG of governance), decision rules are standardised where
necessary, contestability (objection/appeal) is designed-in, and audit is multi-layered (“audit of the auditor”). Local variation is
allowed only through explicit parameters; invariants remain binding.

CH12 binds local governance to the Kernel Spec (definitions/invariants), the Codex (templates, audit and detection packs), commons and
procurement rails, and the lifeworld R/B test. It defines roles and separation of powers, local commons registries and maintenance-first
discipline, admissibility rails for quasi-public bodies, execution capacity metrics, contestability and ombuds functions, audit
architecture, procurement anti-lock-in rules, local finance within anti-regression rails, data minimalism in execution, crisis regimes
with sunset discipline, publication requirements, and hard stops. It is designed to fail-closed: discretionary local deals without
audit packs and contestability are non-conforming until corrected; persistent failure triggers temporary restriction of local autonomy
and forced redesign.

---

## Paragraphs

- [B05.CH12.P01 — Purpose, scope, and normative status of local institutions under OBA](./P01.md)
  - [B05.CH12.P01.S01 — Purpose: execution power close to the lifeworld, with hard rails against arbitrariness and capture](./P01.md#b05ch12p01s01)
  - [B05.CH12.P01.S02 — Scope: municipalities/regions, executing agencies, quasi-public institutions, local commons, enforcement](./P01.md#b05ch12p01s02)
  - [B05.CH12.P01.S03 — Binding: Kernel Spec (definitions/invariants), Codex (templates, audit, detection), commons and procurement rails, R/B lifeworld test](./P01.md#b05ch12p01s03)
  - [B05.CH12.P01.S04 — Fail-closed: local discretionary deals without an audit pack/contestability are non-conform](./P01.md#b05ch12p01s04)

- [B05.CH12.P02 — Roles and powers model (actor versus position)](./P02.md)
  - [B05.CH12.P02.S01 — Positions: mandate-grantor (council), executor, steward/manager, auditor, ombuds/dispute arbiter](./P02.md#b05ch12p02s01)
  - [B05.CH12.P02.S02 — Separation of functions: decision, execution, oversight, appeal (no concentration of block power)](./P02.md#b05ch12p02s02)
  - [B05.CH12.P02.S03 — Delegation: what may vary locally (parameters) and what may not (invariants)](./P02.md#b05ch12p02s03)
  - [B05.CH12.P02.S04 — Intergovernmental coupling: national minima, local modules, escalation paths](./P02.md#b05ch12p02s04)

- [B05.CH12.P03 — Local commons: registration, governance, and maintenance-first](./P03.md)
  - [B05.CH12.P03.S01 — Commons portfolio: housing, mobility, care, community spaces, digital service desks](./P03.md#b05ch12p03s01)
  - [B05.CH12.P03.S02 — Registry discipline: commons_id, access rules, maintenance budget, incident logs](./P03.md#b05ch12p03s02)
  - [B05.CH12.P03.S03 — Prioritisation: L hotspots and R/B tails as allocation criteria](./P03.md#b05ch12p03s03)
  - [B05.CH12.P03.S04 — Anti-capture: rotation, conflict-of-interest rules, vendor-dominance checks, public minutes](./P03.md#b05ch12p03s04)

- [B05.CH12.P04 — Quasi-public bodies: when allowed and under which rails](./P04.md)
  - [B05.CH12.P04.S01 — Definition: bodies with public tasks but autonomous governance (toll risk)](./P04.md#b05ch12p04s01)
  - [B05.CH12.P04.S02 — Admissibility: only with access/quality minima, transparency, procurement rails, contestability](./P04.md#b05ch12p04s02)
  - [B05.CH12.P04.S03 — Prohibited structures: hidden fee-stacks, exclusivity, opaque cross-subsidies](./P04.md#b05ch12p04s03)
  - [B05.CH12.P04.S04 — Remedies: contract rewrite, governance reset, conversion to commons, status downgrade](./P04.md#b05ch12p04s04)

- [B05.CH12.P05 — Execution as infrastructure (ΔG of governance)](./P05.md)
  - [B05.CH12.P05.S01 — Capacity metrics: lead times, backlogs, error rates, drop-off (administrative L)](./P05.md#b05ch12p05s01)
  - [B05.CH12.P05.S02 — Standardisation: templates, decision rules, uniform data dictionaries (without data maximalism)](./P05.md#b05ch12p05s02)
  - [B05.CH12.P05.S03 — Maintenance-first: training, tooling, continuity, incident response](./P05.md#b05ch12p05s03)
  - [B05.CH12.P05.S04 — Hard stop: structural under-capacity → escalation, restructuring, and support mechanisms](./P05.md#b05ch12p05s04)

- [B05.CH12.P06 — Contestability: objection/appeal as a design principle](./P06.md)
  - [B05.CH12.P06.S01 — Dispute flow: low-friction, time-bounded, reproducible, with access to calculations](./P06.md#b05ch12p06s01)
  - [B05.CH12.P06.S02 — Ombuds function: independent triage and escalation for systemic patterns](./P06.md#b05ch12p06s02)
  - [B05.CH12.P06.S03 — Transparency: public case statistics (aggregated), decision logs, exceptions register](./P06.md#b05ch12p06s03)
  - [B05.CH12.P06.S04 — Protection against retaliation: citizens/whistleblowers, due process, non-discrimination](./P06.md#b05ch12p06s04)

- [B05.CH12.P07 — Audit of the auditor: local oversight architecture](./P07.md)
  - [B05.CH12.P07.S01 — Meta-audits: audits of auditors, rotation, peer review](./P07.md#b05ch12p07s01)
  - [B05.CH12.P07.S02 — Openness: audit summaries, conformance status, remediation progress](./P07.md#b05ch12p07s02)
  - [B05.CH12.P07.S03 — Integrity: signed releases of local templates/parameters, change logs](./P07.md#b05ch12p07s03)
  - [B05.CH12.P07.S04 — Hard stop: selective enforcement, opaque exceptions, or capture signals → immediate intervention](./P07.md#b05ch12p07s04)

- [B05.CH12.P08 — Local procurement rails: preventing vendor lock-in and corruption](./P08.md)
  - [B05.CH12.P08.S01 — Open standards: mandatory interop, portability, escrow/source-access triggers](./P08.md#b05ch12p08s01)
  - [B05.CH12.P08.S02 — Transparency: tenders, award rationales, change orders (aggregated), vendor dependency graphs](./P08.md#b05ch12p08s02)
  - [B05.CH12.P08.S03 — Performance contracting: SLAs tied to ΔG/access; penalties; exit assistance](./P08.md#b05ch12p08s03)
  - [B05.CH12.P08.S04 — Corruption risk: conflict-of-interest, revolving door, procurement anomalies → forensics](./P08.md#b05ch12p08s04)

- [B05.CH12.P09 — Local finance and T mix (within rails)](./P09.md)
  - [B05.CH12.P09.S01 — Local levies: admissible within anti-regression and essentials rails](./P09.md#b05ch12p09s01)
  - [B05.CH12.P09.S02 — Intergovernmental transfers: transparent formulas, no political arbitrariness, auditable](./P09.md#b05ch12p09s02)
  - [B05.CH12.P09.S03 — Ring-fencing: maintenance budgets and baseline access protected](./P09.md#b05ch12p09s03)
  - [B05.CH12.P09.S04 — Failure mode: postcode lottery without explanation → legitimacy breach and migration friction](./P09.md#b05ch12p09s04)

- [B05.CH12.P10 — Data and privacy in execution (minimalism without blindness)](./P10.md)
  - [B05.CH12.P10.S01 — Minimal necessary: data only for decision/execution/audit, no secondary profiling](./P10.md#b05ch12p10s01)
  - [B05.CH12.P10.S02 — Tiered disclosure: public (aggregate), regulated (micro), confidential (PII)](./P10.md#b05ch12p10s02)
  - [B05.CH12.P10.S03 — Logging: decision logs, access logs, tamper-evidence, retention caps](./P10.md#b05ch12p10s03)
  - [B05.CH12.P10.S04 — Hard stop: data collection as a substitute for competence (bureaucratic drift)](./P10.md#b05ch12p10s04)

- [B05.CH12.P11 — Local crisis regimes: emergency without permanent power](./P11.md)
  - [B05.CH12.P11.S01 — Triggers: shocks (energy/food/health) with public notice](./P11.md#b05ch12p11s01)
  - [B05.CH12.P11.S02 — Temporariness: sunsets, scope caps, unwind plan, post-mortem audit](./P11.md#b05ch12p11s02)
  - [B05.CH12.P11.S03 — Prioritisation: essentials baseline, vulnerable cohorts, continuity of commons](./P11.md#b05ch12p11s03)
  - [B05.CH12.P11.S04 — Prohibited: emergency as an excuse for opaque deals or vendor capture](./P11.md#b05ch12p11s04)

- [B05.CH12.P12 — Measurement and publication requirements (local institutions as lifeworld test)](./P12.md)
  - [B05.CH12.P12.S01 — Execution: lead times, backlog, error/appeal rates, drop-off (administrative L)](./P12.md#b05ch12p12s01)
  - [B05.CH12.P12.S02 — Commons: access/ΔG/incident/maintenance metrics per domain (aggregated)](./P12.md#b05ch12p12s02)
  - [B05.CH12.P12.S03 — Governance: exceptions register, procurement anomalies, audit findings, remediation rates](./P12.md#b05ch12p12s03)
  - [B05.CH12.P12.S04 — R/B: local cohort profiles and essentials indices (privacy-safe)](./P12.md#b05ch12p12s04)

- [B05.CH12.P13 — Failure modes and hard stops](./P13.md)
  - [B05.CH12.P13.S01 — Local capture: networks of vendors/officials → forensics and governance reset](./P13.md#b05ch12p13s01)
  - [B05.CH12.P13.S02 — Discretion creep: ever more “tailoring” without rules → non-conform](./P13.md#b05ch12p13s02)
  - [B05.CH12.P13.S03 — Compliance theatre: dashboards without remedies → legitimacy breach](./P13.md#b05ch12p13s03)
  - [B05.CH12.P13.S04 — Fail-closed: persistent failure on contestability/auditability → temporarily restrict local autonomy and force redesign](./P13.md#b05ch12p13s04)
