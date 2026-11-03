# Dissertation Prospectus: Trustworthy and Efficient Vision-Language Models for Medical Imaging

Prospectus of Hanqi Jiang, PhD candidate in the School of Computing at the University of Georgia.

## Build
This project uses a standard pdfLaTeX + BibTeX build. It needs no shell-escape, so Overleaf's default settings work.

```
latexmk -pdf main.tex
# or: pdflatex main && bibtex main && pdflatex main && pdflatex main
```

## Layout
- `main.tex`: root document
- `sections/`: title page, abstract and chapters
- `figures/`: figures reused from the source papers (each caption credits its paper)
- `refs.bib`: bibliography
