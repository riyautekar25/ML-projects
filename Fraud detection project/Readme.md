# 💳 Credit Card Fraud Detection Using Machine Learning

This project aims to detect fraudulent credit card transactions using various machine learning algorithms. The dataset used is sourced from Kaggle and includes features such as transaction type, amount, location, and user demographics.

## 📁 Dataset

- **Source**: [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets)
- **Files Used**:
  - `fraudTrain.csv`
  - `fraudTest.csv`
- **Target Column**: `is_fraud` (1 = Fraudulent, 0 = Legitimate)

## 🛠️ Features

- Transaction time & location features
- Transaction category and merchant details
- User demographic info (e.g., gender, job, state)

## 📊 Project Pipeline

1. **Data Loading & Cleaning**
2. **Feature Engineering**
   - Extracted hour, weekday, etc. from timestamp
   - Encoded categorical variables
   - Dropped irrelevant columns
3. **Model Training**
   - Logistic Regression
   - Random Forest
   - XGBoost
   - Support Vector Machine (SVM)
4. **Evaluation**
   - Classification Report (Precision, Recall, F1-Score)
   - ROC Curve
   - AUC Comparison

## 🧪 Evaluation Metrics

| Model              | ROC-AUC Score |
|--------------------|---------------|
| Logistic Regression| 0.993759      |
| Random Forest      | 0.971908      |
| XGBoost            | 0.833640      |

## 📈 Visualization

- Confusion Matrix
- ROC Curves for all models
- Comparison chart of model performances
