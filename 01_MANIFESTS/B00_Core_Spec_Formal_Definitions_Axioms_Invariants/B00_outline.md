

# B00.CH01 Kernel: Core Spec as Canon  
*(scope, definition-set ID, anti-drift, reading contract)*

## B00.CH01.P01 Purpose and function of the Core Spec

### B00.CH01.P01.S01 Core Spec as canonical source of truth
### B00.CH01.P01.S02 Objective: semantic closure, testability, enforceability
### B00.CH01.P01.S03 Objective: anti-washing and anti-drift (preventing fake alignment)
### B00.CH01.P01.S04 Non-goals: rhetoric, political platform, sector storytelling

## B00.CH01.P02 Scope delimitation and layer model

### B00.CH01.P02.S01 What belongs inside the Core Spec (definitions, axioms, invariants, conflict rules)
### B00.CH01.P02.S02 What does not belong in the Core Spec (explanatory text, casework, implementation choices)
### B00.CH01.P02.S03 Relation to Books 1–4 (reference contract: refer, do not re-define)
### B00.CH01.P02.S04 Relation to Codex/Standards (engineering artefacts as derived implementation layer)

## B00.CH01.P03 Definition-set identity and canonical reference

### B00.CH01.P03.S01 Definition-set ID: format and scope (global, sector, jurisdiction)
### B00.CH01.P03.S02 Canonical term registries (terms, symbols, quantities)
### B00.CH01.P03.S03 Normative distinction: definitions vs parameters vs examples
### B00.CH01.P03.S04 Reference units: paragraph IDs and citation rules

## B00.CH01.P04 Anti-drift rules (semantic discipline)

### B00.CH01.P04.S01 Ban on shadow definitions and synonym substitution
### B00.CH01.P04.S02 Hierarchy of interpretation sources (Core Spec > Codex > books > commentary)
### B00.CH01.P04.S03 Consistency requirement: symbols and terms are injective (one term → one meaning)
### B00.CH01.P04.S04 Bridge texts / restatements: allowed when explicitly non-canonical and traceable

## B00.CH01.P05 Reading contract for implementation and evaluation

### B00.CH01.P05.S01 Conservative interpretation: in doubt, no expansion of power or scope
### B00.CH01.P05.S02 Fail-closed: unmeasurable or unauditable = non-conform until specified
### B00.CH01.P05.S03 Evidence and measurement duty: claims require reproducible testing
### B00.CH01.P05.S04 Minimum documentation: what every implementation must publish to carry an “OBA claim”

## B00.CH01.P06 Canon governance and change discipline

### B00.CH01.P06.S01 Change classes: patch / minor / major (semantic)
### B00.CH01.P06.S02 Change procedure: proposal, review, audit, ratification
### B00.CH01.P06.S03 Deprecation and backward compatibility: conditions and timelines
### B00.CH01.P06.S04 Emergency patches and rollback: incident regime without semantic erosion

## B00.CH01.P07 Publication and integrity rules

### B00.CH01.P07.S01 Publication requirements: accessibility, archiving, hash/signature, immutable releases
### B00.CH01.P07.S02 Transparency requirements: changelog, rationale, impact analysis on invariants
### B00.CH01.P07.S03 Fork protocol: name usage, compatibility labels, boundaries
### B00.CH01.P07.S04 Interoperability: mapping to sector canvases and jurisdiction profiles

# B00.CH02 Canonical notation and object model  
*(B,T,N,L,R; P/E/C; W-MAX/I-MAX; ΔM; commons; control/benefit/block)*

## B00.CH02.P01 Notation principles and symbol registry

### B00.CH02.P01.S01 Symbols are canonical and context-free (no local redefinitions)
### B00.CH02.P01.S02 Quantities have type, unit, domain and time index
### B00.CH02.P01.S03 Subscripts/superscripts for jurisdiction, sector, cohort, actor
### B00.CH02.P01.S04 Operators and functions (Σ, Π, Δ, f(·), g(·)) and their semantics

## B00.CH02.P02 Time, resolution and aggregation (indexing)

### B00.CH02.P02.S01 Time index t and standard resolutions (day/month/year)
### B00.CH02.P02.S02 Aggregation rules (additive, mean, percentiles, distributions)
### B00.CH02.P02.S03 Stock-versus-flow conventions (balance sheet vs income/result)
### B00.CH02.P02.S04 Reconciliation: micro→macro consistency and accounting identities

## B00.CH02.P03 Actor, position and role model (economic entities)

### B00.CH02.P03.S01 Actor (natural person) vs entity (legal person/vehicle)
### B00.CH02.P03.S02 Positions: owner, steward, operator, platform, financier
### B00.CH02.P03.S03 Roles as attributes (control, benefit, block, duty)
### B00.CH02.P03.S04 Consolidation and look-through object relations (graph)

## B00.CH02.P04 Flow and contract objects (transaction model)

### B00.CH02.P04.S01 Flow object: {payer, payee, amount, timestamp, contract, label}
### B00.CH02.P04.S02 Contract object: price rule, indexation, lock-in, exit, penalties
### B00.CH02.P04.S03 Supply chains and platform stacks (chain attribution)
### B00.CH02.P04.S04 Avoiding double counting: gross/net and internal recharging

## B00.CH02.P05 Core variables B,T,N,L,R (remainder-space algebra)

### B00.CH02.P05.S01 B (gross income/receipts): definition and measurement framework
### B00.CH02.P05.S02 T (transfer/tax/contribution): definition and classification
### B00.CH02.P05.S03 L (burdens/essentials/claim layers): definition and decomposition
### B00.CH02.P05.S04 Identities: N = B − T; R = N − L; distribution profiles

## B00.CH02.P06 P/E/C classification (production, extraction, commons)

### B00.CH02.P06.S01 P: production- and maintenance-linked value creation (functional output)
### B00.CH02.P06.S02 E: toll/lock-in/claim above functional cost (parasitic component)
### B00.CH02.P06.S03 C: commons contribution (build/maintenance/access) and allocation attributes
### B00.CH02.P06.S04 Attribution at flow level and along chains (P/E/C splitting)

## B00.CH02.P07 Cap objects: W-MAX and I-MAX (limits and bases)

### B00.CH02.P07.S01 W-base: wealth/claims/rights as stock (incl. equivalents)
### B00.CH02.P07.S02 I-base: income/flows as flow (incl. deferral and substitutes)
### B00.CH02.P07.S03 Cap functions: limit, skimming/reallocation, exceptions (canonical)
### B00.CH02.P07.S04 Measurement and valuation conventions (market, book, model; conservatism)

## B00.CH02.P08 ΔM as allocation interface (monetary space)

### B00.CH02.P08.S01 Definition of ΔM: change in monetary capacity/space per t
### B00.CH02.P08.S02 Channel objects: {source, channel, destination, conditions, audit log}
### B00.CH02.P08.S03 Prohibited channels and anti-leakage definitions (asset support, claim stacks)
### B00.CH02.P08.S04 Traceability requirement: ability to trace ΔM→C/maintenance/R/B effects

## B00.CH02.P09 Commons object model (access and maintenance)

### B00.CH02.P09.S01 Commons as order object: access, boundary rules, maintenance duty
### B00.CH02.P09.S02 ΔG (growth/quality/capacity) as state variable and metric set
### B00.CH02.P09.S03 Minimum governance: powers, liability, contestability
### B00.CH02.P09.S04 Public option, hybrid layers and interoperability with markets

## B00.CH02.P10 Control/benefit/block: canonical relational tests

### B00.CH02.P10.S01 Control test: decision power (direct/indirect, de facto/de jure)
### B00.CH02.P10.S02 Benefit test: economic benefit (cashflows, upside, risk transfer)
### B00.CH02.P10.S03 Block test: veto/exit friction/lock-in as power (negative control)
### B00.CH02.P10.S04 Composite UBC consolidation: graph evaluation and conflict rules

# B00.CH03 Definition set I: production, extraction and commons (P/E/C)

## B00.CH03.P01 Purpose, scope and normative status of P/E/C

### B00.CH03.P01.S01 P/E/C as canonical classification for all relevant flows  
### B00.CH03.P01.S02 P/E/C is functional (effect on order), not rhetorical (label)  
### B00.CH03.P01.S03 Scope of application: households, firms, state, platforms, finance  
### B00.CH03.P01.S04 Relation to caps, R/B and ΔM (linkages and dependencies)  

## B00.CH03.P02 Definition of P: production and maintenance (productive)

### B00.CH03.P02.S01 Output criterion: deliverable function/value without toll mechanism  
### B00.CH03.P02.S02 Cost criterion: functional costs + normal margin (bounded)  
### B00.CH03.P02.S03 Maintenance as P: preservation of capacity/quality (ΔG stabilisation)  
### B00.CH03.P02.S04 P in networks: interoperability, open standards, non-exclusivity  

## B00.CH03.P03 Definition of E: extraction (parasitic component)

### B00.CH03.P03.S01 Toll criterion: price > functional costs through power/lock-in  
### B00.CH03.P03.S02 Lock-in criterion: switching costs, exit friction, contractual lock  
### B00.CH03.P03.S03 Claim-stack criterion: interest/fee stacks/monopoly rents above function  
### B00.CH03.P03.S04 Information asymmetry as E-driver: deception, dark patterns, bundling  

## B00.CH03.P04 Definition of C: commons contribution (build and maintenance)

### B00.CH03.P04.S01 C as allocation to public/commons capacity (ΔG↑ or ΔG stabilisation)  
### B00.CH03.P04.S02 C as access: public option, open access, non-discrimination  
### B00.CH03.P04.S03 C as maintenance duty: lifecycle, service levels, repairability  
### B00.CH03.P04.S04 C versus “public ownership”: order-properties prevail over ownership form  

## B00.CH03.P05 P/E/C at flow level: classification rule and minimum metadata

### B00.CH03.P05.S01 Flow object: amount, counterparty, contract, price rule, lock-in features  
### B00.CH03.P05.S02 Primary attribution: default rules per contract type and market structure  
### B00.CH03.P05.S03 Secondary attribution: correction based on power/exit/alternatives  
### B00.CH03.P05.S04 Uncertainty: bands, conservatism, fail-closed when data is missing  

## B00.CH03.P06 Decomposition: a single payment can contain P+E (and sometimes C)

### B00.CH03.P06.S01 Split rule: functional component (P) + toll component (E)  
### B00.CH03.P06.S02 Tariff and bundle decomposition: licences, subscriptions, platform fees, add-ons  
### B00.CH03.P06.S03 Vertical chain: pass-through, internal fees, transfer pricing splitting  
### B00.CH03.P06.S04 Rules against double extraction: fee stacks and cascade detection  

## B00.CH03.P07 Power as classification parameter (structural cause of E)

### B00.CH03.P07.S01 Market power: concentration, entry barriers, natural monopolies  
### B00.CH03.P07.S02 Platform power: ranking/curation, API choke, data lead, bundling  
### B00.CH03.P07.S03 Financial power: collateral dominance, refinancing lock, roll-over pressure  
### B00.CH03.P07.S04 State power: licences/concessions as potential E source (capture risk)  

## B00.CH03.P08 Edge cases and border cases (canonical decision rules)

### B00.CH03.P08.S01 Innovation rent vs toll: when it is temporarily P and when it becomes E  
### B00.CH03.P08.S02 IP/licences: boundary between functional remuneration and lock-in toll  
### B00.CH03.P08.S03 Health/education: P-maintenance versus administrative E-layers  
### B00.CH03.P08.S04 Data/advertising: attention extraction, manipulation and hidden price (E)  

## B00.CH03.P09 Relation to R/B: how E translates into L and remainder space

### B00.CH03.P09.S01 E→L mechanism: essentials become claim layers (housing/energy/health/interest)  
### B00.CH03.P09.S02 P→R mechanism: productive + maintenance lowers vulnerability and increases buffer  
### B00.CH03.P09.S03 C→R mechanism: public option/commons reduces L structurally  
### B00.CH03.P09.S04 Distribution requirement: P/E/C evaluation at cohort level, not just macro averages  

## B00.CH03.P10 Relation to caps (W-MAX/I-MAX): E as input, caps as brake

### B00.CH03.P10.S01 E accumulates in W/I via claim stacks; caps limit the storage  
### B00.CH03.P10.S02 Reallocation rule: cap skimming can be classified as C (under conditions)  
### B00.CH03.P10.S03 Ban on cosmetic caps: relabelling that leaves E untouched is non-conform  
### B00.CH03.P10.S04 Link with anti-avoidance: shifts change form but not function (so E remains E)  

## B00.CH03.P11 Measurement and audit standards for P/E/C

### B00.CH03.P11.S01 Minimum metric set: price/cost, margin bands, lock-in proxies, fee stacks  
### B00.CH03.P11.S02 Audit trail: reproducible derivation of classification per flow/contract  
### B00.CH03.P11.S03 Publication requirements: aggregates + methodology + uncertainty reporting  
### B00.CH03.P11.S04 Escalation: in doubt classify as E unless explicitly rebutted (conservative)  

## B00.CH03.P12 Failure modes and hard stops

### B00.CH03.P12.S01 OBA-washing via semantics: “service”/“innovation” as cover for E  
### B00.CH03.P12.S02 Gaming the classification: bundling, cross-subsidies, shadow prices  
### B00.CH03.P12.S03 Black-box classification is non-conform (non-auditable)  
### B00.CH03.P12.S04 Fail-closed: missing data/controllability → no OBA claim on that component  

# B00.CH04 Definition set II: GROSS→NET→ESSENTIALS→REMAINING SPACE (B,T,N,L,R) and R/B≥α

## B00.CH04.P01 Purpose and scope of Definition set II

### B00.CH04.P01.S01 R/B as primary life-world order indicator (buffer, autonomy, shock resilience)  
### B00.CH04.P01.S02 GROSS→NET→ESSENTIALS→REMAINING SPACE as canonical decomposition (micro and macro)  
### B00.CH04.P01.S03 Scope of application: household, organisation, sector, jurisdiction  
### B00.CH04.P01.S04 Relation to P/E/C, caps and ΔM (linkages and dependencies)  

## B00.CH04.P02 Canonical quantities and base identities (B,T,N,L,R)

### B00.CH04.P02.S01 Definition of B (gross receipts/income; pre-transfer)  
### B00.CH04.P02.S02 Definition of T (levies/transfer-out; tax/fee/mandatory contributions)  
### B00.CH04.P02.S03 Definition of N: N = B − T (net after transfers)  
### B00.CH04.P02.S04 Definition of L (essentials/claim layers; burdens that are not plausibly avoidable)  
### B00.CH04.P02.S05 Definition of R: R = N − L (remaining space as buffer)  

## B00.CH04.P03 Strict classification rules for T (what counts as T)

### B00.CH04.P03.S01 Mandatory contributions to the public order (tax, social security contributions)  
### B00.CH04.P03.S02 Quasi-taxes and mandatory contributions (semi-public, regulated)  
### B00.CH04.P03.S03 Not T: voluntary consumption or contractually avoidable expenditures  
### B00.CH04.P03.S04 Anti-avoidance: relabelling L or E as “voluntary” is not allowed  

## B00.CH04.P04 Strict classification rules for L (burdens/essentials/claim layers)

### B00.CH04.P04.S01 Essentials: housing, energy, health care, mobility, basic connectivity, basic food (canonical set + parameters)  
### B00.CH04.P04.S02 Contractual lock: necessary burdens due to lock-in/exit friction count as L  
### B00.CH04.P04.S03 Financial claim layers: interest/fees/insurance compulsion within essentials count as L  
### B00.CH04.P04.S04 Forbidden inflation of L: luxury/optional upgrades may not be classified as essentials  

## B00.CH04.P05 Distribution requirement: R/B is a profile, not an average

### B00.CH04.P05.S01 Cohorts: income deciles, household type, region, sector, age, vulnerability class  
### B00.CH04.P05.S02 Core statistics: median R/B, p10/p25, share below α, tail risk  
### B00.CH04.P05.S03 Aggregation rules: micro→macro consistency; no masking via Simpson’s paradox  
### B00.CH04.P05.S04 Minimum publication requirement: R/B profiles + methodology + uncertainty  

## B00.CH04.P06 Definition of α (order threshold) and parameter regime

### B00.CH04.P06.S01 α as canonical parameter: meaning (minimum buffer/agency)  
### B00.CH04.P06.S02 α per cohort: allowed variation and prohibited discrimination patterns  
### B00.CH04.P06.S03 Procedure for α changes: evidence, impact analysis, ratification, sunset/rollback  
### B00.CH04.P06.S04 Non-negotiables: no α reduction via semantic redefinition of L or B  

## B00.CH04.P07 Attribution of B (gross) at micro level

### B00.CH04.P07.S01 Gross income components: wages, profit distributions, interest/rent, transfers-in  
### B00.CH04.P07.S02 In-kind and quasi-cash: canonical rules for valuation and inclusion  
### B00.CH04.P07.S03 Seasonal and volatility corrections: smoothing rules (canonical)  
### B00.CH04.P07.S04 Avoid double counting: consolidation across households/entities  

## B00.CH04.P08 R/B as order indicator: interpretation rules and edge cases

### B00.CH04.P08.S01 R/B < 0: structural unsustainability (definition and escalation)  
### B00.CH04.P08.S02 R/B just above 0: fragility; minimum buffer requirement (additional criteria)  
### B00.CH04.P08.S03 High B with low R/B: claim-stack diagnosis (E/L dominance)  
### B00.CH04.P08.S04 Low B with high R/B: detection of measurement errors or exceptional regimes  

## B00.CH04.P09 Relation to P/E/C: how E materialises as L and R pressure

### B00.CH04.P09.S01 E→L transmission: toll/lock-in raises essentials and claim layers  
### B00.CH04.P09.S02 C→L reduction: commons/public option lowers structural burdens  
### B00.CH04.P09.S03 P→R stabilisation: maintenance/capacity reduces shock sensitivity  
### B00.CH04.P09.S04 Diagnostics: decomposition of L into E-driven vs function-driven components  

## B00.CH04.P10 Relation to caps: W-MAX/I-MAX and the R/B floor

### B00.CH04.P10.S01 Caps as prevention of claim accumulation that structurally raises L  
### B00.CH04.P10.S02 Interaction with I-MAX: wage/income compression versus R/B target  
### B00.CH04.P10.S03 Reallocation path: cap skimming → C → L down → R/B up (conditions)  
### B00.CH04.P10.S04 Forbidden compensation: circumventing caps via price increases in essentials (L inflation)  

## B00.CH04.P11 Relation to ΔM: channel rules and macro stability via R/B

### B00.CH04.P11.S01 ΔM allocation must demonstrably improve (or stabilise) R/B profiles  
### B00.CH04.P11.S02 Forbidden channel: asset support that drives up L (rent/housing) and harms R/B  
### B00.CH04.P11.S03 Shock regime: temporary ΔM interventions with sunset and audit requirement  
### B00.CH04.P11.S04 Traceability: causal chain ΔM → C/essentials → L → R/B (evidence standard)  

## B00.CH04.P12 Measurement standards and minimum data layer

### B00.CH04.P12.S01 Minimum data for B: income components and periodicity  
### B00.CH04.P12.S02 Minimum data for T: effective burden, mandatory contributions, quasi-taxes  
### B00.CH04.P12.S03 Minimum data for L: essentials basket, contractual lock, regional price indices  
### B00.CH04.P12.S04 Uncertainty and conservatism: bands; fail-closed when inputs are non-auditable  

## B00.CH04.P13 Auditability and reproducibility

### B00.CH04.P13.S01 Reconciliation with national accounts and microdata (consistency requirements)  
### B00.CH04.P13.S02 Anti-gaming: classification audits, sampling, anomaly detection (L inflation, shadow fees)  
### B00.CH04.P13.S03 Publication requirement: methods, definition-set ID, changelog, revision policy  
### B00.CH04.P13.S04 Dispute protocol: objection/appeal, corrections, restatements without semantic break  

## B00.CH04.P14 Failure modes and hard stops

### B00.CH04.P14.S01 R/B-washing: inflating B, hiding L, relabelling T (detection rules)  
### B00.CH04.P14.S02 Goodhart: optimising on median R/B with tail sacrifice (forbidden)  
### B00.CH04.P14.S03 Black-box burden indices are non-conform (not reproducible)  
### B00.CH04.P14.S04 Fail-closed: when definition conflicts or data leaks occur, conformity is suspended until remediation  

# B00.CH05 Definition set III: caps on wealth/claims (W-MAX)

## B00.CH05.P01 Purpose, scope and normative status of W-MAX

### B00.CH05.P01.S01 W-MAX as order invariant: limiting claim-stacks and power  
### B00.CH05.P01.S02 Purpose: reducing E by putting a brake on claim accumulation and rent-seeking  
### B00.CH05.P01.S03 Scope: natural persons, households, vehicles, trusts, foundations, holdings  
### B00.CH05.P01.S04 Relation to I-MAX, P/E/C, R/B, ΔM and commons (linkages)  

## B00.CH05.P02 Canonical definition of W (wealth/claims/rights)

### B00.CH05.P02.S01 W as stock: net claim position on future flows and assets  
### B00.CH05.P02.S02 Components of W: financial assets, real assets, IP, concessions, control rights  
### B00.CH05.P02.S03 Economic reality over legal form (substance over form)  
### B00.CH05.P02.S04 Prohibition of “non-wealth” labels for economic equivalents  

## B00.CH05.P03 W-base: what counts in the cap base

### B00.CH05.P03.S01 Direct holdings: shares, bonds, cash, real estate, participations  
### B00.CH05.P03.S02 Indirect holdings: vehicles, funds, SPVs, trusts (look-through)  
### B00.CH05.P03.S03 Economic equivalents: options, forwards, synthetic exposures, warrants  
### B00.CH05.P03.S04 Control premium: rights to block/steer as cap-relevant attribute  

## B00.CH05.P04 Net and gross rule: debt and leverage

### B00.CH05.P04.S01 Net W: assets minus recognised liabilities (canonical liability definition)  
### B00.CH05.P04.S02 Leverage anti-avoidance: debt used to bypass the cap is requalified  
### B00.CH05.P04.S03 Collateral and rehypothecation: double claim layers and attribution  
### B00.CH05.P04.S04 Synthetic debt/structured notes: functional classification in W-base  

## B00.CH05.P05 Valuation and measurement rules (valuation discipline)

### B00.CH05.P05.S01 Valuation hierarchy: market price > book > model (with conservatism)  
### B00.CH05.P05.S02 Illiquid assets: haircut rules, bands, independent valuation  
### B00.CH05.P05.S03 IP/private companies: standard methods and prohibited manipulation patterns  
### B00.CH05.P05.S04 Point-in-time vs average: reference dates, smoothing, anti–window dressing  

## B00.CH05.P06 Ultimate Beneficial Control (UBC) and look-through consolidation

### B00.CH05.P06.S01 UBC definition: control, benefit and block as consolidation rules  
### B00.CH05.P06.S02 Graph consolidation: indirect chains, cross-holdings, nominee structures  
### B00.CH05.P06.S03 Family and household rules: joint control/benefit (canonical)  
### B00.CH05.P06.S04 Conflict rules: overlap, shared control, split-benefit situations  

## B00.CH05.P07 Cap parameterisation: W-MAX as boundary and regime

### B00.CH05.P07.S01 Definition of W-MAX: absolute limit vs threshold + skimming function (canonical choice)  
### B00.CH05.P07.S02 Parameters: unit, indexation, cohort rules (only via Kernspec procedure)  
### B00.CH05.P07.S03 Jurisdiction and residency rules: who is subject to which W-MAX regime  
### B00.CH05.P07.S04 Forbidden variation: no ad-hoc exceptions without canonical change procedure  

## B00.CH05.P08 Cap mechanics: what happens above W-MAX

### B00.CH05.P08.S01 Trigger: breach, detection moment, revaluation  
### B00.CH05.P08.S02 Remedy options: skimming, conversion, lockbox, reallocation to C (canonical)  
### B00.CH05.P08.S03 Choice space and duties: timing, order, burden of proof  
### B00.CH05.P08.S04 Fail-closed: uncertainty about W → temporary cap enforcement until clarification  

## B00.CH05.P09 Reallocation path: W-MAX → C (commons build-up/maintenance)

### B00.CH05.P09.S01 Admissibility: reallocation counts as C only with traceable ΔG output  
### B00.CH05.P09.S02 Forbidden reallocation: pseudo-commons, captured institutions, backflow to owner  
### B00.CH05.P09.S03 Destination rules: essentials/infra, maintenance-first, lifecycle obligation  
### B00.CH05.P09.S04 Audit trail: from cap event to project, costs, outputs and ΔG metrics  

## B00.CH05.P10 Exceptions and protected functions (tightly bounded)

### B00.CH05.P10.S01 Functional assets: primary residence/work tools as parameterisable carve-outs  
### B00.CH05.P10.S02 Pensions/collective reserves: treatment, consolidation and anti-privatisation  
### B00.CH05.P10.S03 Entrepreneurial tasks: genuine operational capex vs financial storage (boundary line)  
### B00.CH05.P10.S04 Ban on privilege exceptions: status/sector/legacy is no ground  

## B00.CH05.P11 Cross-border and migration: residency, exit and re-domiciliation

### B00.CH05.P11.S01 Residency tests: actual living/control centres and sham residency  
### B00.CH05.P11.S02 Mark-to-exit: treatment of unrealised gains at departure  
### B00.CH05.P11.S03 Treaty shopping and offshore vehicles: look-through and anti-mismatch rules  
### B00.CH05.P11.S04 Coherence with capital controls and payment rails (consistency requirement)  

## B00.CH05.P12 Anti-avoidance: typical patterns and requalification

### B00.CH05.P12.S01 Legal shifts: splitting, foundations, preferred rights, silent partnerships  
### B00.CH05.P12.S02 Financial shifts: securitisation, fee stacks, total return swaps, SPAC-like routes  
### B00.CH05.P12.S03 Technical shifts: tokenisation, pseudo-decentralisation, custody constructions  
### B00.CH05.P12.S04 Requalification and sanction rules: automatic reclassification + proportional penalties  

## B00.CH05.P13 Measurement and reporting duty (minimum disclosure)

### B00.CH05.P13.S01 Minimum dataset: asset list, exposures, control/benefit relations, valuation basis  
### B00.CH05.P13.S02 Publication level: aggregates + methodology; privacy minimalism where possible  
### B00.CH05.P13.S03 Frequency: periodic + event-driven (major transactions/structural changes)  
### B00.CH05.P13.S04 Mandatory attestation: independent audit, liability in case of misrepresentation  

## B00.CH05.P14 Enforcement and dispute regime

### B00.CH05.P14.S01 Enforcement chain: detection → assessment → cap event → remedy → audit  
### B00.CH05.P14.S02 Objection/appeal: contestability without delay-as-avoidance  
### B00.CH05.P14.S03 Proportionality and legal protection: procedural guarantees (canonical)  
### B00.CH05.P14.S04 Hard stops: refusal to disclose, black-box valuation, obstruction → non-conform status  

## B00.CH05.P15 Interaction with I-MAX (substitution between stock and flow)

### B00.CH05.P15.S01 Deferral as avoidance: conversion of income→wealth (detection)  
### B00.CH05.P15.S02 Dividend/buybacks/carried interest: canonical treatment in W and I  
### B00.CH05.P15.S03 Compensation via perks/benefits: requalification into I-base or W-equivalent  
### B00.CH05.P15.S04 Consistency requirement: no double exemption via stock/flow arbitrage  

## B00.CH05.P16 Interaction with R/B and macro stability

### B00.CH05.P16.S01 Target path: W caps lower claim pressure on essentials (L↓) and raise R/B  
### B00.CH05.P16.S02 Crisis regime: shock absorption without reintroducing claim privileges  
### B00.CH05.P16.S03 Forbidden compensation: price hikes/monopolies as reaction to caps  
### B00.CH05.P16.S04 Monitoring: indicators for avoidance, concentration and E regrowth  

## B00.CH05.P17 Failure modes and hard stops

### B00.CH05.P17.S01 W-MAX-washing: “cap exists” but base is leaky (equivalents excluded)  
### B00.CH05.P17.S02 Gaming: valuation manipulation, window dressing, dispersion over nominees  
### B00.CH05.P17.S03 Capture risk: exceptions, discretionary deals, selective enforcement  
### B00.CH05.P17.S04 Fail-closed: structural audit failure suspends compatibility claim  

# B00.CH06 Definition set IV: caps on income/flows (I-MAX)

## B00.CH06.P01 Purpose, scope and normative status of I-MAX

### B00.CH06.P01.S01 I-MAX as order invariant: limiting top income and flow accumulation  
### B00.CH06.P01.S02 Purpose: brake on E-driven flow extraction and build-up of W via deferral  
### B00.CH06.P01.S03 Scope: wages, bonuses, profit distributions, interest, rent, royalties, fees, carried interest  
### B00.CH06.P01.S04 Relation to W-MAX, P/E/C, R/B and ΔM (linkages and substitution risks)  

## B00.CH06.P02 Canonical definition of I (income/flow)

### B00.CH06.P02.S01 I as flow per time period t (year/month) with standard resolutions  
### B00.CH06.P02.S02 Cash vs in-kind: canonical valuation rules  
### B00.CH06.P02.S03 Realisation and attribution moment: accrual vs cash (canonical choice)  
### B00.CH06.P02.S04 Consolidation: income across entities/vehicles (substance over form)  

## B00.CH06.P03 I-base: what counts in the cap base

### B00.CH06.P03.S01 Labour income: wages, bonuses, equity comp, options (at fair value)  
### B00.CH06.P03.S02 Capital income: dividends, interest, rent, capital gains (canonical treatment)  
### B00.CH06.P03.S03 Entrepreneurial income: profit distributions, management fees, profit shares  
### B00.CH06.P03.S04 Quasi-income: perks, expense accounts, benefits, deferred comp (requalification)  

## B00.CH06.P04 Realisation and deferral: anti-avoidance in time

### B00.CH06.P04.S01 Deferred compensation: attribution to earn-year (look-back)  
### B00.CH06.P04.S02 Capital gains timing: anti–lock-in effects, mark-to-market options (canonical)  
### B00.CH06.P04.S03 Carried interest and performance fees: canonical classification (labour vs capital)  
### B00.CH06.P04.S04 Income smoothing: rules against artificial spikes/dips and “bonus banks”  

## B00.CH06.P05 Netting and costs: what may be deducted

### B00.CH06.P05.S01 Gross I as starting point; limited deductibility for genuine production inputs  
### B00.CH06.P05.S02 Prohibited deductions: sham costs, internal fees, IP-royalty circles  
### B00.CH06.P05.S03 Self-employed/firms: separation between P-costs and E-fee stacks  
### B00.CH06.P05.S04 Anti-mismatch: cross-border cost shifting and transfer pricing  

## B00.CH06.P06 I-MAX parameterisation and cap regime

### B00.CH06.P06.S01 Definition of I-MAX: absolute cap vs cap + skimming function (canonical choice)  
### B00.CH06.P06.S02 Parameters: indexation, cohort/sector variation (only via Kernspec procedure)  
### B00.CH06.P06.S03 Reference anchors: median wage ratio, R/B target path, productivity bands  
### B00.CH06.P06.S04 Forbidden variation: exceptions based on status, lobbying or ad-hoc deals  

## B00.CH06.P07 Cap mechanics: what happens above I-MAX

### B00.CH06.P07.S01 Trigger: periodic breaches and event-driven triggers  
### B00.CH06.P07.S02 Remedy options: skimming, conversion to C, mandatory reinvestment in commons (canonical)  
### B00.CH06.P07.S03 Timing and burden of proof: who demonstrates that a component is P and not E  
### B00.CH06.P07.S04 Fail-closed: unclear income components are included until clarified  

## B00.CH06.P08 Interaction with wage formation and working time (link to lived world)

### B00.CH06.P08.S01 Reservation condition: R/B floor changes bargaining space  
### B00.CH06.P08.S02 Wage compression: effect on labour allocation, “bullshit job” incentives, scarcity  
### B00.CH06.P08.S03 Time as order variable: hours reduction and maintenance capacity (linkage)  
### B00.CH06.P08.S04 Forbidden compensation: avoidance via non-wage perks or price hikes in essentials  

## B00.CH06.P09 Interaction with W-MAX: stock/flow arbitrage

### B00.CH06.P09.S01 Conversion I→W via buybacks, dividends, carry, equity grants (detection)  
### B00.CH06.P09.S02 Conversion W→I via management fees, royalties, rent extraction (detection)  
### B00.CH06.P09.S03 Consistency: double exemption or double counting (conflict rules)  
### B00.CH06.P09.S04 Joint enforcement: combined audits and cross-checks (UBC graph)  

## B00.CH06.P10 Interaction with P/E/C: E-income versus P-income

### B00.CH06.P10.S01 E-income: toll/lock-in fees, monopoly rents, platform take rates, fee stacks  
### B00.CH06.P10.S02 P-income: function-linked remuneration and maintenance-linked output  
### B00.CH06.P10.S03 Splitting mixed roles: executive comp, founder comp, IP royalty + labour  
### B00.CH06.P10.S04 Evidence standard: classification requires auditable decomposition (no black boxes)  

## B00.CH06.P11 Cross-border income and residency

### B00.CH06.P11.S01 Residency and source rules: where income counts  
### B00.CH06.P11.S02 Re-domiciliation, treaty shopping and IP boxes: anti-mismatch and requalification  
### B00.CH06.P11.S03 Remote work and digital services: source determination and platform components  
### B00.CH06.P11.S04 Coherence with capital controls/payment rails (consistency requirement)  

## B00.CH06.P12 Reporting and publication duty (minimum disclosure)

### B00.CH06.P12.S01 Minimum dataset: income components, valuation, deferral schedules, entities  
### B00.CH06.P12.S02 Public statistics: distributions, top shares, under-α correlations with R/B  
### B00.CH06.P12.S03 Frequency: periodic + event-driven (bonus cycles, equity vesting)  
### B00.CH06.P12.S04 Independent attestation and liability in case of misrepresentation  

## B00.CH06.P13 Enforcement and dispute regime

### B00.CH06.P13.S01 Enforcement chain: detection → assessment → cap event → remedy → audit  
### B00.CH06.P13.S02 Objection/appeal: contestability without delay-as-avoidance  
### B00.CH06.P13.S03 Proportionality: procedural guarantees, but no “discretionary deals”  
### B00.CH06.P13.S04 Hard stops: obstruction, non-disclosure, black-box compensation → non-conform status  

## B00.CH06.P14 Failure modes and hard stops

### B00.CH06.P14.S01 I-MAX-washing: cap exists but major components are excluded  
### B00.CH06.P14.S02 Gaming: deferral, relabelling, splitting across family/nominees/entities  
### B00.CH06.P14.S03 Capture: carve-outs, special regimes, sector privileges  
### B00.CH06.P14.S04 Fail-closed: structural audit failure suspends compatibility claim  

# B00.CH07 Definition set V: commons and maintenance (ΔG, access, boundary rules)

## B00.CH07.P01 Purpose, scope and normative status of Definition set V

### B00.CH07.P01.S01 Commons as order invariant: exit options, discipline of power, reduction of L  
### B00.CH07.P01.S02 Commons is not an ownership label but an access/maintenance regime  
### B00.CH07.P01.S03 Scope: essentials, networks, natural monopolies, knowledge/data, digital rails  
### B00.CH07.P01.S04 Relation to P/E/C, R/B, W/I caps and ΔM (linkages)  

## B00.CH07.P02 Canonical definition of commons (order properties)

### B00.CH07.P02.S01 Access: non-discrimination, baseline rights, public option logic  
### B00.CH07.P02.S02 Boundary rules: who may do what, under what conditions, with which duties  
### B00.CH07.P02.S03 Maintenance duty: lifecycle, recoverability, service levels, resiliency  
### B00.CH07.P02.S04 Contestability: objection/appeal, auditability, transparency as constitutive  

## B00.CH07.P03 ΔG as state variable (capacity/quality/continuity)

### B00.CH07.P03.S01 Definition: ΔG(t) as change in commons capacity/quality per period  
### B00.CH07.P03.S02 Components: capex build-out, opex maintenance, replacement, innovation as maintenance  
### B00.CH07.P03.S03 Minimum ΔG: lower bound for continuity (maintenance-first invariant)  
### B00.CH07.P03.S04 Relation to R/B: ΔG affects L (essentials) and shock resilience  

## B00.CH07.P04 Commons categories and scope rules

### B00.CH07.P04.S01 Essentials commons: housing, energy, water, healthcare, education, mobility, basic connectivity  
### B00.CH07.P04.S02 Network commons: payment rails, logistics, identity/credentialing, interoperability layers  
### B00.CH07.P04.S03 Knowledge and information commons: standards, data dictionaries, public models/assumptions  
### B00.CH07.P04.S04 Digital commons: open APIs, protocols, public options alongside platforms  

## B00.CH07.P05 Access as canonical design: baseline and differentiation

### B00.CH07.P05.S01 Baseline access: minimum service/volume as a right (parameterisable)  
### B00.CH07.P05.S02 Differentiation above baseline: allowed if non-extractive and transparent  
### B00.CH07.P05.S03 Price and tariff rules: cost coverage + bounded margin; prohibition of tolls  
### B00.CH07.P05.S04 No-exit-friction: limiting lock-in and contractual grip in commons domains  

## B00.CH07.P06 Boundary rules: rights, duties and enforcement

### B00.CH07.P06.S01 User duties: fair use, maintenance contribution, abuse prevention  
### B00.CH07.P06.S02 Operator duties: service levels, transparency, non-discrimination, recoverability  
### B00.CH07.P06.S03 Suppliers/contractors: open standards, auditability, vendor lock-in prohibited  
### B00.CH07.P06.S04 Sanctions: proportional, procedurally reviewable, no discretionary arbitrariness  

## B00.CH07.P07 Governance minimum (institutional)

### B00.CH07.P07.S01 Role model: owner/mandate giver, operator, executor, auditor, user  
### B00.CH07.P07.S02 Powers: allocation, prioritisation, emergency mode, contracting (bounded)  
### B00.CH07.P07.S03 Liability: duty of care, negligence, conflict-of-interest rules  
### B00.CH07.P07.S04 Anti-capture: term limits, transparency, procurement rules, stakeholder checks  

## B00.CH07.P08 Public option, hybrid layers and interoperability

### B00.CH07.P08.S01 Public option as disciplining exit: minimum viable alternative  
### B00.CH07.P08.S02 Hybrid layers: commons core with competitive edges (allowed)  
### B00.CH07.P08.S03 Interoperability: open standards, portability, caps on switching costs  
### B00.CH07.P08.S04 Prohibition of pseudo-commons: apparent openness with de facto lock-in or tolling  

## B00.CH07.P09 Financing and allocation (link to ΔM and caps)

### B00.CH07.P09.S01 Funding sources: C-flows, cap reallocation, tariff revenues, public funds  
### B00.CH07.P09.S02 Maintenance-first: opex/maintenance before expansion or prestige projects  
### B00.CH07.P09.S03 Allocation rules: priority on reducing L and improving R/B  
### B00.CH07.P09.S04 Prohibited funding: dependence on extractive flows or surveillance rents  

## B00.CH07.P10 Measurement and audit standards for commons and ΔG

### B00.CH07.P10.S01 ΔG metric set: capacity, quality, uptime, recoverability, cost per unit  
### B00.CH07.P10.S02 Access metric set: coverage, waiting times, price/baseline, non-discrimination  
### B00.CH07.P10.S03 Audit trail: contracts, procurement, performance, incidents, change logs  
### B00.CH07.P10.S04 Reproducibility: methods, definition-set ID, versioning of metrics  

## B00.CH07.P11 Edge cases and boundary rules

### B00.CH07.P11.S01 Natural monopolies: tariff regime and anti-private tolling  
### B00.CH07.P11.S02 Data/AI commons: privacy minimalism, model transparency, access governance  
### B00.CH07.P11.S03 Crisis regimes: emergency access and rationing with sunset/rollback  
### B00.CH07.P11.S04 International commons: cross-border interoperability without governance capture  

## B00.CH07.P12 Failure modes and hard stops

### B00.CH07.P12.S01 Commons-washing: label without access/maintenance/contestability  
### B00.CH07.P12.S02 Capture: operator becomes toll gate (E in commons clothing)  
### B00.CH07.P12.S03 Vendor lock-in: closed stacks in public infra (non-conform)  
### B00.CH07.P12.S04 Fail-closed: non-measurability/non-auditability → suspension of commons status  

# B00.CH08 Definition set VI: monetary space as allocation interface (ΔM; channel rules; prohibited channels)

## B00.CH08.P01 Purpose, scope and normative status of Definition set VI

### B00.CH08.P01.S01 ΔM as allocation interface: not “more/less money” but channel discipline  
### B00.CH08.P01.S02 Purpose: R/B stabilisation and commons build-out without asset and claim support  
### B00.CH08.P01.S03 Scope: central bank, treasury, public credit channels, banking system, payment rails  
### B00.CH08.P01.S04 Relation to P/E/C, caps and commons (linkages and dependencies)  

## B00.CH08.P02 Canonical definition of ΔM (monetary space)

### B00.CH08.P02.S01 ΔM as change in monetary capacity per period t (stock/flow convention)  
### B00.CH08.P02.S02 Sources of ΔM: credit creation, balance sheet expansion, guarantees, fiscal injections (canonically delimited)  
### B00.CH08.P02.S03 Measurement framework: monetary aggregates versus functional capacity (canonical choice)  
### B00.CH08.P02.S04 Traceability: every ΔM must be traceable to channel and destination  

## B00.CH08.P03 Channel object model and classification of channels

### B00.CH08.P03.S01 Channel object: {source, intermediary, instrument, destination, conditions, audit log}  
### B00.CH08.P03.S02 Channel categories: commons capex, maintenance/opex, floor stabilisation, crisis buffer  
### B00.CH08.P03.S03 Intermediaries: public banks, commercial banks, funds, programmes (role rules)  
### B00.CH08.P03.S04 Channel frictions: leakage, capture, moral hazard, and how they are measured  

## B00.CH08.P04 Permitted channels (allowed) and conditions

### B00.CH08.P04.S01 Commons build-out: investments with ΔG metrics and lifecycle duties  
### B00.CH08.P04.S02 Maintenance-first: financing of opex/maintenance where ΔG would otherwise degrade  
### B00.CH08.P04.S03 Floor stabilisation: improving R/B profiles (reducing under-α share) via direct instruments  
### B00.CH08.P04.S04 Productive credit: capex for P/commons, no accumulation of claim stacks  

## B00.CH08.P05 Prohibited channels: canonical definition and detection rules

### B00.CH08.P05.S01 Asset support: programmes that support asset prices or reinforce collateral dominance  
### B00.CH08.P05.S02 Claim support: buybacks, fee stacks, rentier cashflows, “stabilisation” of E-structures  
### B00.CH08.P05.S03 Untraced intermediaries: black-box funds, opaque SPVs, off-balance conduits  
### B00.CH08.P05.S04 Surveillance rent: financing that becomes dependent on data extraction/control as toll  

## B00.CH08.P06 Channeling rules and priority (allocation hierarchy)

### B00.CH08.P06.S01 Priority 1: maintenance and continuity of essentials (ΔG lower bound)  
### B00.CH08.P06.S02 Priority 2: reduction of L through public option/commons in essentials  
### B00.CH08.P06.S03 Priority 3: productive capacity (P) that durably strengthens R/B  
### B00.CH08.P06.S04 Prohibited priority: “calming markets” as de facto asset and claim support  

## B00.CH08.P07 Embedding in existing banking system and credit mechanism

### B00.CH08.P07.S01 Role of commercial banks: credit under channel rules and audit requirements  
### B00.CH08.P07.S02 Public credit infrastructure: governance, mandate, risk management  
### B00.CH08.P07.S03 Payment rails governance: choke points, compliance, and anti-leakage  
### B00.CH08.P07.S04 Macroprudential coupling: rules against collateral and leverage cycles  

## B00.CH08.P08 Crisis regime: emergency ΔM without semantic erosion

### B00.CH08.P08.S01 Trigger criteria: shock definitions, measurable indicators, decision procedures  
### B00.CH08.P08.S02 Temporariness: sunsets, caps on size/duration, rollback plan  
### B00.CH08.P08.S03 Prohibited emergency route: crisis as pretext for permanent asset support  
### B00.CH08.P08.S04 Transparency: publication of instruments, beneficiaries, conditions, audits  

## B00.CH08.P09 Relational tests: ΔM and P/E/C classification

### B00.CH08.P09.S01 ΔM→P: credit that yields productive output/maintenance (measurable)  
### B00.CH08.P09.S02 ΔM→C: allocation that yields commons status and ΔG output (traceable)  
### B00.CH08.P09.S03 ΔM→E (prohibited): allocation that consolidates toll/lock-in/claim layers  
### B00.CH08.P09.S04 Mixed programmes: decomposition, redesign, or declaration as non-conform  

## B00.CH08.P10 Measurement and audit standards (monetary)

### B00.CH08.P10.S01 Minimum dataset: instrument, channel, destination, beneficiary, conditions  
### B00.CH08.P10.S02 Outcome metrics: R/B profiles, L indices, ΔG, P output, E indicators  
### B00.CH08.P10.S03 Audit trail: end-to-end linkage from decision → allocation → outcome  
### B00.CH08.P10.S04 Uncertainty and attribution: causal claims require triangulation and counterfactuals  

## B00.CH08.P11 Anti-avoidance: leakage and shadow channels

### B00.CH08.P11.S01 Shadow banking: SPVs, securitisation, synthetic exposures as avoidance routes  
### B00.CH08.P11.S02 Cross-border leakage: carry trades, offshore funding, crypto rails  
### B00.CH08.P11.S03 Instrument innovation: new labels with the same effect (functional reclassification)  
### B00.CH08.P11.S04 Reclassification + sanctions: automatic reclassification to prohibited channel where appropriate  

## B00.CH08.P12 Compatibility with caps and commons (integration tests)

### B00.CH08.P12.S01 No ΔM that undermines W/I caps via asset inflation or deferral  
### B00.CH08.P12.S02 No ΔM that pushes commons into capture (vendor lock-in, private tolling)  
### B00.CH08.P12.S03 Consistency with R/B: channel must reduce or stabilise under-α share  
### B00.CH08.P12.S04 Integration check: “channel plan” as mandatory component of any OBA claim  

## B00.CH08.P13 Failure modes and hard stops

### B00.CH08.P13.S01 ΔM-washing: “commons” label on programmes that are in fact asset support  
### B00.CH08.P13.S02 Moral hazard: private risks socialised without caps/anti-E conditions  
### B00.CH08.P13.S03 Black-box allocation: unknown beneficiaries/conditions = non-conform  
### B00.CH08.P13.S04 Fail-closed: if untraceable or with prohibited leakage, the channel is shut down  

# B00.CH09 Control, benefit and block tests (ultimate control; look-through; consolidation)

## B00.CH09.P01 Purpose, scope and normative status of control/benefit/block tests

### B00.CH09.P01.S01 Tests as canonical basis for UBC (ultimate beneficial control) and consolidation  
### B00.CH09.P01.S02 Purpose: preventing sham structures, nominees and “legal fog”  
### B00.CH09.P01.S03 Scope: wealth (W), income (I), ΔM channels, commons governance, platforms  
### B00.CH09.P01.S04 Relation to caps, P/E/C, R/B, auditing and anti-avoidance  

## B00.CH09.P02 Control test: definition and categories

### B00.CH09.P02.S01 Formal control: voting rights, board appointment, contractual powers  
### B00.CH09.P02.S02 De facto control: actual steering via dependencies, information, operational choke points  
### B00.CH09.P02.S03 Negative control: vetoes, blocking rights, protective provisions (where relevant)  
### B00.CH09.P02.S04 Multi-layer control: cascades across holdings, trusts, funds and platform stacks  

## B00.CH09.P03 Benefit test: definition and categories

### B00.CH09.P03.S01 Cashflow benefit: dividends, interest, rent, fees, distributions, royalties  
### B00.CH09.P03.S02 Upside benefit: value appreciation, performance shares, options, carried interest  
### B00.CH09.P03.S03 Risk-transfer benefit: asymmetric downside, guarantees, limited recourse, bailouts  
### B00.CH09.P03.S04 In-kind benefit: perks, exclusive access, non-cash privileges (reclassification)  

## B00.CH09.P04 Block test: definition and categories

### B00.CH09.P04.S01 Veto/exit-friction: ability to block choices without having positive control  
### B00.CH09.P04.S02 Choke-point power: infrastructure, API, payment-rail, licence or supply-chain blockades  
### B00.CH09.P04.S03 Contractual lock-in: exclusivity, non-competes, MFN, termination penalties  
### B00.CH09.P04.S04 Information and platform power: ranking/curation/algorithmic exclusion as block power  

## B00.CH09.P05 UBC synthesis: composite decision rules

### B00.CH09.P05.S01 UBC criterion: combination of control + benefit + block (canonical threshold)  
### B00.CH09.P05.S02 Priority rules in case of conflict: control prevails unless benefit/block dominance (canonical)  
### B00.CH09.P05.S03 Shared control: joint arrangements, pacts, syndicates, “acting in concert”  
### B00.CH09.P05.S04 Family/household consolidation: shared control/benefit as default, with exception rules  

## B00.CH09.P06 Look-through rules: indirect structures and nominees

### B00.CH09.P06.S01 Trusts/foundations: settlor, trustee, protector, beneficiaries (attribution)  
### B00.CH09.P06.S02 Funds/GP–LP: management control, carried interest, side letters  
### B00.CH09.P06.S03 Custody/nominee: legal holder ≠ economic owner (attribution)  
### B00.CH09.P06.S04 Layering and cross-holdings: graph resolution and cycles (conflict rules)  

## B00.CH09.P07 Consolidation rules: when positions are combined

### B00.CH09.P07.S01 Consolidation for W: assets, exposures, control premia, off-balance claims  
### B00.CH09.P07.S02 Consolidation for I: flow attribution, deferral, pass-through vehicles  
### B00.CH09.P07.S03 Consolidation for ΔM: beneficiaries behind intermediaries and programmes  
### B00.CH09.P07.S04 Consolidation for commons: governance control, procurement, vendor lock-in routes  

## B00.CH09.P08 Standard of proof and documentation duty

### B00.CH09.P08.S01 Minimum documentation: shareholder registers, contracts, side letters, governance docs  
### B00.CH09.P08.S02 Burden of proof: in case of uncertainty, count towards consolidation (conservatism)  
### B00.CH09.P08.S03 Audit trail: reproducible graph evaluation and decision logs  
### B00.CH09.P08.S04 Privacy minimalism: only data needed for control/benefit/block (link to Book 4)  

## B00.CH09.P09 Edge cases: modern structures

### B00.CH09.P09.S01 Dual-class shares and control without cashflow  
### B00.CH09.P09.S02 Derivatives and synthetic exposures: TRS, swaps, options (benefit/risk)  
### B00.CH09.P09.S03 Tokenisation/DAO-like constructs: actual control and governance capture  
### B00.CH09.P09.S04 Platform ecosystems: API terms, ranking, payment gating as control/block  

## B00.CH09.P10 Detection: red flags and anomalies

### B00.CH09.P10.S01 Dispersion across entities without economic rationale (nominee patterns)  
### B00.CH09.P10.S02 Fee stacks and circular flows as benefit masking  
### B00.CH09.P10.S03 Inconsistency between governance docs and operational reality (de facto control)  
### B00.CH09.P10.S04 Cross-border mismatch: treaty shopping, IP boxes, re-domiciliation signals  

## B00.CH09.P11 Enforcement and dispute regime

### B00.CH09.P11.S01 Mandatory registration of control/benefit/block relationships (minimum disclosure)  
### B00.CH09.P11.S02 Objection/appeal: contestability with time-bounded procedures  
### B00.CH09.P11.S03 Sanctions: misrepresentation, non-disclosure, obstruction, reclassification + fines  
### B00.CH09.P11.S04 Hard stops: black-box ownership, refusal of disclosure → non-conform status  

## B00.CH09.P12 Failure modes and hard stops

### B00.CH09.P12.S01 Pseudo-UBO compliance: formally correct but de facto control hidden  
### B00.CH09.P12.S02 Regulatory arbitrage: structures designed to avoid thresholds  
### B00.CH09.P12.S03 Capture: exceptions for “strategic” players or sectors  
### B00.CH09.P12.S04 Fail-closed: irresolvable ownership opacity → consolidate and enforce  

# B00.CH10 Anti-avoidance: reclassification, shift taxonomy and detection rules

## B00.CH10.P01 Purpose, scope and normative status of anti-avoidance

### B00.CH10.P01.S01 Anti-avoidance as order invariant: “form must not trump function”  
### B00.CH10.P01.S02 Purpose: making caps, P/E/C, ΔM channel rules and commons status effective  
### B00.CH10.P01.S03 Scope: legal, financial, technical, international, institutional  
### B00.CH10.P01.S04 Relation to evidence standards, control/benefit/block and compatibility  

## B00.CH10.P02 Canonical shift taxonomy (categories)

### B00.CH10.P02.S01 Legal shifts: relabelling to services/licences/consultancy/franchise  
### B00.CH10.P02.S02 Financial shifts: securitisation, fee stacks, synthetic exposures, shadow banking  
### B00.CH10.P02.S03 Technical shifts: bundling, dark patterns, API locks, data extraction as toll  
### B00.CH10.P02.S04 International shifts: transfer pricing, IP boxes, re-domiciliation, treaty shopping  

## B00.CH10.P03 Reclassification principle (substance over form)

### B00.CH10.P03.S01 Functional equivalence: same economic effect → same classification  
### B00.CH10.P03.S02 Default conservatism: under uncertainty, classify towards E / include in cap base  
### B00.CH10.P03.S03 Anti-fragmentation: splitting flows/entities without function is recombined  
### B00.CH10.P03.S04 Anti-opaque: black-box structures lose privileges and are treated as non-conform  

## B00.CH10.P04 Detection rules: red flags and anomalies (statistical + rule-based)

### B00.CH10.P04.S01 Margin extremes: deviation from cost bands and sector benchmarks  
### B00.CH10.P04.S02 Fee stacks: multiple layers of fees on the same function (cascade patterns)  
### B00.CH10.P04.S03 Concentration/lock-in metrics: switching costs, churn friction, API dependencies  
### B00.CH10.P04.S04 Flow-graph anomalies: circular flows, round-tripping, mismatch between P output and cashflows  

## B00.CH10.P05 Legal shifts: typical patterns and counter-rules

### B00.CH10.P05.S01 Reclassification of sale to licence/subscription with lock-in toll  
### B00.CH10.P05.S02 Franchise/royalty structures as toll-gate  
### B00.CH10.P05.S03 Consultancy/management fees between related parties (profit stripping)  
### B00.CH10.P05.S04 Contractual lock-in (MFN, exclusivity, termination penalties) as E indicator  

## B00.CH10.P06 Financial shifts: typical patterns and counter-rules

### B00.CH10.P06.S01 Securitisation and fee extraction: originator→servicer fee stacks  
### B00.CH10.P06.S02 Synthetic exposures: TRS/swaps used to avoid ownership/caps  
### B00.CH10.P06.S03 Shadow banking: off-balance conduits, repo chains, rehypothecation  
### B00.CH10.P06.S04 Collateral–asset inflation: leverage cycles that undermine L and R/B  

## B00.CH10.P07 Technical shifts: digital avoidance and counter-rules

### B00.CH10.P07.S01 Bundling and tying: opaque price discrimination as toll  
### B00.CH10.P07.S02 Dark patterns: deception as hidden price (E)  
### B00.CH10.P07.S03 API locks and data portability barriers: block power as E driver  
### B00.CH10.P07.S04 Tokenisation/crypto rails: pseudo-decentralisation as avoidance vector  

## B00.CH10.P08 International shifts: cross-border avoidance and counter-rules

### B00.CH10.P08.S01 Transfer pricing: IP royalty and management fee routing  
### B00.CH10.P08.S02 IP boxes and treaty shopping: mismatch between value creation and profit location  
### B00.CH10.P08.S03 Re-domiciliation and inversions: residence and control centres versus paper seat  
### B00.CH10.P08.S04 Offshore vehicles and nominees: look-through and UBC consolidation  

## B00.CH10.P09 Automatic reclassification: triggers and procedures

### B00.CH10.P09.S01 Trigger classes: thresholds, anomalies, structural patterns, audit findings  
### B00.CH10.P09.S02 Reclassification outcome: (i) relabel P→E, (ii) inclusion in W/I base, (iii) channel ban  
### B00.CH10.P09.S03 Time-bounded dispute window: objection without “delay-as-avoidance”  
### B00.CH10.P09.S04 Publication: methods, triggers, error margins (without leaking sensitive details)  

## B00.CH10.P10 Sanctions and remedies (proportional but firm)

### B00.CH10.P10.S01 Financial sanctions: fines, clawback, interest, multipliers for recidivism  
### B00.CH10.P10.S02 Structural remedies: contract adjustment, unbundling, interoperability mandates  
### B00.CH10.P10.S03 Discretion minimisation: sanction tables and mandatory justification  
### B00.CH10.P10.S04 Hard stops: in case of obstruction/black-box → immediate non-conform status  

## B00.CH10.P11 Monitoring and early-warning indicators (order hygiene)

### B00.CH10.P11.S01 E-regrowth indicators: rising fee stacks, take rates, essential price indices  
### B00.CH10.P11.S02 Cap erosion indicators: growth of offshore holdings, derivatives exposures, deferral  
### B00.CH10.P11.S03 Commons erosion indicators: vendor lock-in, maintenance backlog, declining access  
### B00.CH10.P11.S04 ΔM leakage indicators: asset inflation, collateral dominance, shadow credit growth  

## B00.CH10.P12 Failure modes and hard stops

### B00.CH10.P12.S01 Rule overload: too many discretionary exceptions → capture risk  
### B00.CH10.P12.S02 Goodhart: detection KPIs become gameable → triangulation mandatory  
### B00.CH10.P12.S03 Political sabotage: selective enforcement → compatibility breach  
### B00.CH10.P12.S04 Fail-closed: when detection capacity is lost, scope is scaled back to auditable level  

# B00.CH11 Compatibility and forks: parameter space, procedure, conflict rules and name usage

## B00.CH11.P01 Purpose, scope and normative status of compatibility

### B00.CH11.P01.S01 Compatibility as a formal claim: OBA is a class with testable requirements  
### B00.CH11.P01.S02 Purpose: preventing semantic drift, OBA-washing and “incompatible interpretations”  
### B00.CH11.P01.S03 Scope: definitions, parameters, implementations, jurisdictions, sector canvases  
### B00.CH11.P01.S04 Relation to Kernel Spec, Codex, Books 1–4 and public communication  

## B00.CH11.P02 Compatibility layers (hierarchy of sources)

### B00.CH11.P02.S01 Source hierarchy: Kernel Spec > Standards/Codex > books > commentary/marketing  
### B00.CH11.P02.S02 Canonical reference: definition-set ID and version as required part of every claim  
### B00.CH11.P02.S03 Interpretation rule: refer instead of redefining (anti-drift)  
### B00.CH11.P02.S04 Fail-closed: in case of source conflict, the strictest canonical interpretation applies  

## B00.CH11.P03 Invariants versus parameters (what may vary)

### B00.CH11.P03.S01 Invariants: P/E/C function, R/B structure, cap principles, commons order properties, ΔM forbidden channels  
### B00.CH11.P03.S02 Parameters: α, cap levels, baseline access volumes, indexations, time resolutions (within bounds)  
### B00.CH11.P03.S03 Forbidden variation: exceptions that hollow out invariants (semantic break)  
### B00.CH11.P03.S04 Parameter rules: change procedure, evidence, impact analysis, sunsets  

## B00.CH11.P04 Compatibility tests (formal checks)

### B00.CH11.P04.S01 Definition-set closure: all used terms traceable back to Kernel Spec  
### B00.CH11.P04.S02 Auditability check: measurability, reproducibility, public methods (minimum requirement)  
### B00.CH11.P04.S03 Anti-avoidance check: shifts covered; reclassification present; leak tests  
### B00.CH11.P04.S04 Outcome check: R/B profiles and E indicators move consistently with claims  

## B00.CH11.P05 Compatibility labels and status levels (name usage)

### B00.CH11.P05.S01 “OBA-conform”: meets all invariants + audit requirements  
### B00.CH11.P05.S02 “OBA-compatible”: meets core invariants but lacks optional modules (canonically defined)  
### B00.CH11.P05.S03 “OBA-inspired”: refers to ideas without compatibility claim (permitted label)  
### B00.CH11.P05.S04 “Non-conform / Fork”: breaks invariants or auditability; restricted name usage  

## B00.CH11.P06 Fork protocol: when and how forks arise

### B00.CH11.P06.S01 Fork triggers: change of invariant, redefinition, hidden exceptions, black-box governance  
### B00.CH11.P06.S02 Fork documentation: explicit changelog, rationale, impact on invariants  
### B00.CH11.P06.S03 Fork naming: mandatory distinction, no “OBA” without compatibility label  
### B00.CH11.P06.S04 Interoperability: mapping between forks only via explicit bridging docs  

## B00.CH11.P07 Conflict rules for definitions and implementations

### B00.CH11.P07.S01 Definition conflict: canonical resolution procedure (Kernel Spec governance)  
### B00.CH11.P07.S02 Implementation conflict: test outcome prevails over intention or rhetoric  
### B00.CH11.P07.S03 Parameter conflict: outside allowed space = non-conform until remedied  
### B00.CH11.P07.S04 Jurisdiction conflict: cross-border mismatches and priority rules  

## B00.CH11.P08 Compatibility for sector canvases and local variants

### B00.CH11.P08.S01 Sector canvas as derivative: may only fill parameters, cannot change definitions  
### B00.CH11.P08.S02 Local institutional choice: allowed within auditability and invariant rails  
### B00.CH11.P08.S03 Minimum publication per sector: bottlenecks, E sources, commons options, cap compatibility, R/B effect  
### B00.CH11.P08.S04 Anti-avoidance: standard check on legal/technical/international shifts per sector  

## B00.CH11.P09 Compatibility and communication (anti-washing)

### B00.CH11.P09.S01 Ban on “compatibility by branding”: label requires evidence and publication  
### B00.CH11.P09.S02 Misrepresentation and duty to correct: rectification in case of incorrect OBA claim  
### B00.CH11.P09.S03 Audit on the gatekeeper: external audits on compatibility declarations  
### B00.CH11.P09.S04 Transparency: public register of conformity, exceptions and forks  

## B00.CH11.P10 Enforcement of name usage and status

### B00.CH11.P10.S01 Name right: use of “OBA” tied to compatibility status and evidence  
### B00.CH11.P10.S02 Sanctions: ban, fines, public downgrade, loss of access to commons programmes  
### B00.CH11.P10.S03 Dispute protocol: objection/appeal with time-bounded procedures  
### B00.CH11.P10.S04 Hard stops: for black-box, non-disclosure or proven washing → immediate fork status  

## B00.CH11.P11 Failure modes and hard stops

### B00.CH11.P11.S01 Compatibility capture: stacking exceptions until the core is empty  
### B00.CH11.P11.S02 Goodhart on labels: “OBA-compatible” abused as marketing (detection)  
### B00.CH11.P11.S03 Semantic drift via document sprawl: shadow canons (forbidden)  
### B00.CH11.P11.S04 Fail-closed: when status is uncertain, non-conform applies until evidence is provided  

# B00.CH12 Evidence and measurement standards: observability, auditability, reproducibility, uncertainty

## B00.CH12.P01 Purpose, scope and normative status of evidence and measurement standards

### B00.CH12.P01.S01 Standards as order invariant: without evidence there is no compatibility claim  
### B00.CH12.P01.S02 Purpose: preventing black-box governance, measurement-washing and semantic drift  
### B00.CH12.P01.S03 Scope: P/E/C, R/B, W/I caps, ΔM channels, commons status, anti-avoidance  
### B00.CH12.P01.S04 Relation to Kernel Spec, Codex, governance and dispute protocol  

## B00.CH12.P02 Observability: what must be measurable (minimum observables)

### B00.CH12.P02.S01 Core observables: flows (P/E/C), B,T,L,R, cap bases, channel destinations, commons ΔG  
### B00.CH12.P02.S02 Verifiability: inputs, transformations and outputs must be traceable  
### B00.CH12.P02.S03 Distribution observables: cohort profiles (R/B tail, under-α share) as minimum  
### B00.CH12.P02.S04 Prohibited non-observability: “proprietary metrics” as replacement for core observables  

## B00.CH12.P03 Measurement methods: definitions, procedures and minimum metadata

### B00.CH12.P03.S01 Method registration: definition-set ID, version, measurement procedure, source data, sampling  
### B00.CH12.P03.S02 Data minimalism: only data needed for order evaluation (link to Book 4)  
### B00.CH12.P03.S03 Normalisation: units, deflators, price indices, time resolution (canonical)  
### B00.CH12.P03.S04 Consistency: reconciliation with accounting/national accounts and microdata  

## B00.CH12.P04 Auditability: traceability and controllable chains

### B00.CH12.P04.S01 End-to-end lineage: claim → data → transformation → metric → decision  
### B00.CH12.P04.S02 Logging and immutability: changelogs, hashes, versioned datasets/models  
### B00.CH12.P04.S03 Sampling and forensic audits: red flags, anomaly detection, deep dives  
### B00.CH12.P04.S04 Independent audit: role separation, mandates, liability  

## B00.CH12.P05 Reproducibility and replication

### B00.CH12.P05.S01 Reproducible result: third party can obtain the same outcome from the same inputs  
### B00.CH12.P05.S02 Replication requirement: independent data or methods must converge within a band  
### B00.CH12.P05.S03 Open method, closed data: privacy-compatible publication (differential disclosure)  
### B00.CH12.P05.S04 Ban on “trust me” models: untestable claims are non-conform  

## B00.CH12.P06 Uncertainty: intervals, error margins and conservatism

### B00.CH12.P06.S01 Uncertainty reporting: interval estimates, sensitivity analysis, assumptions register  
### B00.CH12.P06.S02 Conservatism rule: under uncertainty, choose against privileges (towards E/cap/forbidden channel)  
### B00.CH12.P06.S03 Model uncertainty: structural uncertainty made explicit (no pseudo-precision)  
### B00.CH12.P06.S04 Revision policy: how updates are processed without semantic break  

## B00.CH12.P07 Attribution and causality (claims about effects)

### B00.CH12.P07.S01 Causal claims require counterfactual discipline (pre/post, control groups, IV where appropriate)  
### B00.CH12.P07.S02 Mechanism claims: explicit causal chain (ΔM→C/essentials→L→R/B)  
### B00.CH12.P07.S03 Confounding and selection: detection and correction requirements  
### B00.CH12.P07.S04 Ban on post-hoc storytelling: narrative without testing is non-conform  

## B00.CH12.P08 Publication requirements and transparency

### B00.CH12.P08.S01 Minimum publication: methods, definition-set ID, core statistics, uncertainty  
### B00.CH12.P08.S02 Public registers: compatibility status, exceptions, forks, audit results  
### B00.CH12.P08.S03 Access for researchers/journalists: procedures and data minimalism  
### B00.CH12.P08.S04 Redaction & privacy: what may be anonymised; what must be public  

## B00.CH12.P09 Dispute protocol: contesting measurements and claims

### B00.CH12.P09.S01 Initiation: who may challenge a measurement claim and on what grounds  
### B00.CH12.P09.S02 Procedure: time-bounded steps, evidentiary rules, independent review  
### B00.CH12.P09.S03 Correction: restatements, recalculation, public rectification  
### B00.CH12.P09.S04 Escalation: in case of structural measurement failure → suspension of conformity status (fail-closed)  

## B00.CH12.P10 Anti-Goodhart: metric governance

### B00.CH12.P10.S01 Metric rotation: multiple metrics per invariant to limit gaming  
### B00.CH12.P10.S02 Triangulation: alternative data/methods as mandatory counterweight  
### B00.CH12.P10.S03 Monitoring of gaming: detection of strategic responses to KPIs  
### B00.CH12.P10.S04 Ban on single-metric governance: no decision on one KPI without corroboration  

## B00.CH12.P11 Tooling and model standards (incl. AI)

### B00.CH12.P11.S01 Model cards and datasheets: assumptions, limits, failure modes  
### B00.CH12.P11.S02 Model audit: reproducibility, bias checks, drift monitoring  
### B00.CH12.P11.S03 Black-box limitation: critical decisions require interpretable/inspectable pipelines  
### B00.CH12.P11.S04 Supply-chain security: provenance of data/software, signed builds, tamper evidence  

## B00.CH12.P12 Failure modes and hard stops

### B00.CH12.P12.S01 Measurement-washing: pretty dashboards without traceable data (detection)  
### B00.CH12.P12.S02 Capture of audits: auditors dependent on auditees (institutional leak)  
### B00.CH12.P12.S03 Over-measurement: surveillance risk from data maximalism (non-conform)  
### B00.CH12.P12.S04 Fail-closed: when reproducibility/lineage is lost, decision space is curtailed  

# B00.CH13 Canon version control: changelog, restatements/bridging, backward compatibility and deprecation

## B00.CH13.P01 Purpose, scope and normative status of version control

### B00.CH13.P01.S01 Version control as order invariant: semantic stability is enforceability  
### B00.CH13.P01.S02 Purpose: controlled evolution without drift, without “shadow canons”  
### B00.CH13.P01.S03 Scope: Kernel Spec, definition sets, parameters, Codex/Standards, measurement methods  
### B00.CH13.P01.S04 Relation to compatibility, forks, auditability and publication requirements  

## B00.CH13.P02 Release structure and identification (definition-set ID + version)

### B00.CH13.P02.S01 Versioning scheme: MAJOR.MINOR.PATCH (semantic)  
### B00.CH13.P02.S02 Release ID: date, hash, signature, immutable artifact  
### B00.CH13.P02.S03 Definition-set ID binding: version binds to definition sets (I–VI) and parameters  
### B00.CH13.P02.S04 Publication channels: registry, archive, mirrors, verification instructions  

## B00.CH13.P03 Change classes: what counts as patch/minor/major

### B00.CH13.P03.S01 Patch: clarification without meaning change (formal equivalence must be shown)  
### B00.CH13.P03.S02 Minor: parameter extension or new optional module within invariants  
### B00.CH13.P03.S03 Major: change to an invariant, definitions, or conflict rules (fork risk)  
### B00.CH13.P03.S04 Prohibited change: retroactive semantics without restatement/bridge  

## B00.CH13.P04 Changelog requirements (transparency and impact)

### B00.CH13.P04.S01 Minimum fields: what, why, who, date, review, tests, impact on invariants  
### B00.CH13.P04.S02 Diff publication: text diff + formal mapping (old→new terms/rules)  
### B00.CH13.P04.S03 Impact analysis: effects on R/B, P/E/C, caps, ΔM, commons and auditability  
### B00.CH13.P04.S04 Communication: compatibility-label updates and public summary without marketing  

## B00.CH13.P05 Restatements: canonical rephrasings without substantive change

### B00.CH13.P05.S01 Purpose: readability and integration without drift  
### B00.CH13.P05.S02 Permissibility: only with demonstrable formal equivalence  
### B00.CH13.P05.S03 Traceability: restatement references source version + proof of equivalence  
### B00.CH13.P05.S04 Hard stop: a restatement that shifts meaning = major change (fork/ratification)  

## B00.CH13.P06 Bridging: mappings between versions and between forks

### B00.CH13.P06.S01 Bridge documents: explicit translation of definitions/parameters/metrics  
### B00.CH13.P06.S02 Use cases: sector canvases, jurisdiction implementations, dataset migrations  
### B00.CH13.P06.S03 Correctness criteria: preserve invariant claims or explicitly declare a break  
### B00.CH13.P06.S04 Interoperability: a bridge is an annex, not a new canon (no shadow definitions)  

## B00.CH13.P07 Backward compatibility: policy and guarantees

### B00.CH13.P07.S01 Compatibility windows: how long old versions remain “supported”  
### B00.CH13.P07.S02 Compatibility tests: implementations must demonstrate outputs do not break  
### B00.CH13.P07.S03 Data and model migration: schema evolution with reproducibility  
### B00.CH13.P07.S04 Ban on silent breaks: breaking changes require major bump + notice  

## B00.CH13.P08 Deprecation: phase-out of terms, rules and modules

### B00.CH13.P08.S01 Deprecation notice: timeline, rationale, impact, migration path  
### B00.CH13.P08.S02 Deprecation tags: “discouraged”, “deprecated”, “removed” (canonical)  
### B00.CH13.P08.S03 Sunsets: automatic expiry of temporary exceptions/crisis modes  
### B00.CH13.P08.S04 Hard stop: expired modules lose compatibility status  

## B00.CH13.P09 Governance of changes (procedure and roles)

### B00.CH13.P09.S01 Roles: editor, reviewer, auditor, ratifier, public registrar  
### B00.CH13.P09.S02 Review criteria: invariant preservation, auditability, anti-avoidance, privacy minimalism  
### B00.CH13.P09.S03 Decision procedure: quorum, supermajority for major, dispute protocol  
### B00.CH13.P09.S04 Audit the guardians: external assessment of change processes  

## B00.CH13.P10 Incident and emergency patch regime

### B00.CH13.P10.S01 Incident triggers: exploit/avoidance discovered, measurement error, security breach, drift event  
### B00.CH13.P10.S02 Emergency patch procedure: rapid patch with post-hoc audit and sunset  
### B00.CH13.P10.S03 Rollback: criteria, procedure, communication and restoration of compatibility status  
### B00.CH13.P10.S04 Ban on emergency-patch abuse: crisis as cover for semantic erosion  

## B00.CH13.P11 Registers and proof of integrity

### B00.CH13.P11.S01 Canon registry: list of releases, hashes, signatures, mirrors  
### B00.CH13.P11.S02 Compatibility registry: implementations, status, exceptions, audit results  
### B00.CH13.P11.S03 Provenance: who published what and when (tamper evidence)  
### B00.CH13.P11.S04 Archiving: long-term access, citability, immutable snapshots  

## B00.CH13.P12 Failure modes and hard stops

### B00.CH13.P12.S01 Document sprawl: multiple “near-canons” → prohibited; consolidation required  
### B00.CH13.P12.S02 Drift via silent edits: no mutable publications; releases only  
### B00.CH13.P12.S03 Governance capture: stacking exceptions via major changes without fork label  
### B00.CH13.P12.S04 Fail-closed: loss of integrity/registration suspends canon status  
