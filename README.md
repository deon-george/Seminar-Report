# Seminar Report - NeRF-DA

This repository contains the LaTeX source for the seminar report titled "NeRF-DA: Neural Radiance Fields Deblurring with Active Learning".

## Project structure

- `thesis.tex` — main document entry point
- `frontmatter/` — title page and formatting setup
- `chapters/` — chapter files
- `references/` — bibliography file
- `assets/` — images and other media
- `templates/` — class and style files

## Build

From the project root, compile with:

```bash
pdflatex -interaction=nonstopmode -halt-on-error thesis.tex
```

If you use a LaTeX build tool such as `latexmk`, it can also be used for repeated recompilation:

```bash
latexmk -pdf thesis.tex
```

## Notes

- The project is configured so that generated LaTeX artifacts are ignored via `.gitignore`.
- The source is organized into logical folders to keep the thesis easier to manage and maintain.
