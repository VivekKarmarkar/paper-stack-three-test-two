# paper-stack-three-test-two

A small test corpus and bibliography artifacts for the **Stack 3** (user-curated) branch of an agentic literature-review pipeline. The repo holds the source PDFs, the OpenAlex-enriched metadata records, and the compiled bibliography PDFs produced by the `/identify-papers-user*` and `/latex` skills.

## What's here

The corpus is organized around a tomography / inverse-elasticity literature thread (the "PAT-scan" topic):

- **`shortlisted/`** — 8 PDFs grouped by methodological category:
  - `Mathematical Foundations/` (1 paper, 1994)
  - `Statics/` (5 papers, 2003–2022)
  - `Vibrations/` (2 papers, 2007–2022)
- **`precomps/`** — 4 PDFs in a flat folder. Three overlap with the shortlisted set; one (Wu 2024, JAX-SSO) is unique.

Each curated subset has been run through the Stack 3 enrichment pipeline, producing the metadata `.md` files and the compiled bibliography PDFs at the repo root.

## Generated artifacts

| File | What it is |
|---|---|
| `identified_papers_user_shortlisted.md` | OpenAlex metadata for the 8 shortlisted papers — title, DOI, authors + affiliations, year, venue, topics, abstract, source paths |
| `identified_papers_user_precomps.md` | Same, for the 4 precomps papers |
| `identified_papers_user_tree_candidates_shortlisted.md` | Candidate list from the tree-walk of `shortlisted/` |
| `identified_papers_user_folder_candidates_precomps.md` | Candidate list from the flat scan of `precomps/` |
| `shortlisted_bibliography.tex` / `.pdf` | Publication-quality bibliography PDF grouped by the three shortlisted categories |
| `precomps_bibliography.tex` / `.pdf` | Bibliography PDF for the precomps set, with overlap-vs-unique flagged |

## How the artifacts were produced

1. **Discover** — walk a curated tree (or scan a flat folder) for PDFs, extracting a best-effort title per file:
   ```
   /identify-papers-user-tree    shortlisted/
   /identify-papers-user-folder  precomps/
   ```
2. **Enrich** — hit OpenAlex per candidate, dedup by DOI / normalized title with address-union for source paths:
   ```
   /identify-papers-user
   ```
3. **Render** — compile a typeset bibliography PDF from the enriched metadata:
   ```
   /latex
   ```

The discover and enrich skills are part of the user's Claude Code skill library under `~/.claude/skills/identify-papers-user*/`. Stack 3 deliberately omits verify + validate gates — every PDF the user placed is trusted on curation.

## Quick stats

- **Total unique papers across both stacks:** 9 (8 shortlisted + 1 unique to precomps)
- **Year span:** 1994 – 2024
- **Open-access papers:** 5 (gold ×2, green ×3)
- **Most-cited:** Zhang et al. 2022 (Science Advances, PINNs for elasticity) — 344 citations
- **In-house University of Iowa contribution:** Liu, Sun & Wang 2005 (IEEE T-MI)

## Project layout

```
.
├── shortlisted/
│   ├── Mathematical Foundations/
│   ├── Statics/
│   └── Vibrations/
├── precomps/
├── identified_papers_user_shortlisted.md
├── identified_papers_user_precomps.md
├── identified_papers_user_tree_candidates_shortlisted.md
├── identified_papers_user_folder_candidates_precomps.md
├── shortlisted_bibliography.tex
├── shortlisted_bibliography.pdf
├── precomps_bibliography.tex
└── precomps_bibliography.pdf
```

## Compiling the bibliography PDFs

The `.tex` files use only stock CTAN packages (`amsmath`, `xcolor`, `enumitem`, `titlesec`, `hyperref`, `fancyhdr`). To rebuild:

```bash
pdflatex -interaction=nonstopmode shortlisted_bibliography.tex
pdflatex -interaction=nonstopmode precomps_bibliography.tex
```

## Notes

- This is a **test corpus** — the directory name carries `-test-two` deliberately. It's used to exercise the Stack 3 pipeline on a small, well-understood input set.
- PDFs are checked in because they ARE the corpus, not build artifacts.
- `.claude/` (Claude Code session state) is gitignored.
