| id             | book | chapter | type          | status |
|----------------|------|---------|---------------|--------|
| B05.CH15.INDEX | B05  | CH15    | chapter-index | draft  |

<a id="b05ch15index"></a>
# B05.CH15 — Day-in-the-life II: middle household (work/security/time, essentials baseline, frictions)

This chapter is the second “day-in-the-life” module for OBA. It operationalises the framework in a **middle-household** case: not extreme precarity, but the “normal” household that still experiences structural frictions (time poverty, administrative tolls, lock-ins, volatility in essentials). The purpose is explicitly non-PR: it must show, in reproducible terms, how **BRUTO → NETTO → LASTEN → RESTRUIMTE** and **time security** change under OBA, and which mechanisms cause the change (price rails, public options, schedule rails, portability, reduced administrative toll, faster dispute and correction).

CH15 binds the case to OBA’s canonical rails (**B,T,N,L,R; R/B; lock-in/block power; P/E/C; contestability; audit/evidence discipline**) and extends the lifeworld lens: not only “can the household survive shocks?”, but “does the household regain predictable time and real choice without hidden tolls?”. The case is template-driven and measurable: every before/after claim links to `definitionset_id` and `method_id`, uncertainty is explicit, and qualitative signals are admitted only as procedural input (not KPIs).

CH15 is **fail-closed**: a case that describes “normal life improved” without explicit friction diagnosis (administration, lock-in, time poverty, volatility) and without a measurable case dashboard is **NON-CONFORM**.

---

## Conformance summary (chapter-level gates)

A CH15 case **MUST**:
- Emit a comparable **before/after dashboard** with provenance (`definitionset_id`, `method_id`, time windows) and uncertainty bands.
- Diagnose **pre-OBA frictions** as concrete mechanisms (contract lock-ins, administrative tolls, time capture, volatility channels).
- Show measurable deltas for:
  - L-level and L-volatility (essentials baseline / price rails),
  - time security (schedule predictability, admin-time burden, commute variance),
  - and shock recovery (time-to-recovery, arrears/late payment incidence).
- Provide dispute-flow rails (fast correction + provisional relief + restatement) and protection (no retaliation, transparent logs).

A CH15 case **MUST NOT**:
- Substitute narrative plausibility for measurement linkage.
- Treat “health” as a success KPI (experience signals may exist only as procedural input).
- Claim conformance if “after” worsens volatility or tails (arrears, time poverty, lock-in).

---

## Depends on (canonical references to be resolved in-repo)

- `B,T,N,L,R` definitions and computation rules (`definitionset_id`)
- Lock-in / block power definitions (exit realism, threat vectors)
- P/E/C classification rules for lifeworld fee/toll layers
- Contestability + audit rails (evidence classes, logging, dispute time bounds)
- Method/version discipline (`method_id`, reproducibility, uncertainty handling)

---

## Emitted artifacts (chapter outputs)

CH15 **MUST** emit, at minimum:
- Baseline profile + time structure inventory (P02)
- Friction map (P03) with measurable proxies (switching costs, wait times, schedule capture, admin steps)
- Risk event stressors (P04) and recovery implications
- Intervention set mapping (P05) with evidence requirements
- Domain “after” modules (P06–P10) with measurable effect claims
- Case dashboard schema (P11)
- Dispute-flow dashboard + incident/rollback handling (P12)
- Residual friction register (P13)
- Early-warning / hard-stop register (P14)

---

## Paragraphs

- [B05.CH15.P01 — Purpose, scope, and method for the middle-household case](./P01.md)
  - [B05.CH15.P01.S01 — Purpose: show how “normal” households experience OBA: lower L/lock-in, more time security, more stable R/B](./P01.md#b05ch15p01s01)
  - [B05.CH15.P01.S02 — Scope: dual earners or single + children (variant), middle incomes, work/care combination, mortgage/rent, mobility](./P01.md#b05ch15p01s02)
  - [B05.CH15.P01.S03 — Method: fixed case template with before/after and measurement linkage (definitionset_id, method_id, uncertainty)](./P01.md#b05ch15p01s03)
  - [B05.CH15.P01.S04 — Fail-closed: a case without explicit frictions (administration, lock-in, time poverty) is cosmetic and NON-CONFORM](./P01.md#b05ch15p01s04)

- [B05.CH15.P02 — Baseline profile (pre-OBA): income mix and time structure](./P02.md)
  - [B05.CH15.P02.S01 — BRUTO (B): wages + variable (bonus/overtime), predictability, contract type](./P02.md#b05ch15p02s01)
  - [B05.CH15.P02.S02 — NETTO (N) and T: withholdings, allowances, timing, clawback risk](./P02.md#b05ch15p02s02)
  - [B05.CH15.P02.S03 — Time budget: working hours, commute, childcare, informal care, “administrative time”](./P02.md#b05ch15p02s03)
  - [B05.CH15.P02.S04 — LASTEN (L): housing/energy/food/insurance/digital + debt service](./P02.md#b05ch15p02s04)

- [B05.CH15.P03 — Friction map: where the middle household gets stuck (pre-OBA)](./P03.md)
  - [B05.CH15.P03.S01 — Housing/mortgage: refinancing friction, rate-reset risk, moving friction, maintenance costs](./P03.md#b05ch15p03s01)
  - [B05.CH15.P03.S02 — Childcare/education: wait times, schedule mismatches, quality dispersion, administrative burden](./P03.md#b05ch15p03s02)
  - [B05.CH15.P03.S03 — Mobility: car lock-in, fuel/parking, unreliable public transport, time loss](./P03.md#b05ch15p03s03)
  - [B05.CH15.P03.S04 — Digital friction: subscription bundles, vendor lock-in, identity processes, platform fees](./P03.md#b05ch15p03s04)

- [B05.CH15.P04 — Risk events: typical middle-class shocks](./P04.md)
  - [B05.CH15.P04.S01 — Health shock: temporary incapacity + wait time/pathway friction](./P04.md#b05ch15p04s01)
  - [B05.CH15.P04.S02 — Work transition: sector shift, reorganization, skills mismatch](./P04.md#b05ch15p04s02)
  - [B05.CH15.P04.S03 — Price shock: energy, food, interest rates; compounding into rising L](./P04.md#b05ch15p04s03)
  - [B05.CH15.P04.S04 — Care shock: sudden informal care, divorce, death; system friction as multiplier](./P04.md#b05ch15p04s04)

- [B05.CH15.P05 — OBA intervention set (after): how “normality” shifts](./P05.md)
  - [B05.CH15.P05.S01 — Essentials baseline: price rails + public options; less volatility in L](./P05.md#b05ch15p05s01)
  - [B05.CH15.P05.S02 — Time security: schedule rails, portability of leave/care rights, lower administrative toll](./P05.md#b05ch15p05s02)
  - [B05.CH15.P05.S03 — Security/buffers: better shock absorption via insurance and fallback commons; faster procedures](./P05.md#b05ch15p05s03)
  - [B05.CH15.P05.S04 — Work transition: reskilling rails and mobility support without a precarious dip](./P05.md#b05ch15p05s04)

- [B05.CH15.P06 — Housing and maintenance (after): less asset stress, more quality security](./P06.md)
  - [B05.CH15.P06.S01 — Mortgage without a bubble: demand stimulus banned; focus on supply/renovation/commons options](./P06.md#b05ch15p06s01)
  - [B05.CH15.P06.S02 — Maintenance regime: renovation/insulation via commons capacity; fewer unexpected cost spikes](./P06.md#b05ch15p06s02)
  - [B05.CH15.P06.S03 — Moving: lower switching costs; transparent contracts; better work/home matching](./P06.md#b05ch15p06s03)
  - [B05.CH15.P06.S04 — Measurable effect: housing burden down, arrears down, dispute times down](./P06.md#b05ch15p06s04)

- [B05.CH15.P07 — Work and time (after): less schedule capture, more agency](./P07.md)
  - [B05.CH15.P07.S01 — Workweek/schedules: higher predictability; room for care and participation](./P07.md#b05ch15p07s01)
  - [B05.CH15.P07.S02 — Career path: less rat race via caps; focus on craft and contribution](./P07.md#b05ch15p07s02)
  - [B05.CH15.P07.S03 — Overtime/bonus: less incentive toward burnout; income spikes dampened via security/buffers](./P07.md#b05ch15p07s03)
  - [B05.CH15.P07.S04 — Failure mode: new status barriers (credentials/networks) → detection via drop-off metrics](./P07.md#b05ch15p07s04)

- [B05.CH15.P08 — Childcare, education, and care (after): access without wait-time lock-ins](./P08.md)
  - [B05.CH15.P08.S01 — Childcare: baseline access, predictability, quality; lower “time burden”](./P08.md#b05ch15p08s01)
  - [B05.CH15.P08.S02 — Education: less pay-to-win; stronger baseline provision; contestability when quality diverges](./P08.md#b05ch15p08s02)
  - [B05.CH15.P08.S03 — Healthcare: shorter waits, clear pathways, less claims industry and paperwork](./P08.md#b05ch15p08s03)
  - [B05.CH15.P08.S04 — Measurable effect: admin burden down, incident rates transparent, satisfaction as procedural input](./P08.md#b05ch15p08s04)

- [B05.CH15.P09 — Mobility and logistics (after): less car lock-in](./P09.md)
  - [B05.CH15.P09.S01 — Public transport quality: higher reliability and coverage; more predictable travel time](./P09.md#b05ch15p09s01)
  - [B05.CH15.P09.S02 — Active mobility: better infrastructure → time/health as a side effect, not a KPI target](./P09.md#b05ch15p09s02)
  - [B05.CH15.P09.S03 — Cost structure: lower volatility in mobility costs; fewer fee stacks (tolls/parking extraction)](./P09.md#b05ch15p09s03)
  - [B05.CH15.P09.S04 — Measurable effect: commute-time variance down, modal options up, mobility burden down](./P09.md#b05ch15p09s04)

- [B05.CH15.P10 — Digital lifeworld (after): less subscription lock-in and platform toll](./P10.md)
  - [B05.CH15.P10.S01 — Baseline digital services: interoperability/portability; less vendor lock-in](./P10.md#b05ch15p10s01)
  - [B05.CH15.P10.S02 — Platform fees: bounded take rates; transparency and dispute-flow](./P10.md#b05ch15p10s02)
  - [B05.CH15.P10.S03 — Identity: recovery and due process; no lockout from essentials](./P10.md#b05ch15p10s03)
  - [B05.CH15.P10.S04 — Measurable effect: portability success rates up, lockout incidents down, fee shares down](./P10.md#b05ch15p10s04)

- [B05.CH15.P11 — Measurable “before/after” outputs (case dashboard)](./P11.md)
  - [B05.CH15.P11.S01 — B,T,N,L,R: median values + uncertainty bands + method_id](./P11.md#b05ch15p11s01)
  - [B05.CH15.P11.S02 — L components: housing/energy/childcare/digital/mobility shares; volatility](./P11.md#b05ch15p11s02)
  - [B05.CH15.P11.S03 — Time metrics: schedule predictability, admin-time burden, commute variance (aggregated/survey-based)](./P11.md#b05ch15p11s03)
  - [B05.CH15.P11.S04 — Shock absorption: time-to-recovery, arrears/late payments, use of fallback commons](./P11.md#b05ch15p11s04)

- [B05.CH15.P12 — Dispute-flow and exceptions: how the middle household corrects system errors](./P12.md)
  - [B05.CH15.P12.S01 — Wrong decision: fast correction + provisional relief + restatement](./P12.md#b05ch15p12s01)
  - [B05.CH15.P12.S02 — Provider abuse: anomaly → audit → contract remedies](./P12.md#b05ch15p12s02)
  - [B05.CH15.P12.S03 — Privacy overreach: hard stop and rollback; public incident log](./P12.md#b05ch15p12s03)
  - [B05.CH15.P12.S04 — Protection: no retaliation; transparent logs and appeals stats](./P12.md#b05ch15p12s04)

- [B05.CH15.P13 — Residual frictions (honesty about what remains)](./P13.md)
  - [B05.CH15.P13.S01 — Transition costs: reskilling, temporary wait times, infrastructure rebuild](./P13.md#b05ch15p13s01)
  - [B05.CH15.P13.S02 — Regional variation: differences in pace/quality; mitigate via minima and escalation](./P13.md#b05ch15p13s02)
  - [B05.CH15.P13.S03 — Cultural adaptation: status norms and consumption patterns shift slowly](./P13.md#b05ch15p13s03)
  - [B05.CH15.P13.S04 — Risk: “the middle class feels nothing” if L does not visibly fall → need transparent case dashboards](./P13.md#b05ch15p13s04)

- [B05.CH15.P14 — Failure modes and hard stops](./P14.md)
  - [B05.CH15.P14.S01 — Cosmetic gains: higher net but unchanged L/lock-in → legitimacy loss](./P14.md#b05ch15p14s01)
  - [B05.CH15.P14.S02 — New lock-in: public services with digital exclusion or bureaucratic toll → NON-CONFORM](./P14.md#b05ch15p14s02)
  - [B05.CH15.P14.S03 — Selective execution: local postcode differences without accountability → contestability breach](./P14.md#b05ch15p14s03)
  - [B05.CH15.P14.S04 — Fail-closed: if “after” worsens volatility or tails (more arrears, more time poverty), redesign is mandatory](./P14.md#b05ch15p14s04)
