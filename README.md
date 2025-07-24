# Credit Card Fraud Detection using Machine Learning

This project aims to detect fraudulent credit card transactions using a machine learning model. We use logistic regression for binary classification, with a focus on dealing with class imbalance and ensuring accurate detection of rare fraud cases.

---

## 🔍 Project Overview

- Load and preprocess the dataset
- Split data into training and testing sets
- Train a Logistic Regression model
- Evaluate performance using accuracy score
- Analyze fraud detection effectiveness

---

## 🧰 Tech Stack

- Python 3.x  
- NumPy  
- Pandas  
- Scikit-learn  

---

## 📊 Dataset

The dataset includes anonymized credit card transactions and a target variable indicating whether a transaction is fraudulent (1) or not (0).

- Features: V1, V2, ..., V28 (PCA-transformed), Time, Amount
- Target: `Class` (0 = legitimate, 1 = fraud)

You can find the dataset here: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

## 🚀 How to Run

1. **Clone the Repository**

```bash

