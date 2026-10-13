> [!TIP]
> 📑 [Click here to view the Full Literature Review (`thesis.pdf`)](./thesis.pdf)

# Seminar Report - NeRF-DA

Welcome to the repository for the Seminar Report on **NeRF-DA: Neural Radiance Fields Deblurring with Active Learning**, written in LaTeX. This project serves as a centralized, version-controlled source for the document, allowing for clean formatting and easy updates.

## 🚀 How to Build

To compile the PDF from the LaTeX source, you will need a LaTeX distribution installed on your system, such as TeX Live, MiKTeX, or MacTeX.

Clone the repository:

```bash
git clone <repository-url>
cd Seminar-Report
```

Compile the document:

You can compile the `.tex` file using `pdflatex`:

```bash
pdflatex -interaction=nonstopmode -halt-on-error thesis.tex
```

This will generate a `thesis.pdf` file in the same directory.

Alternatively, you can use a LaTeX build tool such as `latexmk` for repeated recompilation:

```bash
latexmk -pdf thesis.tex
```

## 📁 Repository Structure

- `thesis.tex`: The main LaTeX source file containing the report content and formatting.
- `thesis.pdf`: The compiled, ready-to-view PDF version of the seminar report.
- `frontmatter/`: Title page, formatting, and document front matter.
- `chapters/`: Individual chapter source files.
- `references/`: Bibliography/reference file.
- `assets/`: Images, figures, and other media used in the document.
- `templates/`: Backup or legacy class/style files.
- `.gitignore`: Git configuration to ignore temporary LaTeX build artifacts.
- `README.md`: This file, providing an overview of the repository.

## Notes

- The project is organized into logical folders to keep the thesis easier to manage and maintain.
- Generated LaTeX artifacts are ignored via `.gitignore` so the repository stays clean.
- The source is suitable for local compilation or for uploading to Overleaf as-is.
