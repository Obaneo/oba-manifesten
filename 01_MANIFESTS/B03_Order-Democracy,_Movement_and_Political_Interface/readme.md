| id         | book | chapter | type   | status |
|------------|------|---------|--------|--------|
| B03.README | B03  | —       | readme | draft  |

# B03 — Order-Democracy, Movement and Political Interface

This folder contains **Book 3 (B03)** of the OBA manifests.  
B03 specifies the **political and institutional interface layer**: what democratic politics may decide, what is constitutively invariant, how mandates remain contestable, how commons governance stays non-captured, how variants/forks are labeled, and how drift is detected and corrected.

B03 is intentionally **anti-drift**:
- It **references** canonical definitions and calculation rules where they already live (Kernel Spec / Book 1),
- and focuses on **governance, mandate discipline, contestability, auditability, and labeling rules**.

---

## Files

- `outline.md` — English outline for B03 (authoritative structure)
- `INDEX.md` — navigation index (chapter map + reading route)
- `README.md` — this file
- `chapters/` — chapter content, stored as machine-addressable units

---

## Structure and naming conventions

**ID grammar**
- Chapter: `B03.CHxx`
- Paragraph: `B03.CHxx.Pyy`
- Subparagraph: `B03.CHxx.Pyy.Szz`

**Folder layout (recommended)**
- `chapters/B03_CH01/`
  - `P01.md`
  - `P02.md`
  - ...
- `chapters/B03_CH02/`
  - `P01.md`
  - `P02.md`
  - ...

This keeps the repository:
- human-navigable (GitHub browsing),
- and machine-robust (stable IDs and deterministic ordering).

---

## Editing rule (anti-drift)

- **Do not rephrase** canonical definitions from the Kernel Spec / Book 1 inside B03.
- If B03 needs a definition, it should **reference** the canonical location and only specify the **political/governance implication**.

---

## What B03 is (and is not)

**B03 is**
- a governance and democracy layer: invariants, mandate types, institutional design, commons governance, anti-capture, conflict mechanics, fork/compatibility labeling, and a closing consistency test.

**B03 is not**
- the canonical definition layer (Kernel Spec),
- the economic rulebook and measurement canon (Book 1),
- nor the transition instrument catalogue (Book 2).

---

## Status discipline

Each artifact has a status header table (draft → reviewed → stable).  
Keep changes traceable:
- prefer small, ID-scoped edits,
- preserve semantics by ID,
- and maintain changelog discipline inside the relevant paragraph files.

---

## Suggested next steps (practical)

1. Ensure `chapters/B03_CH01/ ... B03_CH12/` exist (even if empty placeholders).
2. Add `P01.md`, `P02.md`, ... per chapter as you start writing.
3. Keep `outline.md` authoritative; content files should implement it.

If you later generate a compiled “single book” output, the deterministic order should be:
- sort by ID (CH → P → S),
- concatenate with stable headings,
- and never hand-edit the compiled output (compile is a build artifact).

