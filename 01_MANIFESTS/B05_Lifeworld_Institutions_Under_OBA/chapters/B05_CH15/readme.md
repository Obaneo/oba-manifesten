| id              | book | chapter | type   | status |
|-----------------|------|---------|--------|--------|
| B05.CH15.README | B05  | CH15    | readme | draft  |

<a id="b05ch15readme"></a>
# B05.CH15 — Day-in-the-life II: middle household (work/security/time, essentials baseline, frictions)

This chapter is the second **day-in-the-life** module for OBA. It translates the framework into a concrete **middle-household** case:
not extreme precarity, but the “normal” household that still experiences structural frictions—time poverty, administrative tolls,
contract lock-ins, and volatility in essentials. The purpose is explicitly **non-PR**: it must show, in reproducible terms, how
**BRUTO → NETTO → LASTEN → RESTRUIMTE** and **time security** change under OBA, and which mechanisms cause the change (price rails,
public options, schedule rails, portability, lower administrative toll, faster dispute/correction).

Narrative is permitted only as a carrier. The truth condition is **measurement linkage**: `definitionset_id`, `method_id`, explicit
time windows, and explicit uncertainty bands.

CH15 is designed to be **anti-washing** and **FAIL-CLOSED**. A “normal life improved” story without explicit friction diagnosis
(administration, lock-in, time capture) and without a measurable before/after dashboard is **NON-CONFORM**. Likewise, a story that
claims “normality” while hiding volatility, tails, or residual frictions is non-conforming. The case is also an early-warning tool:
if an “after” system still produces worsening volatility, rising arrears/late payments, increased time poverty, or selective execution
differences by locality without transparency, that is a design breach requiring redesign.

---

## Conformance gates (chapter-level)

A CH15 case **MUST**:
- Declare provenance: `definitionset_id`, `method_id`, `case_mode`, and comparable `time_window_pre/post`.
- Provide a **before/after dashboard** that includes B,T,N,L,R and time metrics with uncertainty bands.
- Diagnose **pre-OBA frictions** as concrete mechanisms (lock-ins, wait-time gates, refinancing friction, schedule capture, admin toll).
- Provide dispute-flow rails: fast correction + provisional relief + restatement (where relevant), plus transparent logs.

A CH15 case **MUST NOT**:
- Substitute plausibility or narrative coherence for measurable deltas.
- Treat health as a KPI or eligibility signal (experience signals may appear only as procedural input).
- Claim conformance if “after” worsens volatility or tails (arrears/late payments, time poverty, lock-in intensity).

---

## Scope and exclusions

**In scope**
- Middle-income household variants (e.g., dual earners; single + children variant), with work/care combination.
- Essentials and recurring obligations: housing (rent/mortgage), energy, food, insurance, digital, mobility, debt service.
- Time structure: work hours, commute, childcare/informal care, administrative time, schedule predictability.
- Risk events typical for the middle household (health/work/price/care shocks) and recovery pathways.

**Out of scope**
- Macro-economic claims and political campaigning.
- “Lifestyle optimization” advice.
- Medical outcome optimization as a performance metric.

---

## Artifacts emitted (chapter outputs)

CH15 **MUST** emit, at minimum:
- A baseline profile with income mix + time structure inventory (P02).
- A friction map (P03) with measurable proxies (wait times, switching costs, schedule capture markers, admin steps).
- A risk event set (P04) with propagation channels into L volatility and time poverty.
- A mapped intervention set (P05) linking each rail to a friction and a measurable expected delta.
- Domain “after” modules (P06–P10) with measurable effect claims and evidence classes.
- A case dashboard schema (P11).
- A dispute-flow and protections module (P12).
- A residual friction register (P13).
- A failure mode / hard-stop register (P14).

---

## How to use this chapter

- If you are **explaining OBA concretely**: use CH15 to show how OBA changes “normality” by lowering L volatility, reducing time capture,
  and making exit/contestability real (without relying on crisis narratives).
- If you are **designing essentials baselines and price rails**: use the friction map (P03) and intervention set (P05) to identify
  where middle households are pinned (mortgage resets, childcare wait times, mobility lock-in, subscription bundles) and which rails
  remove volatility and toll layers.
- If you are **designing time security**: use the time budget baseline (P02) and “work and time” module (P07) to specify schedule rails,
  portability of leave/care rights, and reduction of administrative toll.
- If you are **designing public options**: use P06/P08/P09/P10 to operationalize public/commons options as real alternatives (coverage,
  wait times, service levels, dispute-safe rules).
- If you are **auditing implementation**: use the case dashboard (P11) and dispute-flow (P12) as conformance tests and early-warning
  indicators for volatility/tail regressions and selective execution.

---

## Structure

P01 — Purpose, scope, and method for the middle-household case  
P02 — Baseline profile (pre-OBA): income mix and time structure  
P03 — Friction map: where the middle household gets stuck (pre-OBA)  
P04 — Risk events: typical middle-class shocks  
P05 — OBA intervention set (after): how “normality” shifts  
P06 — Housing and maintenance (after): less asset stress, more quality security  
P07 — Work and time (after): less schedule capture, more agency  
P08 — Childcare, education, and care (after): access without wait-time lock-ins  
P09 — Mobility and logistics (after): less car lock-in  
P10 — Digital lifeworld (after): less subscription lock-in and platform toll  
P11 — Measurable “before/after” outputs (case dashboard)  
P12 — Dispute-flow and exceptions: how the middle household corrects system errors  
P13 — Residual frictions (honesty about what remains)  
P14 — Failure modes and hard stops  

---

## Status

This chapter is **normative** for using “middle household” day-in-the-life narratives inside OBA. The standardized case template,
explicit friction diagnosis (time capture, administrative toll, lock-ins), and measurable before/after dashboard are treated as
**constitutive** requirements. Any OBA narrative that claims improved normality, reduced stress from volatility, or restored time
security must be able to instantiate this template and emit the linked measurements.

Conversely, if implementation produces “after” cases with unchanged essentials volatility, persistent wait-time gates, high
administrative time burden, rising arrears/late payments, or selective execution differences without transparency, that is evidence of
**NON-CONFORM** that must trigger redesign and/or scope restriction to auditable coverage.
