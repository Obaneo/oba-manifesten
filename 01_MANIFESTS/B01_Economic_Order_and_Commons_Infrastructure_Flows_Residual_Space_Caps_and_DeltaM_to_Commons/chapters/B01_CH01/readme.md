| id           | book | chapter  | type   | status |
|--------------|------|----------|--------|--------|
| B01.CH01.README | B01  | B01.CH01 | readme | draft  |

# B01.CH01 — Kernel (one page)

This chapter provides the **minimum economic kernel** of Book 1 in one place: purpose, scope, invariants, notation, and the compatibility test for the economic layer.

It is written as a **navigation and binding layer**: it points to canonical sources, states what is non-negotiable, and defines how the rest of the book must be read and applied.

---

## What this chapter is

- A **one-page kernel** for B01: the smallest set of statements needed to orient design, review, and audit.
- A **binding map**: how Book 1 applies (but does not redefine) the Kernel Spec.
- A **compatibility gate**: necessary/sufficient conditions for claiming “OBA-compatible” in the economic layer.

---

## What this chapter is not

- Not a replacement for the Kernel Spec.
- Not a place to introduce new definitions, new semantics, or alternative notation.
- Not a policy wish-list: it defines structure, constraints, and testability requirements.

---

## Binding rule

**Kernel precedence:** if any wording in B01 conflicts with the Kernel Spec, the Kernel Spec wins.  
This chapter is therefore allowed to **summarize** and **reference**, but not to redefine.

---

## Chapter structure

- **P01 — Purpose and scope:** what Book 1 covers and what it explicitly does not.
- **P02 — Minimal invariants:** the non-negotiables; fail-closed on missing evidence.
- **P03 — Core notation:** B→T→N→L→R, P/E/C, W-MAX/I-MAX, ΔM, commons.
- **P04 — Compatibility test:** necessary and sufficient conditions to claim economic-layer compatibility.
- **P05 — Reading guide:** how to traverse the book without repetition and where templates live.

See: **[index.md](./index.md)** for the paragraph map.

---

## How to use this chapter

- **As a reviewer/auditor:** read P02 and P04 first; treat them as the gating criteria.
- **As an author/editor:** pin notation in P03 and avoid introducing synonyms elsewhere.
- **As an implementer:** treat P05 as the route map into later chapters and into Book X (Codex) for schemas and audit packs.

---

## Status and editing constraints

- Status: **draft** (structure is fixed; content may expand).
- Edits must preserve:
  - ID grammar (`B01.CH01.Pxx.Sxx`)
  - Link integrity (lowercase filenames)
  - No new definitions that override the Kernel Spec
  - Fail-closed discipline for any compatibility claim
