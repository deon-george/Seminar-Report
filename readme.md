# Seminar Report

**XGBoost-Based URL Phishing Detection Method With Cross-Dataset Validation**

> [!TIP]
> 📑 [Click here to view the full seminar report (`thesis.pdf`)](https://github.com/deon-george/Seminar-Report/raw/refs/heads/main/thesis.pdf)

## Contents

- `thesis.tex`: Main LaTeX entry point
- `frontpage.tex`: Title page, certificate, acknowledgement, abstract, and abbreviations
- `chapter/chapter1.tex` through `chapter/chapter12.tex`: Report chapters
- `ref.tex`: References
- `Annexure.tex`, `append.tex`, and `vm.tex`: Supporting report sections
- `dmathesis.cls`, `format.tex`, and `showlabel.sty`: Document class and formatting files
- `SJCET_logo.jpg`: Logo used by the report
- `thesis.pdf`: Compiled report

## Building the report

Install a LaTeX distribution with `latexmk`, then run from this directory:

```sh
latexmk -pdf thesis.tex
```

This creates the single final PDF, `thesis.pdf`. 

 To remove generated files:

```sh
latexmk -C thesis.tex
```

📄 Made with ❤️ by Deon George
