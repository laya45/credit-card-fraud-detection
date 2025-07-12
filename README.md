# 💳 Credit Card Fraud Detection

Detect fraudulent credit card transactions using machine learning with real-world imbalanced data.

![fraud](https://img.shields.io/badge/fraud-detection-red)
![ML](https://img.shields.io/badge/Machine%20Learning-RandomForest-blue)
![status](https://img.shields.io/badge/status-Working-success)

---

## 📌 Project Description

This project uses the **Kaggle Credit Card Fraud Detection Dataset** to classify transactions as **legitimate** or **fraudulent**. It tackles:
- Class imbalance
- Feature scaling
- Model training and evaluation
- Confusion matrix & metrics (accuracy, precision, recall, F1)
- User prediction interface (optional)

---

## 📂 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 transactions
- 492 frauds (~0.17%)
- Features `V1` to `V28` are PCA components
- Class: `0` = Legitimate, `1` = Fraud

---

## 🧪 Features

- Preprocessing: handling nulls, scaling, class balance with SMOTE
- Classification Model: `RandomForestClassifier`
- Evaluation: Confusion Matrix, Accuracy, Precision, Recall, F1-score
- Visualization: Class distribution, PCA, heatmaps
- (Optional) User input & Streamlit integration
