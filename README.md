# Predictive Data Analytics – Loan Approval Classification

This repository contains an implementation of a binary classification project for automating loan approval decisions.
The analysis is implemented in a Jupyter notebook (`main.ipynb`) and follows a standard predictive analytics workflow:
data exploration, Analytic Base Table (ABT) construction, preprocessing, feature engineering, model training, and evaluation.

## Overview

Two supervised learning models are used and compared:

- Logistic Regression (baseline)
- Decision Tree Classifier (with tuned depth)

The data pipeline includes imputation for missing values, one-hot encoding for categorical features,
scaling for numeric variables where appropriate, and Synthetic Minority Over-sampling Technique SMOTE for class imbalance handling.

## Project Structure
```
├── main.ipynb
├── requirements.txt
├── Dataset/              
└── README.md
```
The notebook cells load the dataset, build the ABT, run the preprocessing and feature engineering,
fit the models, and report metrics (accuracy, precision, recall, F1-score, confusion matrix).

## Reproducibility

- Dependencies are listed in `requirements.txt`.

## License

MIT License.
