| id         | book | chapter | type   | status |
|------------|------|---------|--------|--------|
| B05.README | B05  | —       | readme | draft  |

# B05 — Lifeworld & Institutions under OBA (Work, time, security, and “day-in-the-life” sector cases)

This folder contains **Book 5 (B05)** of the OBA manifests.  
B05 specifies the **lifeworld and institutions layer**: how OBA’s macro-invariants become **experienced** BRUTO/NETTO/LASTEN/RESTRUIMTE, how clamp dynamics and toll layers are detected in daily routines, and how institutions (work, care, security, housing, energy, health/education, digital, local governance) must be designed to deliver **measurable L-reduction and tail-risk stabilisation** without drift or new extraction channels.

B05 is intentionally **anti-washing and anti-drift**:
- it **references** canonical definitions and calculation rules where they already live (Kernel Spec / Book 1 / Codex),
- and focuses on **lifeworld validation, institutional execution patterns, contestability, auditability, and stop rules**.

---

## Files

- `outline.md` — English outline for B05 (authoritative structure)
- `INDEX.md` — navigation index (chapter map + reading route)
- `README.md` — this file
- `chapters/` — chapter content, stored as machine-addressable units

---

## Structure and naming conventions

**ID grammar**
- Chapter: `B05.CHxx`
- Paragraph: `B05.CHxx.Pyy`
- Subparagraph: `B05.CHxx.Pyy.Szz`

**Folder layout (recommended)**
- `chapters/B05_CH01/`
  - `P01.md`
  - `P02.md`
  - ...
- `chapters/B05_CH02/`
  - `P01.md`
  - `P02.md`
  - ...

This keeps the repository:
- human-navigable (GitHub browsing),
- and machine-robust (stable IDs and deterministic ordering).

---

## Editing rule (anti-drift)

- **Do not redefine** canonical terms (P/E/C, B/T/N/L/R, caps W/I, ΔM rails, core tests) inside B05.
- If B05 needs a definition, it must **reference** the canonical location and only specify:
  - the **lifeworld translation**,  
  - the **institutional implication**, and/or  
  - the **measurement/audit requirement**.

---

## What B05 is (and is not)

**B05 is**
- a **lifeworld validation layer**: the “contract clamp test” for everyday reality (essentials, lock-in, fee stacks, block power),
- an **institutional execution layer**: repeatable templates for work/care/security/essentials institutions that produce measurable outcomes,
- a **case layer**: day-in-the-life cases and sector templates as regression tests,
- a **stop-rule layer**: failure modes (resentment, sabotage, evasion, drift/capture) and fail-closed conditions.

**B05 is not**
- the canonical definition layer (Kernel Spec / Book 0),
- the economic elaboration and measurement canon (Book 1),
- the transition instrument catalogue and sequencing logic (Book 2),
- nor the standards and schema authority itself (Book X / Codex), except by reference.

---

## Status discipline

Each artifact has a status header table (draft → reviewed → stable).  
Keep changes traceable:
- prefer small, ID-scoped edits,
- preserve semantics by ID,
- and maintain changelog discipline inside the relevant paragraph files.

---

## Suggested next steps (practical)

1. Ensure `chapters/B05_CH01/ ... B05_CH18/` exist (even if empty placeholders).
2. Add `P01.md`, `P02.md`, ... per chapter as you start writing (matching the outline IDs).
3. Keep `outline.md` authoritative; content files should implement it.

If you later generate a compiled “single book” output, the deterministic order should be:
- sort by ID (CH → P → S),
- concatenate with stable headings,
- and never hand-edit the compiled output (compile is a build artifact).
