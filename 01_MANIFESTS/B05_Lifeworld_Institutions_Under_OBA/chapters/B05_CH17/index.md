| id             | book | chapter | type          | status |
|----------------|------|---------|---------------|--------|
| B05.CH17.INDEX | B05  | CH17    | chapter-index | draft  |

<a id="b05ch17index"></a>
# B05.CH17 — Sector cases as templates: sector-canvas in lifeworld form (housing/energy/healthcare/digital)

This chapter specifies **sector cases as reusable templates**: a standardized “sector-canvas” expressed in lifeworld form that can be
replicated, audited, and extended across domains. The goal is not descriptive storytelling; it is **operationalization**: convert sector
analysis into a repeatable case format that exposes bottlenecks, E-sources (fee stacks/lock-in), commons/public options, caps
compatibility, R/B effects, and ΔM channels—bound to Codex schemas and auditpacks.

CH17 binds sector narratives to OBA’s canonical rails (**bottlenecks → E-sources → commons option → caps compatibility → R/B effects →
ΔM channel → governance/execution → evidence packs**). The chapter is **FAIL-CLOSED**: a sector case that omits required template fields
or measurement binding is not reusable and is **NON-CONFORM**.

---

## Conformance summary (chapter-level gates)

A CH17 sector case **MUST**:
- Use the canonical sector-case template fields (bottlenecks, E sources, commons option, caps compatibility, R/B effect, ΔM channel).
- Bind every quantitative claim to `definitionset_id`, `method_id`, and uncertainty reporting where applicable.
- Emit machine-readable evidence minimums (identifiers, datasets, logs) compatible with Codex schemas/auditpacks.
- Include contestability and audit rails (including audit-on-the-auditor) as first-class template fields.

A CH17 sector case **MUST NOT**:
- Replace template fields with narrative plausibility (“template-washing”).
- Use the template to justify surveillance or microdata publication (data maximalism).
- Become a vendor/consultancy capture product outside procurement rails.

---

## Depends on (canonical references to be resolved in-repo)

- Sector-canvas field definitions (bottlenecks, E sources, commons options, caps compatibility, R/B effects, ΔM channels)
- Codex schemas: identifiers, flow objects, forbidden-channel flags, auditpacks, decision logs
- Core measurement discipline: `definitionset_id`, `method_id`, benchmark versions, uncertainty handling
- Contestability and dispute-flow rails; audit-on-the-auditor rails
- UBC look-through (for caps compatibility mapping)

---

## Emitted artifacts (chapter outputs)

CH17 **MUST** emit, at minimum:
- A canonical sector-case template schema (P02) suitable for reuse.
- Governance/execution field set (roles, logs, contestability, meta-audit) (P06).
- Data/evidence minimum schema (machine-readable) (P07).
- Four exemplar sector cases: housing/energy/healthcare/digital (P08).
- Extension and fork-management rules for other sectors (P09).
- Failure mode / hard-stop register for template abuse and scaling gates (P10).

---

## Paragraphs

- [B05.CH17.P01 — Purpose, scope, and normative status of sector cases as templates](./P01.md)
  - [B05.CH17.P01.S01 — Purpose: operationalize the sector canvas into repeatable lifeworld case formats (replicable, auditable)](./P01.md#b05ch17p01s01)
  - [B05.CH17.P01.S02 — Scope: housing/energy/healthcare/digital (minimum), extensible to other essentials](./P01.md#b05ch17p01s02)
  - [B05.CH17.P01.S03 — Binding: sector-canvas fields (bottlenecks, E sources, commons option, caps compatibility, R/B effect, ΔM channel) + Codex schemas/auditpacks](./P01.md#b05ch17p01s03)
  - [B05.CH17.P01.S04 — Fail-closed: a sector case without template fields and without measurement binding is not reusable and is NON-CONFORM](./P01.md#b05ch17p01s04)

- [B05.CH17.P02 — Canonical template structure (one sector case)](./P02.md)
  - [B05.CH17.P02.S01 — Context: sector boundaries, users, dependencies, choke points](./P02.md#b05ch17p02s01)
  - [B05.CH17.P02.S02 — Bottlenecks: scarcity/capacity/permits/skills/infrastructure; time as a constraint](./P02.md#b05ch17p02s02)
  - [B05.CH17.P02.S03 — E sources: fee stacks, lock-in, market power, dark patterns, clamp contracts](./P02.md#b05ch17p02s03)
  - [B05.CH17.P02.S04 — Commons/public option: alternative design, governance minima, maintenance plan, procurement rails](./P02.md#b05ch17p02s04)

- [B05.CH17.P03 — Caps compatibility and incentive redesign (per sector)](./P03.md)
  - [B05.CH17.P03.S01 — W/I exposure: where claims and concentration sit (UBC look-through)](./P03.md#b05ch17p03s01)
  - [B05.CH17.P03.S02 — Incentives: how caps steer behavior; which status shifts to expect](./P03.md#b05ch17p03s02)
  - [B05.CH17.P03.S03 — No-arbitrage: prevent shifts into unregulated positions or sham constructions](./P03.md#b05ch17p03s03)
  - [B05.CH17.P03.S04 — Remedies: divestment, conversion-to-commons, contract rewrite, bounded returns](./P03.md#b05ch17p03s04)

- [B05.CH17.P04 — R/B effect and lifeworld metrics (per sector)](./P04.md)
  - [B05.CH17.P04.S01 — B,T,N,L,R: which L component falls and for whom (cohorts)](./P04.md#b05ch17p04s01)
  - [B05.CH17.P04.S02 — Tails: which shocks are dampened (arrears, lockouts, wait times, cost spikes)](./P04.md#b05ch17p04s02)
  - [B05.CH17.P04.S03 — Time friction: schedules, wait times, administrative burden as hidden L](./P04.md#b05ch17p04s03)
  - [B05.CH17.P04.S04 — Experience inputs: procedurally fixed signals (challenge rights, sampling, transparency)](./P04.md#b05ch17p04s04)

- [B05.CH17.P05 — ΔM channel: financing and forbidden routes](./P05.md)
  - [B05.CH17.P05.S01 — Allowed channels: commons capex/maintenance; transition instruments with traceability](./P05.md#b05ch17p05s01)
  - [B05.CH17.P05.S02 — Forbidden channels: asset/claim support, bubble subsidies, concessions with excess returns](./P05.md#b05ch17p05s02)
  - [B05.CH17.P05.S03 — Leakage tests: where money can leak into claims/fees; prevention via tagging and audits](./P05.md#b05ch17p05s03)
  - [B05.CH17.P05.S04 — Sunset/rollback: how temporary programs are wound down and evaluated](./P05.md#b05ch17p05s04)

- [B05.CH17.P06 — Template fields for governance and execution](./P06.md)
  - [B05.CH17.P06.S01 — Roles: mandator, executor, operator, auditor, ombuds/dispute arbiter](./P06.md#b05ch17p06s01)
  - [B05.CH17.P06.S02 — Decision logs: rules, exceptions, procurement, incidents (tamper-evident)](./P06.md#b05ch17p06s02)
  - [B05.CH17.P06.S03 — Contestability: objections/appeals, escalation, protection against retaliation](./P06.md#b05ch17p06s03)
  - [B05.CH17.P06.S04 — Audit-on-the-auditor: meta-audits, rotation, conformance status](./P06.md#b05ch17p06s04)

- [B05.CH17.P07 — Data and evidence minimum per sector case (machine-readable)](./P07.md)
  - [B05.CH17.P07.S01 — Minimal datasets: pricing tables, contract templates, capacity/backlog, incident logs, cohort aggregates](./P07.md#b05ch17p07s01)
  - [B05.CH17.P07.S02 — Identifiers: actor_id, position_id, contract_id, flow_id, service_id, commons_id](./P07.md#b05ch17p07s02)
  - [B05.CH17.P07.S03 — Method binding: definitionset_id, method_id, benchmark versions, uncertainty reporting](./P07.md#b05ch17p07s03)
  - [B05.CH17.P07.S04 — Privacy rails: aggregation, suppression, join-safety; microdata publication prohibited](./P07.md#b05ch17p07s04)

- [B05.CH17.P08 — The four core cases as exemplars (housing/energy/healthcare/digital)](./P08.md)
  - [B05.CH17.P08.S01 — Housing exemplar: scarcity → rent clamp → commons-housing pipeline + lock-in metrics](./P08.md#b05ch17p08s01)
  - [B05.CH17.P08.S02 — Energy exemplar: network monopoly → tariff rails → baseline access + reliability/incident discipline](./P08.md#b05ch17p08s02)
  - [B05.CH17.P08.S03 — Healthcare exemplar: wait times/claims industry → capacity/maintenance-first + quality triangulation](./P08.md#b05ch17p08s03)
  - [B05.CH17.P08.S04 — Digital exemplar: platform toll/identity lockout → interop/public option + portability metrics](./P08.md#b05ch17p08s04)

- [B05.CH17.P09 — Portability to other sectors (template extension)](./P09.md)
  - [B05.CH17.P09.S01 — Extension rules: no new definitions; only sector-specific parameters/benchmarks](./P09.md#b05ch17p09s01)
  - [B05.CH17.P09.S02 — Sector onboarding: baseline map, bottleneck scan, E scan, commons design, measurement pack](./P09.md#b05ch17p09s02)
  - [B05.CH17.P09.S03 — Fork management: local variants within compatibility; naming and versioning](./P09.md#b05ch17p09s03)
  - [B05.CH17.P09.S04 — Rollout: pilot → audit → scale → restatement; deprecate legacy contract forms](./P09.md#b05ch17p09s04)

- [B05.CH17.P10 — Failure modes and hard stops](./P10.md)
  - [B05.CH17.P10.S01 — Template-washing: a “case” without bottleneck/E/ΔM analysis → disqualification](./P10.md#b05ch17p10s01)
  - [B05.CH17.P10.S02 — Data maximalism: template used to justify surveillance → NON-CONFORM](./P10.md#b05ch17p10s02)
  - [B05.CH17.P10.S03 — Vendor capture: sector cases become consultancy products → procurement breach](./P10.md#b05ch17p10s03)
  - [B05.CH17.P10.S04 — Fail-closed: if the sector case does not deliver demonstrable L reduction or tail stabilization, scaling is blocked and redesign is mandatory](./P10.md#b05ch17p10s04)
