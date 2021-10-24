# Credit_Risk_Analysis

## Overview

The purpose of the analysis is to compare different techniques to assess credit card risk, which is inherently an unbalanced classification problem

### Tools

- Jupyter notebook
- Python:
  - numpy
  - pandas
  - pathlib
  - collections
  - imbalanced-learn
  - scikit-learn

## Results

- Six techniques were explored:
  - Logistic Regression resampling with:
    - Naive Random Oversampling
    - SMOTE Oversampling
    - Cluster Centroids Undersampling
    - SMOTEENN (Over and Under) Sampling
  - Ensemble algorithms:
    - Random Forest
    - AdaBoost

### Logistic Regression resampling

#### Naive Random Oversampling

![Naive Random](./resources/images/Naive_Random.png)

#### SMOTE Oversampling

![SMOTE](./resources/images/SMOTE.png)

#### Cluster Centroids Undersampling

![undersampling](./resources/images/undersampling.png)

#### SMOTEENN (Over and Under) Sampling

![SMOTEENN](./resources/images/SMOTEENN.png)

### Ensemble algorithms

#### Random Forest

![balanced_random_forest.png](./resources/images/balanced_random_forest.png)

#### AdaBoost

![AdaBoost](./resources/images/AdaBoost.png)

### Resume

![resume](./resources/images/resume.png)

- AdaBoost seems to be the best alternative as:
  - It has the best Balanced Accuracy
  - Precision (TruePositive / (TruePositive + FalsePositive)) for high-risk cases is higher
  - And most important for this case of credit risk, Recall (TruePositive / (TruePositive + FalseNegative)) is higher

## Summary

- From this analysis the AdaBoost algorithm is recommended to assess credit risk as it has better performance in all three critical indicators: Balanced Accuracy, Precision and Recall.
