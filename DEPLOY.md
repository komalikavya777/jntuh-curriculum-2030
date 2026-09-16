# Assembling and publishing

## Repository layout

```
jntuh-curriculum-2030/
├── README.md        ← sections 1-7 concatenated, in order
├── SOURCES.md       ← your source list, grouped primary / contrast / cross-check / secondary
├── index.html       ← the live report
└── evidence/        ← (optional) lab sheets, prompt transcripts, screenshots of the R25 structure
```

Build `README.md` by concatenating your existing sections 1-4 with the new files, in order:

```bash
cat README_sections1-4.md section5.md section6.md section7.md > README.md
```

Keep the heading levels consistent — every section starts at `##`, as these files do.

## Publishing the live report on GitHub Pages

1. Push `index.html` to the repository root on the `main` branch.
2. Repository → **Settings** → **Pages**.
3. Source: *Deploy from a branch*. Branch: `main`, folder: `/ (root)`. Save.
4. Wait two or three minutes. The URL will be `https://<your-username>.github.io/<repo-name>/`.
5. Open that URL **on your phone, on mobile data, not on college wifi.** That is the actual test the brief asks for — that it opens from a machine that is not yours.

## Before you submit

- [ ] Repository is **public** (Settings → General → Danger Zone → Change visibility).
- [ ] The Pages URL opens in a private/incognito window.
- [ ] Every filter chip on the live page does something visible when tapped.
- [ ] Section 7's ⚠️ placeholders are all replaced or deleted — 7b, the two `[DATE]` fields in 7c, and the conversation record.
- [ ] The conversation has actually happened, and the unexpected thing is written down.
- [ ] `README.md` renders correctly on GitHub (check the tables — GitHub is stricter about pipe alignment than most editors).

## The two one-sentence submission fields

Drafts you can cut down, both drawn from what the report actually found:

**Biggest finding.** In four of the five subjects I tested, a 2026 model produced the lab artefact to passing standard and missed the correctness check — so what has aged in R22 is the assessment, not the content.

**First curriculum change.** Add a 3-credit Verification and Evaluation of AI Systems course in IV-II, paid for by removing Open Elective III, and mark students on the defects they find rather than the artefacts they produce.
