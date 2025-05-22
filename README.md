# Credit Default Prediction

This project analyzes the UCI Credit Card dataset to predict whether customers will default on their payments. It includes data exploration, preprocessing, and classification using four different algorithms.

## Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)
- **Records**: 30,000
- **Features**: 23 (including demographic, payment history, bill amount, and payment amount)

## Features Used

- LIMIT_BAL: Credit limit
- SEX, EDUCATION, MARRIAGE, AGE
- PAY_0 to PAY_6: Payment history
- BILL_AMT1 to BILL_AMT6: Bill statements
- PAY_AMT1 to PAY_AMT6: Amounts paid

## Process

1. Exploratory Data Analysis (EDA)
2. Data preprocessing (null values, encoding, scaling)
3. Train-test split
4. Model training & evaluation:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Multi-Layer Perceptron (MLP)
   - LightGBM

## Evaluation

- Accuracy score
- Confusion Matrix
- Classification Report

## Results

LightGBM provided the highest accuracy among the tested models. Evaluation metrics and visuals are included in the notebook.

## Requirements

- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- lightgbm
![Proje Ekran Görüntüsü](https://github.com/user-attachments/assets/8e33b8b1-6e34-40af-bfaa-b4984e064cb0)
Install dependencies:

```bash
pip install -r requirements.txt

