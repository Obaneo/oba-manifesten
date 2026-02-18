| id         | book | chapter | type   | status |
|------------|------|---------|--------|--------|
| B00.README | B00  | —       | readme | draft  |

# B00 — Core Spec (Formal definitions, axioms and invariants)

B00 is the **Kernel Spec** of OBA: it defines the canonical objects, axioms, invariants, and conflict rules that make OBA a **testable
class** rather than an interpretive label. B00 is written to be **auditable**, **reproducible**, and **version-pinnable**: any claim
must bind to explicit definition-set IDs and versions, and meaning must not drift through commentary, marketing, or local rewrite.

## How to use this book

- **Reading**: treat B00 as the meaning layer. Later books instantiate and apply it but must not redefine it.
- **Implementing**: pin implementations to the relevant definition-set IDs + versions and follow the parameter rails (no semantic edits).
- **Auditing / disputing**: use B00’s compatibility, evidence, and version-control rules to test claims and resolve conflicts.
- **Publishing / communicating**: do not use OBA name/status labels without the evidence, registry, and compatibility discipline defined here.

## Navigation

- Book index: [B00.BOOK](./INDEX.md)

## Chapters

- CH01 — Kernel: Core Spec as Canon  
- CH02 — Canonical notation and object model  
- CH03 — Definition set I: production, extraction and commons (P/E/C)  
- CH04 — Definition set II: GROSS→NET→ESSENTIALS→REMAINING SPACE (B,T,N,L,R) and R/B≥α  
- CH05 — Definition set III: caps on wealth/claims (W-MAX)  
- CH06 — Definition set IV: caps on income/flows (I-MAX)  
- CH07 — Definition set V: commons and maintenance (ΔG, access, boundary rules)  
- CH08 — Definition set VI: monetary space as allocation interface (ΔM; channel rules; prohibited channels)  
- CH09 — Control, benefit and block tests (ultimate control; look-through; consolidation)  
- CH10 — Anti-avoidance: reclassification, shift taxonomy and detection rules  
- CH11 — Compatibility and forks: parameter space, procedure, conflict rules and name usage  
- CH12 — Evidence and measurement standards: observability, auditability, reproducibility, uncertainty  
- CH13 — Canon version control: changelog, restatements/bridging, backward compatibility and deprecation  

## Status

B00 is normative. If integrity (registry, hashes/signatures, retrievability) or evidence requirements are not met, dependent claims
must be treated as **non-conform** (fail-closed) until corrected.

