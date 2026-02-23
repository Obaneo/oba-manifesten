| id              | book | chapter | type   | status |
|-----------------|------|---------|--------|--------|
| B05.CH16.README | B05  | CH16    | readme | draft  |

<a id="b05ch16readme"></a>
# B05.CH16 — Day-in-the-life III: high income/wealth (cap events, reallocation, adaptation, and evasion)

This chapter is the third **day-in-the-life** module for OBA. It translates the framework into a concrete **high income/wealth** case:
the lifeworld at the top, where **I-MAX** and **W-MAX** become real events, and where system credibility depends on
**substance-over-form**, **UBC look-through**, and robust **anti-evasion** enforcement.

The purpose is explicitly **non-caricature** and **non-PR**. The chapter must make visible—in testable terms—how caps operate, how
breaches are remedied without systemic damage, and how evasion routes are detected and neutralised. Narrative is permitted only as a
carrier. The truth condition is **measurement linkage**: `definitionset_id`, `method_id`, explicit time windows, explicit valuation and
exposure rules, and explicit uncertainty bands.

CH16 is designed to be **anti-washing** and **FAIL-CLOSED**. A “rich person story” without explicit evasion routes and without
enforcement logic is unrealistic and **NON-CONFORM**. Likewise, a case that smuggles in bespoke carve-outs, tolerates opacity, or
“negotiates” enforcement is non-conforming. This module is also an early-warning tool: if shadow regimes grow (offshore/crypto/synthetics
bypassing rails), or if enforcement becomes arbitrary/selective, the system must escalate via tighter presumptions, forbidden-channel
rails, and transparent precedents.

---

## Conformance gates (chapter-level)

A CH16 case **MUST**:
- Declare provenance: `definitionset_id`, `method_id`, `case_mode`, and comparable `time_window_pre/post`.
- Emit explicit **cap events** (I-MAX and W-MAX triggers, timing, valuation logic) and associated remedies.
- Provide a **UBC control map** (look-through) for holdings, trusts, SPVs, partnerships, nominee structures, and offshore exposure.
- Model **evasion attempts** (legal, technical, financial) and apply detection/remedy logic:
  - substance-over-form,
  - denial-of-benefits / look-through allocation,
  - economic exposure tests (synthetics/leverage),
  - conservative valuation under opacity,
  - forbidden channels + tagging + leakage tests.
- Provide dispute-flow rules with boundaries (escrow/lockbox, no suspension under opacity/flight risk, time-bounded decisions).

A CH16 case **MUST NOT**:
- Use caricature or moral theatre as proof; only testable mechanisms.
- Treat opacity as “unknown”; opacity triggers conservative presumptions and provisional enforcement.
- Permit bespoke deals (“strategic capital” carve-outs) or discretionary exceptions outside versioned rules.

---

## Scope and exclusions

**In scope**
- High **I** and/or high **W** profiles, including:
  - salary/bonus, dividends/interest, fees/royalties, carry, in-kind perks.
- Ownership and control architectures:
  - holdings, trusts, SPVs, partnerships, nominee/beneficial ownership, offshore exposure.
- Wealth composition and valuation risk:
  - public equity, real estate, private funds, derivatives/synthetics, IP claims.
- Cross-cap arbitrage strategies and detection.
- Evasion routes:
  - legal form shifts, treaty/IP-box shopping,
  - technical shifts (platform tolls, crypto rails, surveillance rent),
  - financial shifts (leverage, securitization, synthetics).
- International mobility:
  - re-domiciliation, control-center moves, asset migration, capital flight risk.

**Out of scope**
- Personal moral judgement about wealth.
- “Confessional” biography writing.
- Non-testable claims about motives or psychology as proof.

---

## Artifacts emitted (chapter outputs)

CH16 **MUST** emit, at minimum:
- Baseline income/wealth architecture + UBC control map (P02).
- Cap event log (P03) including opacity handling and timing.
- Remedy choice log (P04) including escrow/lockbox where relevant.
- Adaptation vs evasion taxonomy application (P05).
- Evasion route inventories + remedy mappings (P06–P08).
- Dispute-flow register with boundary conditions (P09).
- International mobility trigger map (P10).
- Lifeworld impact summary (bounded consumption, power and status shifts) (P11).
- Case dashboard schema (P12).
- Residual risk / adaptation war register (P13).
- Failure mode / hard-stop register (P14).

---

## How to use this chapter

- If you are **explaining caps concretely**: use the cap events (P03) and remedies (P04) to show how I-MAX/W-MAX are applied without
  destroying enterprise activity or turning into bespoke bargaining.
- If you are **designing anti-evasion policy**: use the evasion route modules (P06–P08) as a shift taxonomy and remedy cookbook:
  substance-over-form, look-through, denial-of-benefits, exposure tests, conservative valuation under opacity.
- If you are **building auditpacks and enforcement logic**: use P03/P09/P12 to specify disclosure duties, presumptions, escrow/lockbox,
  time-bounded dispute cycles, and precedent/versioning.
- If you are **designing international exit and leakage controls**: use P10 to model mobility triggers, exit tax hooks, withholding
  regimes, and temporary capital controls under leakage.
- If you are **auditing legitimacy**: use P12 (dashboard) and P14 (hard stops) to detect carve-outs, shadow regime growth, or arbitrary
  enforcement.

---

## Structure

P01 — Purpose, scope, and method for the high-income/wealth case  
P02 — Baseline profile (pre-OBA): income and wealth architecture  
P03 — Cap events: triggers and timing (W-MAX and I-MAX)  
P04 — Remedies upon breach: reallocation without system damage  
P05 — Adaptation: legitimate adjustment versus evasion  
P06 — Evasion routes I: legal shifts (form over substance)  
P07 — Evasion routes II: technical shifts (platforms, bundling, digital assets)  
P08 — Evasion routes III: financial shifts (securitization, leverage, synthetics)  
P09 — Dispute-flow: how high positions appeal (and where the boundary lies)  
P10 — International mobility: exit, re-domiciliation, and capital flight  
P11 — Lifeworld impact: what it feels like “at the top” (without sentimentality)  
P12 — Measurable “before/after” outputs (case dashboard)  
P13 — Residual risks and the adaptation war  
P14 — Failure modes and hard stops  

---

## Status

This chapter is **normative** for representing high-income/wealth lifeworld dynamics inside OBA. A credible OBA system cannot stop at
low- and middle-household improvements; it must also demonstrate that caps are enforceable at the top without collapsing into elite
exceptions, opacity tolerance, or a growing shadow regime.

Accordingly, **evasion modeling and enforcement logic are constitutive requirements** in CH16. Any narrative that claims “caps work” must
be able to instantiate this template: emit cap events, apply UBC look-through, model shifts/evasion, trigger presumptions under opacity,
and produce auditable remedies and dispute outcomes. Conversely, if implementation shows carve-outs, opaque structures that evade
disclosure, or selective/arbitrary enforcement, that is evidence of **NON-CONFORM** that must trigger escalation and redesign under the
hard-stop logic (P14).
