| id             | book | chapter | type          | status |
|----------------|------|---------|---------------|--------|
| B03.CH01.README | B03  | CH01    | chapter-readme | draft  |

# B03.CH01 — Kernel (Chapter README)

This chapter is the Book 3 interface layer to the Kernel Spec: it states what Book 3 *does* (political decision grammar and boundary conditions) and what it *does not do* (no redefinition; no economic elaboration; no transition toolkit).

## Files

- `INDEX.md` — chapter navigation (links to each paragraph and subparagraph anchor)
- `P01.md` … `P06.md` — one file per paragraph

## Anchor convention (so S-links in INDEX.md work)

For each subparagraph `Sxx`, include an explicit HTML anchor in the paragraph file, e.g. in `P01.md`:

- `<a id="b03ch01p01s01"></a>` above the `B03.CH01.P01.S01` heading
- `<a id="b03ch01p01s02"></a>` above the `B03.CH01.P01.S02` heading
- …and so on

This keeps links stable and avoids GitHub’s auto-generated heading IDs drifting when titles change.

## Navigation

- Chapter index: [INDEX.md](./INDEX.md)

