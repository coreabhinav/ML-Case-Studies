# Hospital Readmission Prediction

## Objective

Predict whether a patient will be readmitted to the hospital within 30 days.

## Model

Logistic Regression with L2 Regularization.

## Dataset

Diabetes 130-US Hospitals Dataset.

## Features

The model uses patient demographics, diagnosis information,
vital/clinical information and previous healthcare utilization.

## Target

1 = Readmitted within 30 days

0 = Not readmitted within 30 days

## Preprocessing

- Missing value imputation
- Numerical feature standardization
- Categorical feature one-hot encoding

## Evaluation

The model is evaluated using:

- ROC-AUC
- Precision
- Recall
- F1-score
- Confusion Matrix

## Clinical Considerations

False negatives can be clinically important because a high-risk
patient may not receive additional monitoring or follow-up.

False positives can result in unnecessary monitoring and resource use.

Therefore, model threshold selection should consider the relative
clinical costs of false negatives and false positives.
