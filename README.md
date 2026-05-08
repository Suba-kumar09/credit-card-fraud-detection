# Credit Card Fraud Detection 🔍

## Project Overview
A Data Science project using Machine Learning to detect fraudulent credit card transactions using Python.

## Dataset
- Source: Kaggle (mlg-ulb/creditcardfraud)
- Total Transactions: 2,84,807
- Fraud Cases: 492 (0.17%)
- Features: 30 (Time, V1-V28, Amount)

## Problem Statement
Credit card fraud causes billions in losses annually. 
This project builds a classifier to detect fraud even with severely imbalanced data.

## Technologies Used
- Python 3.14
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)

## Project Steps
1. Exploratory Data Analysis (EDA)
2. Data Visualization
3. Data Preprocessing & SMOTE
4. Model Building (Logistic Regression, Random Forest, XGBoost)
5. Model Evaluation

## Results
| Model | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| Logistic Regression | 0.06 | 0.92 | 0.11 |
| Random Forest | 0.82 | 0.82 | 0.82 |
| XGBoost | 0.73 | 0.89 | 0.80 |

## Best Model
✅ Random Forest with AUC = 0.969

## Key Findings
- Dataset is highly imbalanced (0.17% fraud)
- Used SMOTE to handle class imbalance
- V14 is the most important feature for fraud detection
- Random Forest achieved best F1-score of 0.82

## How to Run
pip install -r requirements.txt

jupyter notebook 01_eda.ipynb

## Author
Subashini K