| id              | book | chapter | type   | status |
|-----------------|------|---------|--------|--------|
| B05.CH17.README | B05  | CH17    | readme | draft  |

<a id="b05ch17readme"></a>
# B05.CH17 — Sector cases as templates: sector-canvas in lifeworld form (housing/energy/healthcare/digital)

This chapter defines **sector cases as reusable templates**. It converts the sector-canvas into a repeatable lifeworld case format that
is **replicable**, **auditable**, and **machine-bindable** to Codex schemas/auditpacks. The objective is not narrative description; it is
operationalization: each sector case must expose bottlenecks, E-sources (fee stacks/lock-in), commons/public options, caps
compatibility, R/B effects, and ΔM channels—so that sector analysis can be instantiated consistently across jurisdictions and over time.

Narrative is allowed only as a carrier. The truth condition is **template completeness + measurement binding** (`definitionset_id`,
`method_id`, benchmark versions, uncertainty discipline).

CH17 is designed to be **anti-washing** and **FAIL-CLOSED**. A sector “case” that omits required template fields, omits ΔM channel logic,
or omits measurable lifeworld outputs is **NON-CONFORM** and not reusable. Likewise, using the template to justify surveillance or vendor
capture is a hard stop.

---

## Conformance gates (chapter-level)

A CH17 sector case **MUST**:
- Use the canonical template fields: **context**, **bottlenecks**, **E sources**, **commons/public option**, **caps compatibility**,
  **R/B effect + lifeworld metrics**, **ΔM channel**, **governance/execution**, **data/evidence minimum**.
- Bind outputs to `definitionset_id` and `method_id` and include uncertainty reporting where valuation/estimation is used.
- Emit machine-readable evidence and identifiers aligned to Codex (datasets, logs, contract templates, auditpacks).
- Include contestability and audit rails (including audit-on-the-auditor) as constitutive fields.

A CH17 sector case **MUST NOT**:
- Replace template fields with a “nice story” (template-washing).
- Use data maximalism (microdata publication, surveillance justification).
- Become a vendor/consultancy product outside procurement rails (capture).

---

## Scope and exclusions

**In scope**
- Four core exemplar sectors: **housing, energy, healthcare, digital** (minimum set).
- The template is extensible to other essentials, but extensions must not introduce new foundational definitions (only parameters and
  benchmarks).

**Out of scope**
- Sector ideology or political campaigning.
- Surveillance-first “data solutions”.
- Bespoke sector exceptions that break caps compatibility or no-arbitrage.

---

## Artifacts emitted (chapter outputs)

CH17 **MUST** emit:
- A canonical sector-case template structure (P02) suitable for cloning.
- Caps compatibility mapping fields (UBC look-through, incentive redesign, no-arbitrage) (P03).
- Lifeworld metric binding (B,T,N,L,R; tail and time friction outputs) (P04).
- ΔM channel rules (allowed/forbidden channels, leakage tests, sunset/rollback) (P05).
- Governance and execution fields (roles, decision logs, contestability, meta-audit) (P06).
- Data and evidence minimum schema (machine-readable identifiers and datasets; privacy rails) (P07).
- Four exemplars (P08) and extension rules/fork management (P09).
- Failure modes and hard stops (P10).

---

## How to use this chapter

- If you are **designing a sector intervention**: start with P02 (template) and fill P03–P05 to ensure caps compatibility, R/B impact,
  and ΔM channel discipline are explicit.
- If you are **building a commons/public option**: use P02.S04 + P06 to specify governance minima, maintenance plans, procurement rails,
  and contestability/audit requirements.
- If you are **auditing a sector narrative**: apply P01.S04 and P10—if bottlenecks/E/ΔM and measurement binding are missing, the case is
  NON-CONFORM.
- If you are **extending to a new sector**: use P09 (onboarding and fork management). Extensions may add parameters/benchmarks but must
  not add new definitions.

---

## Structure

P01 — Purpose, scope, and normative status of sector cases as templates  
P02 — Canonical template structure (one sector case)  
P03 — Caps compatibility and incentive redesign (per sector)  
P04 — R/B effect and lifeworld metrics (per sector)  
P05 — ΔM channel: financing and forbidden routes  
P06 — Template fields for governance and execution  
P07 — Data and evidence minimum per sector case (machine-readable)  
P08 — The four core cases as exemplars (housing/energy/healthcare/digital)  
P09 — Portability to other sectors (template extension)  
P10 — Failure modes and hard stops  

---

## Status

This chapter is **normative** for turning sector reasoning into OBA-conform case modules. The sector-case template fields, Codex binding,
and measurement discipline are treated as **constitutive** requirements. Any claim that a sector intervention reduces extraction,
improves essentials access, or stabilizes lifeworld tails must be able to instantiate this template and emit the linked measurements.

Conversely, if sector cases are produced that omit bottleneck/E/ΔM analysis, justify surveillance, or deliver no demonstrable L reduction
or tail stabilization, that is evidence of **NON-CONFORM** that must block scaling and trigger redesign under the hard-stop logic (P10).
