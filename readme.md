# Seminar Report

**XGBoost-Based URL Phishing Detection Method With Cross-Dataset Validation**

This repository contains the LaTeX source for the seminar report based on the source paper by Misiek and Hyla (2026), published in *IEEE Access* (DOI: [10.1109/ACCESS.2026.3672690](https://doi.org/10.1109/ACCESS.2026.3672690)).

## Contents

- `thesis.tex`: Main LaTeX entry point
- `frontpage.tex`: Title page, certificate, acknowledgement, abstract, and abbreviations
- `chapter1.tex` through `chapter12.tex`: Report chapters
- `ref.tex`: References
- `Annexure.tex`, `append.tex`, and `vm.tex`: Supporting report sections
- `dmathesis.cls`, `format.tex`, and `showlabel.sty`: Document class and formatting files
- `SJCET_logo.jpg`: Logo used by the report

## Building the report

Install a LaTeX distribution with `latexmk`, then run from this directory:

```sh
latexmk -pdf thesis.tex
```

The generated PDF and auxiliary build files are ignored by Git. To remove generated files:

```sh
latexmk -C thesis.tex
```

## Before submission

Verify institutional names, dates, and approval or signature details. Numerical findings are attributed to the original authors and are not presented as an independent reproduction of their experiments.
