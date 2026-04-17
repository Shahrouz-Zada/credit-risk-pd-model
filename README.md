
# Credit Risk Modeling Project (PD Estimation)

## Objective

This project implements an end-to-end credit risk modeling framework for estimating Probability of Default (PD), inspired by Basel/IFRS9 practices.

---
## Project Highlights

- End-to-end PD modeling pipeline
- Out-of-time validation framework
- Calibration diagnostics and correction
- ML vs traditional model comparison

## Methodology

- Data transformation into bank-style portfolio
- Time-based train/test split
- Logistic Regression (baseline)
- LightGBM (ML challenger)
- Evaluation using AUC and KS
- Calibration analysis and adjustment

---

## Key Results

- Logistic Regression:
  - AUC ≈ 0.81
  - KS ≈ 0.52

- LightGBM:
  - AUC ≈ 0.87
  - KS ≈ 0.62

---

## Key Insights

- LightGBM improves predictive performance but suffers from calibration issues
- Logistic regression provides more stable PD estimates
- Base-rate shift significantly impacts calibration
- Post-model calibration improves alignment with observed defaults

---

## Tools

- Python (pandas, numpy)
- scikit-learn
- LightGBM

---

## Author

Shahrouz JAFARZADEH (ZADA)
