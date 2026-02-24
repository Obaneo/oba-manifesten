| id         | book | chapter | type   | status |
|------------|------|---------|--------|--------|
| B01.README | B01  | —       | readme | draft  |

# B01 — Economic Order & Commons Infrastructure

This book specifies the **economic layer** of OBA: how the Kernel Spec is applied to flows, household residual space, bounded accumulation, commons build-up, and the allocation of monetary space (ΔM) into the commons rather than into asset/claim inflation.

**Scope:** economic order design + auditability requirements.  
**Non-scope:** party politics, persuasion, ideology, “nice narratives”, or new definitions that override the Kernel Spec.

---

## What this book is

B01 is an **application layer** of the Kernel Spec to the economy, with four core functions:

1. **Flow classification (P/E/C):** decompose economic flows into productive value, extractive components, and commons contribution.
2. **Household order indicator (R/B ≥ α):** define and measure residual space via the B→T→N→L→R chain, with distribution profiles rather than averages.
3. **Bounded accumulation (W-MAX / I-MAX):** cap accumulation (or enforce functional equivalents) with robust anti-avoidance.
4. **ΔM→commons allocation:** specify channels, governance, and anti-capture rails so monetary space builds and maintains commons capacity.

Everything in this book is written to remain **auditable**, **versionable**, and **fail-closed** under missing evidence.

---

## What this book is not

- **Not a new canon.** It must not redefine terms from the Kernel Spec.
- **Not a collection of policy slogans.** Claims must map to measurable indicators and audit routes.
- **Not “growth-first” economics.** Outcomes are evaluated by order variables (E share, R/B tails, cap effectiveness, commons ΔG and quality, ΔM channel distribution).
- **Not surveillance-by-default.** Measurement is bounded and must respect proportionality constraints.

---

## How to use this book

- Start with **[index.md](./index.md)** for the chapter map and reading route.
- Use **[outline.md](./outline.md)** to see the full structure before writing or reviewing.
- For each chapter:
  - `chapters/B01_CHxx/readme.md` states purpose/scope/binding.
  - `chapters/B01_CHxx/index.md` lists paragraphs (Pxx) and sections (Sxx).
  - `chapters/B01_CHxx/Pyy.md` contains the normative content and testable claims.

---

## Chapter summary (one line each)

- **CH01:** kernel-on-one-page; invariants, notation, compatibility conditions, reading guide  
- **CH02:** P/E/C flow network model; attribution, consolidation, edge cases, measurability  
- **CH03:** residual space (R/B ≥ α); burdens definition, distributions, Goodhart mitigations  
- **CH04:** W-MAX / I-MAX; functional equivalents; transition regimes; anti-avoidance toolkit  
- **CH05:** phase-down of parasitic flows; typology, instruments, shift-detection, sequencing  
- **CH06:** commons as base layer; rights, governance minimum, maintenance/financing, ΔG metrics  
- **CH07:** ΔM→commons; channels, criteria, governance, anti-capture, banking interface, dashboards  
- **CH08:** state/fiscality/debt; boundary conditions, legal anchoring, social security as R/B stabilizer  
- **CH09:** sector reference implementations; housing/energy/healthcare/platforms; reusable sector canvas  
- **CH10:** measurability & audit; minimum dataset, consolidation, audit architecture, public reporting, privacy  
- **CH11:** implementation risks; avoidance, arbitrage, capture, regression, shocks, hard stops  
- **CH12:** economic consistency test; pillar check, KPI minimum, red flags, fork protocol, cross-book links

---

## Binding and compatibility rules

- **Kernel precedence:** where there is any conflict, the Kernel Spec wins.
- **No new definitions:** B01 may only apply and operationalize existing definitions.
- **Fail-closed:** if measurement/auditability is not available, compatibility labels must not be issued.
- **Version discipline:** changes must be recorded with rationale and traceability.

---

## Interfaces to other books

- **Book 0 (Kernel Spec):** canonical definitions, axioms, invariants, and core calculation rules.
- **Book X (Codex):** schemas, validators, audit packs, dispute flows, publication tables.
- **Book 2:** transition sequencing, stress tests, capital flight / retaliation scenarios.
- **Book 3:** governance and legitimation for core levers, especially ΔM oversight.
- **Book 4:** information and audit conditions for measurement without drift or capture.
- **Book 5:** lifeworld validation layer (experienced burdens, contract clamp, sector day-in-the-life tests).

---

## Repository conventions

- Filenames are **lowercase** (`readme.md`, `index.md`, `outline.md`) to avoid case-sensitive link breakage.
- IDs follow the grammar: `B01.CHxx.Pyy.Szz` (book/chapter/paragraph/section).
- Any “draft” content should still be structurally valid (IDs, headers, links), even if incomplete.
