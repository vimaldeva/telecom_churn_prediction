# 📡 Telecom Customer Churn Prediction

> Predict whether a telecom customer will **stay**, **churn**, or **rejoin** using a full ML/Deep Learning pipeline designed for insight, experimentation, and reproducibility.

![Domain](https://img.shields.io/badge/domain-telecom-blue)
![Python](https://img.shields.io/badge/python-3.9%2B-yellow)
![Status](https://img.shields.io/badge/status-active-brightgreen)

---

## 📝 Project Overview

Telecom operators fight churn every quarter. This repository demonstrates an end-to-end workflow that turns raw subscriber data into actionable churn predictions. You’ll find comprehensive exploratory data analysis, feature engineering best practices, and a model zoo ranging from traditional machine learning to an ANN baseline. All artifacts (plots, metrics, processed datasets) are saved for quick inspection and reproducibility.

---

## ✨ Highlights

### 📊 Exploratory Data Analysis
- Countplots, histplots, boxplots to study class imbalance, usage behaviour, and revenue patterns.
- Correlation heatmaps to uncover relationships among numerical features.

### 🧹 Feature Engineering & Preprocessing
- Removal of redundant / leakage columns.
- Binary & one-hot encoding for categorical variables.
- Imputation of null/default values.
- Min-max scaling / normalization of numeric features.

### 🤖 Model Benchmarks
- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Random Forest Classifier
- Artificial Neural Network (ANN)

### 📈 Evaluation & Reporting
- Confusion matrices and ROC curves saved per model.
- Precision, Recall, F1-score, and Accuracy compared across models.
- Aggregated metrics in CSV plus comparison visualization.

---

## 🧭 Workflow

1. **Understand Data** – Load raw `telecom_customer_churn.csv` and study metadata via `telecom_data_dictionary.csv`.
2. **EDA** – Generate visualizations (class balance, revenue distribution, tenure trends, etc.).
3. **Preprocess** – Encode categoricals, handle missing values, normalize numeric fields, and export processed dataset.
4. **Modeling** – Train and evaluate multiple algorithms; tune basic hyperparameters.
5. **Evaluation** – Produce confusion matrices, ROC curves, and consolidated metrics.
6. **Insights** – Compare models and identify the best-performing approach for deployment/experimentation.

---

## 🧪 Model Evaluation Snapshot

| Model                  | Accuracy | Precision | Recall | F1-score |
|-----------------------|----------|-----------|--------|----------|
| Logistic Regression    | …        | …         | …      | …        |
| SVM                    | …        | …         | …      | …        |
| KNN                    | …        | …         | …      | …        |
| Random Forest          | …        | …         | …      | …        |
| ANN                    | …        | …         | …      | …        |

> Replace the ellipses with actual numbers from `metrics/model_metrics.csv`.

---
