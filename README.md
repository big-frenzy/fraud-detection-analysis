# Fraud Detection Notebook (Model Development)

This repository contains the exploratory and modelling work behind the deployed fraud detection decision-support system.

In this notebook you will find:
- Exploratory data analysis (EDA)
- Model training (Logistic Regression, Random Forest)
- Class imbalance handling
- Triage threshold design (ALLOW / REVIEW / BLOCK)
- Model explainability examples

This notebook is meant to document the thought process and experimentation that led to the deployed system.

---

## 🔗 Related Resources

- **Live demo:** 🔗 https://fraud-detection-decision-system.streamlit.app/
- **Deployed project (code + application):** 🔗 https://github.com/big-frenzy/fraud-detection-decision-system

---

## Dataset

The dataset used in this project is the **Credit Card Fraud Detection dataset** from Kaggle:

🔗 https://kaggle.com/datasets/mlg-ulb/creditcardfraud

The dataset contains anonymised transaction features (PCA-transformed), along with a `Class` label indicating fraud or normal transactions.

---

## Getting Started

To run this notebook locally:

1. Clone this repository
2. Install the required packages (e.g. `pandas`, `numpy`, `scikit-learn`)
3. Open `fraud.ipynb` in Jupyter
4. Run all cells top to bottom

---

## Notes

This notebook covers model development only — the interactive deployed system is in a separate repository linked above.
