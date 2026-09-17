# Credit Card Fraud Detection

## Objective

Detect fraudulent credit card transactions using machine learning.

## Model

XGBoost Classifier.

## Dataset

IEEE-CIS Fraud Detection Dataset.

## Problem

Credit card fraud detection is a highly imbalanced classification
problem where fraudulent transactions represent a small proportion
of total transactions.

## Preprocessing

- Missing value handling
- Feature selection
- Stratified train-test split
- Class imbalance handling using scale_pos_weight

## Evaluation

The model is evaluated using:

- ROC-AUC
- PR-AUC
- Precision
- Recall
- F1-score
- Confusion Matrix

## Business Considerations

False positives may cause legitimate transactions to be declined
or flagged unnecessarily.

False negatives allow fraudulent transactions to pass through,
potentially causing financial losses.

Therefore, threshold selection and recall/precision trade-offs are
important in fraud detection.
