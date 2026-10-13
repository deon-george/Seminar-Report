> [!TIP]
> 📑 [View the completed seminar report (`thesis.pdf`)](./thesis.pdf)

# Seminar Report - XGBoost-Based URL Phishing Detection

This repository contains the seminar report **“XGBoost-Based URL Phishing Detection Method With Cross-Dataset Validation.”** The report examines the X-PHIDE approach for phishing URL detection, with emphasis on feature stability, Bayesian optimisation, browser-oriented deployment, and cross-dataset generalisation.

## Report highlights

- Explains phishing-URL detection using XGBoost and URL-derived features.
- Reviews the X-PHIDE pipeline: URL input, feature extraction, stable-feature selection, XGBoost scoring, and browser-side safety labels.
- Summarises experiments on the Custom, GramBeddings, and PhiUSIIL datasets.
- Highlights the difference between within-dataset and cross-dataset performance, including the reported 77.93% average F1 score across the three evaluation sets.
- Discusses model efficiency, limitations under dataset shift, and future directions such as retraining, model compression, and runtime validation.

## Reference material

- `XGBoost-Based_URL_Phishing_Detection_Method_With_Cross-Dataset_Validation.pdf` - the primary IEEE Access paper analysed in the report.
- `Seminar-ppt.pdf` - the accompanying seminar presentation.
- `thesis.pdf` - the final, ready-to-read seminar report.

## Repository structure

```text
.
├── thesis.pdf
├── XGBoost-Based_URL_Phishing_Detection_Method_With_Cross-Dataset_Validation.pdf
├── Seminar-ppt.pdf
├── README.md
├── thesis.tex
├── chapters/
├── frontmatter/
├── references/
└── assets/
```

## Note on sources

`thesis.pdf` is the current deliverable and reflects the XGBoost phishing-detection topic. The LaTeX source tree (`thesis.tex`, `chapters/`, `frontmatter/`, `references/`, and legacy assets) 

Made with ❤️ by Deon George 