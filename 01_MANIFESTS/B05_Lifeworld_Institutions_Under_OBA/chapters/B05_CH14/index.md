| id             | book | chapter | type          | status |
|----------------|------|---------|---------------|--------|
| B05.CH14.INDEX | B05  | CH14    | chapter-index | draft  |

# B05.CH14 — Day-in-the-life I: household with low R/B (before/after, contract lock-ins, commons exits)

This chapter is the first “day-in-the-life” module for OBA. It operationalises the framework in a concrete household case with **low
R/B** (precarity / high tail exposure): a situation where small shocks cascade into arrears, lockouts, debt spirals, and administrative
clamp. The chapter’s purpose is explicitly non-PR: it must show, in reproducible terms, how **BRUTO → NETTO → LASTEN → RESTRUIMTE**
changes under OBA, and which mechanisms cause the change (lock-in removal, fee-stack collapse, baseline access, faster dispute and
restructuring). The case must be template-driven and measurable: every “before/after” claim links to definition sets and method_id, and
uncertainty is made explicit. The chapter is fail-closed: storytelling without lock-in diagnosis and without a measurable case dashboard
is non-conforming.

CH14 binds the narrative to OBA’s canonical rails (B,T,N,L,R; P/E/C; lock-in and block power; ΔM leakage; commons exits; contestability
and audit packs). It maps the household’s baseline profile, pinning lock-ins, fee-stacks and paperwork tolls, typical shock moments and
tail failures, and then specifies the OBA intervention set that changes structural conditions. It makes “commons exits” concrete (switch
paths out of lock-in contracts), shows how daily time structure changes after friction reduction, defines a measurable before/after
dashboard, and includes dispute/error handling plus residual frictions and early-warning failure modes.

---

## Paragraphs

- [B05.CH14.P01 — Purpose, scope, and method for the “day-in-the-life” case](./P01.md)
  - [B05.CH14.P01.S01 — Purpose: concretely show how BRUTO → NETTO → LASTEN → RESTRUIMTE changes (no PR)](./P01.md#b05ch14p01s01)
  - [B05.CH14.P01.S02 — Scope: low R/B household (precarity), essentials (housing/energy/food/digital), work/care, debts](./P01.md#b05ch14p01s02)
  - [B05.CH14.P01.S03 — Method: standardized case template + measurement linkage (definitionset-ID, method_id, uncertainty)](./P01.md#b05ch14p01s03)
  - [B05.CH14.P01.S04 — Fail-closed: a case without lock-in diagnosis and without measurable “before/after” claims is non-conform storytelling](./P01.md#b05ch14p01s04)

- [B05.CH14.P02 — Baseline profile (pre-OBA): inputs and observables](./P02.md)
  - [B05.CH14.P02.S01 — Cohort and context: region, household type, employment status, dependencies (aggregated)](./P02.md#b05ch14p02s01)
  - [B05.CH14.P02.S02 — BRUTO (B): income mix and volatility (hours, variable shifts, small side jobs)](./P02.md#b05ch14p02s02)
  - [B05.CH14.P02.S03 — NETTO (N) and T: withholdings, timing, clawback risk, administrative friction](./P02.md#b05ch14p02s03)
  - [B05.CH14.P02.S04 — LASTEN (L): essentials basket + contract lock-in indicators (penalties, exclusivity, arrears)](./P02.md#b05ch14p02s04)

- [B05.CH14.P03 — Lock-in map: where block power pins the household](./P03.md)
  - [B05.CH14.P03.S01 — Housing lock-in: lease terms, deposit, waitlists, moving friction, blacklisting](./P03.md#b05ch14p03s01)
  - [B05.CH14.P03.S02 — Energy lock-in: disconnection threats, advance payments, penalties, opaque surcharges](./P03.md#b05ch14p03s02)
  - [B05.CH14.P03.S03 — Digital lock-in: paywalls, device lock-in, identity lockout, platform fees](./P03.md#b05ch14p03s03)
  - [B05.CH14.P03.S04 — Debt and collections lock-in: fee cascades, garnishment threats, exploitation of vulnerability](./P03.md#b05ch14p03s04)

- [B05.CH14.P04 — Fee stacks and toll layers (E in the lifeworld)](./P04.md)
  - [B05.CH14.P04.S01 — Intermediaries: brokerage, administration, collections, insurance layers, pay-to-access](./P04.md#b05ch14p04s01)
  - [B05.CH14.P04.S02 — Dark patterns: misleading discounts, bundles, penalty clauses](./P04.md#b05ch14p04s02)
  - [B05.CH14.P04.S03 — Paperwork as E: forms burden as a gate and disciplining mechanism](./P04.md#b05ch14p04s03)
  - [B05.CH14.P04.S04 — Evidence pack: minimum data/contracts needed to prove E-layers](./P04.md#b05ch14p04s04)

- [B05.CH14.P05 — Shock moments (pre-OBA): what breaks the R/B tail](./P05.md)
  - [B05.CH14.P05.S01 — Small shock: broken washing machine/phone → emergency credit → fee cascade](./P05.md#b05ch14p05s01)
  - [B05.CH14.P05.S02 — Time shock: sick child/schedule change → income dip + extra childcare costs](./P05.md#b05ch14p05s02)
  - [B05.CH14.P05.S03 — Price shock: energy/food rises → arrears → disconnection threat](./P05.md#b05ch14p05s03)
  - [B05.CH14.P05.S04 — Administrative shock: clawback, wrong decision, long appeal cycle](./P05.md#b05ch14p05s04)

- [B05.CH14.P06 — OBA intervention set (after): what changes structurally](./P06.md)
  - [B05.CH14.P06.S01 — L reduction: baseline access (energy/food), rent rails/commons housing, fee-stack collapse](./P06.md#b05ch14p06s01)
  - [B05.CH14.P06.S02 — Security/buffers: income floor, emergency buffer, fast restructuring (link CH04/CH06)](./P06.md#b05ch14p06s02)
  - [B05.CH14.P06.S03 — Exit rails: portability, ban on punitive fees, public options in essentials](./P06.md#b05ch14p06s03)
  - [B05.CH14.P06.S04 — Execution: one-stop interface, minimal proof burden, time-bounded contestability](./P06.md#b05ch14p06s04)

- [B05.CH14.P07 — “Commons exits”: concrete switches out of lock-in contracts](./P07.md)
  - [B05.CH14.P07.S01 — Housing: from private lock-in renting → commons/public alternative; moving friction down](./P07.md#b05ch14p07s01)
  - [B05.CH14.P07.S02 — Energy: from penalty/advance-payment lock-in → baseline access + transparent tariffs](./P07.md#b05ch14p07s02)
  - [B05.CH14.P07.S03 — Digital: from platform lock-in → interoperable baseline services and portability](./P07.md#b05ch14p07s03)
  - [B05.CH14.P07.S04 — Debt: from collections ecosystem → restructuring + fee waivers + stop on cascades](./P07.md#b05ch14p07s04)

- [B05.CH14.P08 — New day structure: time, work, and care after friction reduction](./P08.md)
  - [B05.CH14.P08.S01 — Schedule predictability: less schedule capture; better compatibility with care](./P08.md#b05ch14p08s01)
  - [B05.CH14.P08.S02 — Administrative time: fewer forms/calls/delays; lower “time burden”](./P08.md#b05ch14p08s02)
  - [B05.CH14.P08.S03 — Health and stress: not as a KPI, but as an experience signal with procedural input](./P08.md#b05ch14p08s03)
  - [B05.CH14.P08.S04 — Agency: choice-space grows because exit becomes real (not only “in theory”)](./P08.md#b05ch14p08s04)

- [B05.CH14.P09 — Measurable “before/after” outputs (case dashboard)](./P09.md)
  - [B05.CH14.P09.S01 — B,T,N,L,R: values/percentiles + uncertainty bands + method_id](./P09.md#b05ch14p09s01)
  - [B05.CH14.P09.S02 — Lock-in metrics: switching costs, penalty incidence, arrears/disconnects, dispute duration](./P09.md#b05ch14p09s02)
  - [B05.CH14.P09.S03 — Shock absorption: time-to-recovery, buffer adequacy, default/eviction avoidance](./P09.md#b05ch14p09s03)
  - [B05.CH14.P09.S04 — Commons metrics: access coverage, wait times, incident rates, service levels (aggregated)](./P09.md#b05ch14p09s04)

- [B05.CH14.P10 — Dispute-flow and errors (what if it goes wrong)](./P10.md)
  - [B05.CH14.P10.S01 — Wrong decision: fast correction, provisional relief, restatement of the calculation](./P10.md#b05ch14p10s01)
  - [B05.CH14.P10.S02 — Provider abuse: anomaly → audit → contract rewrite/sanction](./P10.md#b05ch14p10s02)
  - [B05.CH14.P10.S03 — System abuse: privacy breach or overreach → hard stop and rollback](./P10.md#b05ch14p10s03)
  - [B05.CH14.P10.S04 — Protection: no retaliation, humane procedures, transparent logs](./P10.md#b05ch14p10s04)

- [B05.CH14.P11 — Residual frictions and edge cases (honesty about what remains)](./P11.md)
  - [B05.CH14.P11.S01 — Transition costs: moving, reskilling, temporary wait times](./P11.md#b05ch14p11s01)
  - [B05.CH14.P11.S02 — Non-eliminable shocks: severe illness/regional crises; role of fallback commons](./P11.md#b05ch14p11s02)
  - [B05.CH14.P11.S03 — Cultural adaptation: status/identity shifts with changes in work and consumption](./P11.md#b05ch14p11s03)
  - [B05.CH14.P11.S04 — Risk: “lower R/B group” gets stigmatized; mitigate via universal design](./P11.md#b05ch14p11s04)

- [B05.CH14.P12 — Failure modes and hard stops (case as an early-warning system)](./P12.md)
  - [B05.CH14.P12.S01 — Storytelling-washing: nice day but no measurement linkage → disqualification](./P12.md#b05ch14p12s01)
  - [B05.CH14.P12.S02 — New lock-in: public systems that exclude/punish → non-conform](./P12.md#b05ch14p12s02)
  - [B05.CH14.P12.S03 — Selective execution: differences by municipality without transparency → legitimacy breach](./P12.md#b05ch14p12s03)
  - [B05.CH14.P12.S04 — Fail-closed: if the “after” case shows a worse tail (more arrears/lock-in), redesign is mandatory](./P12.md#b05ch14p12s04)
