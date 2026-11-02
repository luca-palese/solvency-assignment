# Solvency Assignment – Motor Insurance Claims Modelling

Claim frequency and severity modelling on the French Motor TPL dataset (freMTPL2), using GLMs (Poisson / Gamma) and XGBoost with SHAP explanations.

Notebook: `solvency_assignement.ipynb`

## Data

`fremtpl2-french-motor-tpl-insurance-claims/versions/1/` holds `freMTPL2freq.csv` and `freMTPL2sev.csv` (French Motor Third-Party Liability dataset, public via Kaggle / CASdatasets).

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```
