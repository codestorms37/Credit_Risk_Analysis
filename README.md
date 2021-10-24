# Credit_Risk_Analysis

## Overview

The purpose of the analysis is to compare different techniques to asess credit card risk, wich is inherently an unbalanced clasification problem

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


### Resampling Models to Predict Credit Risk



Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
