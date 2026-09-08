# DecodeLabs Project 2 — Fraud Detection

This project focuses on building a machine learning pipeline to identify potentially fraudulent transactions.

I worked with a highly imbalanced transaction dataset and explored different techniques to prepare the data, handle class imbalance, build classification models, and evaluate their performance.

## Project Overview

The main goal was to develop a reliable fraud detection model while paying particular attention to fraudulent transactions, which represented a small portion of the dataset.

The project includes:

- Data exploration and preprocessing
- Handling class imbalance using SMOTE
- Logistic Regression
- Random Forest
- Hyperparameter tuning using GridSearchCV
- Model comparison
- Confusion Matrix and Classification Report
- ROC Curve and ROC-AUC evaluation
- Feature importance analysis
- Final model selection

## Dataset

The dataset contains:

- 5,000 transaction records
- 35 features
- 4,881 non-fraudulent transactions
- 119 fraudulent transactions
- Fraud rate: 2.38%

## Models Used

### Logistic Regression

Used as a baseline classification model for identifying fraudulent transactions.

### Random Forest

Used to capture more complex relationships between transaction characteristics and fraud.

Random Forest was further optimized using GridSearchCV with StratifiedKFold cross-validation.

## Results

The models were evaluated using Precision, Recall, and ROC-AUC.

| Metric | Logistic Regression |
|---|---:|
| Precision | 1.00 |
| Recall | 1.00 |
| ROC-AUC | 1.00 |

The final model selected by the project pipeline was **Logistic Regression**.

## Feature Analysis

The feature importance analysis highlighted several transaction-related variables, including:

- Previous Orders
- Transaction Hour
- Velocity Score
- IP Risk Score
- Account Age
- Shipping Distance
- Device Risk Score
- Failed Transactions
- Distance from Billing Address
- Card Age

## Tools & Technologies

Python, Pandas, NumPy, Scikit-learn, Imbalanced-learn, Matplotlib, Seaborn, Jupyter Notebook, and Google Colab.

## Google Colab

[Open the project in Google Colab](https://colab.research.google.com/drive/1Jk3YlJ1fU5-NkOXWYWBBWjnw3h38jN-v?usp=sharing)

## What I Learned

This project helped me gain practical experience in handling imbalanced datasets, applying SMOTE, comparing classification models, tuning model parameters, and selecting appropriate evaluation metrics for fraud detection.

## Internship

This project was completed as part of my **Data Science Internship at DecodeLabs**.
