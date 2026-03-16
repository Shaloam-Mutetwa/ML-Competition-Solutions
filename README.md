# Machine Learning Competition Solutions

This repository contains my solutions to various machine learning competitions, primarily from Zindi, where I experiment with modeling techniques, feature engineering strategies, and evaluation methods.

The goal of this repository is to showcase my skills in:

- Data preprocessing and feature engineering
- Machine learning model development
- Model evaluation and benchmarking
- Explainability and feature importance analysis
- Competition-style ML pipelines

Each competition is organized into its own folder with notebooks, code, and documentation explaining the approach and results.

## Competitions

### DataOrg Financial Health Prediction

**Goal:** Predict the financial health category of small businesses using financial and behavioral indicators.

**Approach:**

- Feature engineering with financial ratios
- Gradient boosting models (LightGBM, CatBoost)
- Class imbalance handling
- Cross-validation and threshold tuning

### Financial Inclusion in Africa

This project predicts whether individuals in Kenya, Rwanda, Tanzania, and Uganda have access to a bank account.

**Problem:** Predict if an individual has a bank account (`0 = No`, `1 = Yes`)

**Models Used:**

- GradientBoostingClassifier (best performer, MAE ~= 0.10)
- XGBClassifier
- RandomForestClassifier
- LogisticRegression

**Project Features:**

- End-to-end ML pipeline
- SHAP explainability analysis
- Model benchmarking
- Threshold tuning
- Zindi submission generation

**Evaluation Metric:** Mean Absolute Error (MAE)

## Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- LightGBM
- CatBoost
- XGBoost
- SHAP
