# 📊 Financial Risk Profile Prediction

A comprehensive machine learning pipeline for predicting the **financial risk profile** of individuals based on diverse demographic, economic, behavioral, and financial features.

---

## 🚀 Project Overview

This project aims to build a **multi-class classification model** that categorizes individuals into one of three risk profiles:
- **0 – Low Risk**
- **1 – Medium Risk**
- **2 – High Risk**

The solution is designed with end-to-end data science best practices:  
✅ Data preprocessing · ✅ Feature engineering · ✅ Model training · ✅ Evaluation · ✅ Interpretability

---

## 🧠 Problem Statement

In the financial sector, identifying a client's risk category is crucial for:
- Credit Approval
- Insurance Underwriting
- Investment Planning

This project builds a model that predicts a user's **Risk Profile** using over **45+ input features** from personal, behavioral, and economic data.

---

## 📁 Dataset Description

The dataset contains `100,000` samples and `48` columns.

### 📌 Key Feature Categories:

- **Demographics:** Age, Gender, Marital Status, Dependents  
- **Financials:** Income Level, Credit Score, Monthly Expenses, Debt-to-Income Ratio  
- **Behavioral:** Risk Tolerance, Long-term Goals, Emergency Fund  
- **History & Stability:** Bankruptcy, Job Loss, Residency Stability  
- **Macro Economic:** Unemployment Rate, Inflation Rate, Interest Rates  
- **Health & Insurance:** Health History, Insurance Adequacy  

---

## 🔧 Tech Stack

| Tool / Library      | Role                            |
|---------------------|---------------------------------|
| `Pandas`            | Data manipulation               |
| `Seaborn`, `Matplotlib` | EDA & Visualizations       |
| `scikit-learn`      | Preprocessing & Metrics         |
| `XGBoost`           | Classification Model            |
| `SHAP`              | Model Explainability            |

---

## 📂 Project Structure

```bash
📦 Financial-Risk-Prediction/
├── notebook.ipynb             # Main Jupyter Notebook
├── cleaned_data.csv           # Processed dataset (optional)
├── model.pkl                  # Trained model (optional)
├── README.md                  # Project documentation
└── requirements.txt           # Libraries and dependencies


## 📎 Additional Information

As an enhancement to the standard training workflow, an additional module named `automated_model_trainer.py` has been added to the project.

This script is designed to **evaluate and compare multiple classification models** including:

- ✅ XGBoost
- ✅ Random Forest
- ✅ Support Vector Machine (SVM)
- ✅ Logistic Regression (optional extension)

🔍 The pipeline:
- Preprocesses the data using appropriate encoders and scalers
- Trains each model individually
- Evaluates them on a held-out test set using **accuracy** and **precision**
- Automatically identifies and logs the **best-performing model** based on evaluation metrics

This allows for better **model benchmarking** and ensures the most optimal model is selected for the problem at hand.
