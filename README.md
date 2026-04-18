# Breast Cancer Classification

## Problem Statement
Predict whether a tumor is Malignant or Benign based on cell nucleus features.

## Dataset
- UCI Breast Cancer Wisconsin Dataset (built into sklearn)
- 569 samples, 30 features

## Models Used
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Naive Bayes

## Highlights
- Exploratory Data Analysis with correlation heatmap
- StandardScaler applied to all models
- Confusion Matrix + Precision, Recall, F1-Score
- 5-Fold Cross Validation

## Result
| Model | Accuracy |
|---|---|
| KNN | ~92% |
| Logistic Regression | ~95% |
| Naive Bayes | ~94% |

## Tools & Libraries
Python, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn
