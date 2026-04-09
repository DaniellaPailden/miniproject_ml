# LNCS LaTeX Workspace

## Structure
- `main.tex` — main entry file
- `sections/` — separate files for each major section
- `references.bib` — bibliography database
- `llncs.cls` — LNCS class file
- `splncs04.bst` — bibliography style file
- `figures/` — optional folder for images

## Compile order
Use:
1. `pdflatex main.tex`
2. `bibtex main`
3. `pdflatex main.tex`
4. `pdflatex main.tex`

This workspace is suitable for Overleaf or local LaTeX compilation.
