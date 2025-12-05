# 🫀 Heart Disease Prediction using Machine Learning (SVM & Logistic Regression)

This repository contains a machine learning project focused on predicting the presence of heart disease using two classification algorithms: **Support Vector Machine (SVM)** and **Logistic Regression**.

---

## Objectives

- Load and explore the dataset
- Preprocess the data
- Train models using SVM and Logistic Regression
- Evaluate model performance with:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix
- Visualize results and make comparisons

---

Dataset source: [Kaggle](https://www.kaggle.com/datasets/rishidamarla/heart-disease-prediction)

---

## Tech Stack

- **Programming Language**: Python
- **Libraries**:
  - `Pandas`, `NumPy` – Data manipulation
  - `Matplotlib`, `Seaborn` – Visualization
  - `Scikit-learn` – ML models and evaluation
- **Tools**: Jupyter Notebook

---

## Results

| Model               | Accuracy (Test) | Accuracy (Train) |
|--------------------|------------------|------------------|
| Logistic Regression| 81.96%           | 85.12%           |
| SVM (Linear Kernel)| 81.96%           | —                |

> Both models achieved similar test accuracy. Logistic Regression showed slightly better performance on training data. Future improvements can include hyperparameter tuning or using ensemble methods.

---

## Acknowledgements
UCI Machine Learning Repository
Kaggle Datasets
