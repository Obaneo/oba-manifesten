---
id: B00.CH01.README
book: B00
chapter: CH01
type: readme
status: draft
---

# B00.CH01 — Kernel: Core Spec as Canon

This chapter defines the **reading and governance contract** for the entire B00 Core Spec. It establishes what the Core Spec is (and is not), how it is referenced, and how claims of compatibility are evaluated and enforced.

The chapter is intentionally *normative*: it specifies rules, constraints, and procedures that prevent semantic drift, OBA-washing, and “shadow canons.”

## How to use this chapter

- If you are **writing** new Core Spec content: follow the scope and anti-drift rules (P02–P04).
- If you are **implementing** OBA in a jurisdiction, sector, or system: treat P05 as binding evaluation logic.
- If you are **auditing** an OBA claim: use P05–P07 as the minimum acceptance test for documentation, publication, and integrity.
- If you are **updating** the canon: follow P06–P07 (change discipline, deprecations, releases, forks).

## Structure

- **P01 — Purpose and function**: why the Core Spec exists and what it guarantees.
- **P02 — Scope and layers**: what belongs inside the Core Spec vs derived materials.
- **P03 — Identity and reference**: IDs, registries, and citation units.
- **P04 — Anti-drift rules**: preventing redefinition, synonym drift, and shadow definitions.
- **P05 — Reading contract**: fail-closed evaluation rules and evidence obligations.
- **P06 — Canon governance**: how changes are proposed, reviewed, and ratified.
- **P07 — Publication and integrity**: immutable releases, transparency, forks, interoperability mappings.

## Status

This chapter is expected to stabilize early and change rarely. When it changes, it typically implies **major** impact (compatibility labels, enforcement rules, or fork boundaries) and therefore requires heightened review, explicit changelogs, and public notice.
