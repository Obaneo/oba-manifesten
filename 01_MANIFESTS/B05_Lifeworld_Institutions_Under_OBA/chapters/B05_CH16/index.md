| id             | book | chapter | type          | status |
|----------------|------|---------|---------------|--------|
| B05.CH16.INDEX | B05  | CH16    | chapter-index | draft  |

<a id="b05ch16index"></a>
# B05.CH16 — Day-in-the-life III: high income/wealth (cap events, reallocation, adaptation, and evasion)

This chapter is the third **day-in-the-life** module for OBA. It operationalises the framework in a **high income/wealth** case: the
lifeworld at the top, where **I-MAX** and **W-MAX** become concrete events, and where the system’s credibility depends on
**substance-over-form**, **UBC look-through**, and robust **anti-evasion enforcement**. The purpose is explicitly non-caricature and
non-PR: it must make visible, in testable terms, how caps operate, how remedies reallocate without system damage, and how evasion routes
are detected and neutralised.

CH16 binds the case to OBA’s canonical rails (**B,T,N,L,R; I-MAX/W-MAX caps; P/E/C; control/benefit/block; UBC look-through; auditpacks;
forbidden channels and leakage tests; contestability and dispute-flow**). The chapter is fail-closed: a case that does not explicitly
model **evasion attempts**, **shift taxonomies**, and **enforcement logic** is unrealistic and **NON-CONFORM**.

---

## Conformance summary (chapter-level gates)

A CH16 case **MUST**:
- Declare provenance: `definitionset_id`, `method_id`, `case_mode`, and comparable `time_window_pre/post`.
- Emit explicit **cap events** (I-MAX and W-MAX triggers, timing, valuation logic) and associated remedies (levy/clawback, escrow/lockbox,
  divestment, conversion to commons funding).
- Provide an explicit **UBC control map** (look-through) for holdings, trusts, SPVs, partnerships, nominee structures, and offshore
  exposure.
- Model **evasion routes** (legal, technical, financial) and apply detection/remedy logic (substance-over-form, denial-of-benefits,
  exposure look-through, conservative valuation, forbidden channels + leakage tests).
- Provide dispute-flow rules with boundaries (no suspension under opacity/flight risk; escrow requirements; versioned precedents).

A CH16 case **MUST NOT**:
- Caricature the subject (no moral theatre); only testable mechanisms and conformance rules.
- Treat disclosure opacity as “unknown”; opacity triggers conservative presumptions and provisional enforcement (FAIL-CLOSED).
- Allow bespoke deals or elite carve-outs; remedies must be rule-bound and versioned.

---

## Depends on (canonical references to be resolved in-repo)

- Cap definitions and invariants: `I-MAX`, `W-MAX`, cross-cap arbitrage detection
- UBC definitions: control/benefit/block synthesis; look-through and economic exposure tests
- P/E/C classification for fees, carry, platform take-rates, surveillance rent
- Codex channel objects: forbidden channels, tagging, leakage tests, auditpacks, evidence classes
- Dispute-flow rails: time bounds, provisional enforcement, escrow/lockbox, precedent publication/versioning

---

## Emitted artifacts (chapter outputs)

CH16 **MUST** emit, at minimum:
- Baseline income/wealth architecture + UBC control map (P02)
- Cap event log (P03) including opacity presumptions and timing
- Remedy choice log (P04) with rule-bound options and conformance status
- Adaptation vs evasion taxonomy application (P05)
- Evasion route inventories + remedy mappings (P06–P08)
- Dispute-flow register including escrow/flight-risk boundaries (P09)
- International mobility/exit controls trigger mapping (P10)
- Lifeworld impact summary (bounded consumption, power, status shifts) (P11)
- Case dashboard schema (P12)
- Residual risk / adaptation war register (P13)
- Failure mode / hard-stop register (P14)

---

## Paragraphs

- [B05.CH16.P01 — Purpose, scope, and method for the high-income/wealth case](./P01.md)
  - [B05.CH16.P01.S01 — Purpose: make visible how caps and anti-evasion operate in the lifeworld (no caricature, but testable)](./P01.md#b05ch16p01s01)
  - [B05.CH16.P01.S02 — Scope: high I and/or high W, ownership structures, carry/fees, real estate/portfolios, international mobility](./P01.md#b05ch16p01s02)
  - [B05.CH16.P01.S03 — Method: case template with cap events, remedies, auditpacks, dispute-flow, and evasion attempts](./P01.md#b05ch16p01s03)
  - [B05.CH16.P01.S04 — Fail-closed: a case without explicit evasion routes (shifts) and without enforcement logic is unrealistic](./P01.md#b05ch16p01s04)

- [B05.CH16.P02 — Baseline profile (pre-OBA): income and wealth architecture](./P02.md)
  - [B05.CH16.P02.S01 — BRUTO (B): salary/bonus + dividends/interest + fees/royalties + carry + in-kind perks](./P02.md#b05ch16p02s01)
  - [B05.CH16.P02.S02 — Structure: holdings, trusts, SPVs, partnerships, nominee ownership, offshore exposure](./P02.md#b05ch16p02s02)
  - [B05.CH16.P02.S03 — Wealth (W): asset mix (equity, real estate, private funds, derivatives, IP claims) and valuation risks](./P02.md#b05ch16p02s03)
  - [B05.CH16.P02.S04 — Control map: where ultimate control and block power actually sit (UBC look-through)](./P02.md#b05ch16p02s04)

- [B05.CH16.P03 — Cap events: triggers and timing (W-MAX and I-MAX)](./P03.md)
  - [B05.CH16.P03.S01 — I-MAX event: bonus/vesting/carry realization; deferral look-back; in-kind reclassification](./P03.md#b05ch16p03s01)
  - [B05.CH16.P03.S02 — W-MAX event: portfolio appreciation, concentrated positions, private valuations, property aggregation](./P03.md#b05ch16p03s02)
  - [B05.CH16.P03.S03 — Cross-cap arbitrage: I→W shifting via deferral, debt, SPV pricing (detection)](./P03.md#b05ch16p03s03)
  - [B05.CH16.P03.S04 — Fail-closed: opacity (no disclosure) → conservative presumption + provisional enforcement](./P03.md#b05ch16p03s04)

- [B05.CH16.P04 — Remedies upon breach: reallocation without system damage](./P04.md)
  - [B05.CH16.P04.S01 — Remedy set: levy/clawback, conversion to commons funding (C), divestment, lockbox/escrow](./P04.md#b05ch16p04s01)
  - [B05.CH16.P04.S02 — Choice space: multiple routes, but within fixed rules (no bespoke deals)](./P04.md#b05ch16p04s02)
  - [B05.CH16.P04.S03 — Lifeworld impact: consumption can continue within I-MAX, but claim power and rentier positions decline](./P04.md#b05ch16p04s03)
  - [B05.CH16.P04.S04 — Public consequence: conformance status and audit summary (aggregated, privacy tiers)](./P04.md#b05ch16p04s04)

- [B05.CH16.P05 — Adaptation: legitimate adjustment versus evasion](./P05.md)
  - [B05.CH16.P05.S01 — Legitimate: shift toward production/commons investment, less leverage, transparent structures](./P05.md#b05ch16p05s01)
  - [B05.CH16.P05.S02 — Pseudo-legitimate: relabeling into consultancy/licensing; perks; offshore SPVs; synthetic exposure](./P05.md#b05ch16p05s02)
  - [B05.CH16.P05.S03 — New status arenas: gatekeeping, reputation, network access (link to CH13)](./P05.md#b05ch16p05s03)
  - [B05.CH16.P05.S04 — Detection: shift taxonomy applied to behavior patterns, contracts, and graph structures](./P05.md#b05ch16p05s04)

- [B05.CH16.P06 — Evasion routes I: legal shifts (form over substance)](./P06.md)
  - [B05.CH16.P06.S01 — Reclassification: wage→fee→royalty; dividend→loan; rent→service contract](./P06.md#b05ch16p06s01)
  - [B05.CH16.P06.S02 — IP-box and treaty shopping: profit shifting via licensing and mailbox “substance”](./P06.md#b05ch16p06s02)
  - [B05.CH16.P06.S03 — Nominee/beneficial ownership: hiding UBC; trustees; layered vehicles](./P06.md#b05ch16p06s03)
  - [B05.CH16.P06.S04 — Remedy: substance-over-form, look-through, denial-of-benefits, automatic presumptions](./P06.md#b05ch16p06s04)

- [B05.CH16.P07 — Evasion routes II: technical shifts (platforms, bundling, digital assets)](./P07.md)
  - [B05.CH16.P07.S01 — Platform arbitrage: self-preferencing, API gating, marketplace fees as extraction](./P07.md#b05ch16p07s01)
  - [B05.CH16.P07.S02 — Crypto/DeFi rails: shadow channels, mixers, wrapped assets; payment rail governance (link to Codex)](./P07.md#b05ch16p07s02)
  - [B05.CH16.P07.S03 — Data extraction: surveillance rent as a new cashflow; reclassify as E](./P07.md#b05ch16p07s03)
  - [B05.CH16.P07.S04 — Remedy: forbidden channels, tagging, leakage tests, rail-level enforcement](./P07.md#b05ch16p07s04)

- [B05.CH16.P08 — Evasion routes III: financial shifts (securitization, leverage, synthetics)](./P08.md)
  - [B05.CH16.P08.S01 — Fee stacks: management fees, carry, structuring fees in fund stacks](./P08.md#b05ch16p08s01)
  - [B05.CH16.P08.S02 — Leverage and collateral: debt used to mask W or extract cashflows](./P08.md#b05ch16p08s02)
  - [B05.CH16.P08.S03 — Synthetics: total return swaps, options, contracts for difference as hidden exposure](./P08.md#b05ch16p08s03)
  - [B05.CH16.P08.S04 — Remedy: look-through to economic exposure, conservative valuation, reporting duty](./P08.md#b05ch16p08s04)

- [B05.CH16.P09 — Dispute-flow: how high positions appeal (and where the boundary lies)](./P09.md)
  - [B05.CH16.P09.S01 — Right to appeal: reproducible calculations, access to methods and evidence packs](./P09.md#b05ch16p09s01)
  - [B05.CH16.P09.S02 — Limits: no suspension under flight risk/opacity; escrow/lockbox for disputed amounts](./P09.md#b05ch16p09s02)
  - [B05.CH16.P09.S03 — Transparency: aggregated publication of dispute outcomes and precedents (versioned)](./P09.md#b05ch16p09s03)
  - [B05.CH16.P09.S04 — Failure mode: legal delay as evasion → deadlines, presumptions, sanction multipliers](./P09.md#b05ch16p09s04)

- [B05.CH16.P10 — International mobility: exit, re-domiciliation, and capital flight](./P10.md)
  - [B05.CH16.P10.S01 — Exit triggers: end of residency, relocation of control center, asset migration (link to exit-tax templates)](./P10.md#b05ch16p10s01)
  - [B05.CH16.P10.S02 — Capital controls: reporting, withholding, approval regimes under leakage (temporary, sunset)](./P10.md#b05ch16p10s02)
  - [B05.CH16.P10.S03 — Treaty mismatch: denial-of-benefits, look-through allocation, withholding hooks](./P10.md#b05ch16p10s03)
  - [B05.CH16.P10.S04 — Consequence: mobility remains possible, but not as arbitrage against core invariants](./P10.md#b05ch16p10s04)

- [B05.CH16.P11 — Lifeworld impact: what it feels like “at the top” (without sentimentality)](./P11.md)
  - [B05.CH16.P11.S01 — Consumption and freedom: more bounded by I-MAX, but broad choice remains within the cap](./P11.md#b05ch16p11s01)
  - [B05.CH16.P11.S02 — Power: less block power via concentrated capital, platform positions, and claim stacks](./P11.md#b05ch16p11s02)
  - [B05.CH16.P11.S03 — Status: shifts toward reputation/competence; risk of new elite forms (CH13)](./P11.md#b05ch16p11s03)
  - [B05.CH16.P11.S04 — Evasion pressure: higher pressure to be creative; the system must keep shift detection robust](./P11.md#b05ch16p11s04)

- [B05.CH16.P12 — Measurable “before/after” outputs (case dashboard)](./P12.md)
  - [B05.CH16.P12.S01 — Cap events: frequency, magnitude, remedies chosen, compliance timing](./P12.md#b05ch16p12s01)
  - [B05.CH16.P12.S02 — Evasion indicators: structure patterns, offshore exposure, synthetic usage, fee-stack depth (aggregated)](./P12.md#b05ch16p12s02)
  - [B05.CH16.P12.S03 — Enforcement: audits, finding severities, dispute durations, sanction outcomes](./P12.md#b05ch16p12s03)
  - [B05.CH16.P12.S04 — System impact: effects on concentration, platform take-rates, essentials L (macro→micro link)](./P12.md#b05ch16p12s04)

- [B05.CH16.P13 — Residual risks and the adaptation war](./P13.md)
  - [B05.CH16.P13.S01 — “Cat-and-mouse”: innovation in evasion; need versioning and rapid reclassification](./P13.md#b05ch16p13s01)
  - [B05.CH16.P13.S02 — Capture risk: pressure on legislation/auditors/media; mitigated via audit-on-the-auditor](./P13.md#b05ch16p13s02)
  - [B05.CH16.P13.S03 — International pressure: sanctions/retaliation; scenarios in Book 2](./P13.md#b05ch16p13s03)
  - [B05.CH16.P13.S04 — Unintended collateral: do not choke legitimate entrepreneurship; parameter tuning within rails](./P13.md#b05ch16p13s04)

- [B05.CH16.P14 — Failure modes and hard stops](./P14.md)
  - [B05.CH16.P14.S01 — Elite carve-outs: exceptions for “strategic capital” → compatibility breach](./P14.md#b05ch16p14s01)
  - [B05.CH16.P14.S02 — Shadow regime: parallel rails (crypto/offshore) grows → leakage breach and escalation to controls](./P14.md#b05ch16p14s02)
  - [B05.CH16.P14.S03 — Overenforcement: arbitrariness or selectivity → legitimacy breach; requires transparent precedents](./P14.md#b05ch16p14s03)
  - [B05.CH16.P14.S04 — Fail-closed: under structural opacity/obstruction, stricter presumptions, rail restrictions, and status downgrades auto-activate](./P14.md#b05ch16p14s04)
