# 🏦 Financial Inclusion in Africa - Predictive Modeling Project

This project builds a predictive machine learning pipeline to estimate the likelihood of individuals in East African countries (Kenya, Rwanda, Tanzania, Uganda) having access to a **bank account**.

It is based on the Zindi competition: [Financial Inclusion in Africa](https://zindi.africa/competitions/financial-inclusion-in-africa)

---

##  Problem Statement

**Goal:** Predict whether an individual has a bank account (0 = No, 1 = Yes), using demographic and socioeconomic data.

**Why it matters:** Access to financial services is a major factor in improving economic opportunities and human development. This model aims to assist in identifying underserved populations.

---

## Models Used

- `GradientBoostingClassifier` (Best performer, MAE: ~0.100)
- `XGBClassifier`
- `RandomForestClassifier`
- `LogisticRegression`

Ensembles and SHAP-based feature reduction were also explored.

---

## Features of the Project

- End-to-end ML pipeline (data cleaning → model evaluation → submission)
- SHAP explainability integration
- Threshold tuning to minimize MAE
- Benchmarking across models
- Custom test preprocessing to ensure train-test alignment
- Zindi-style submission generation

---


---

## 📈 Evaluation Metric

- **Mean Absolute Error (MAE)**  
This measures how often the predicted class differs from the true class (0 or 1).

---

## 🛠️ How to Run

1. Clone the repo or open the notebook
2. Install requirements:
   ```bash
   pip install -r requirements.txt


