# regulated-credit-scoring-amex
Regulated Credit Scoring with Explainable and Monotonic Machine Learning


# Regulated Credit Scoring with AMEX Default Prediction

## Project Overview
This project builds a credit default prediction model using the AMEX Default Prediction dataset. The goal is to compare baseline modeling, aggregated customer-level features, monotonic constraints, and SHAP-based explainability.

## Business Problem
Credit scoring models are used to estimate the risk that a customer will default. In regulated finance, model performance alone is not enough. Interpretability, stability, and explainability are also important.

## Methods
- Last statement baseline model
- Aggregated customer-level features
- LightGBM classifier
- Monotonic constraints
- SHAP explainability

## Evaluation Metrics
- ROC-AUC
- PR-AUC / Average Precision
- Precision
- Recall
- F1-score
- Recall@Top4%

## Project Structure
```text
regulated-credit-scoring-amex/
├── notebooks/
├── reports/
└── figures/


Key Results
Aggregated features improved model performance compared to the last-statement baseline.
SHAP analysis showed that features such as P_2, B_1, B_4, and D_39 were important for prediction.
Monotonic constraints were tested to make the model more aligned with credit risk intuition.
Tools

Python, pandas, scikit-learn, LightGBM, SHAP, matplotlib
```

