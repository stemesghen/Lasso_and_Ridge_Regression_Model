# Surrogate Modeling with Lasso and Ridge Regression

This project demonstrates how surrogate models can be constructed using Lasso and Ridge regression. The approach includes hyperparameter tuning, model evaluation using different data splits, and performance comparison. The original dataset used for this analysis is no longer included in the repository.

## Project Objectives

- Implement surrogate models using Lasso and Ridge regression.
- Tune regularization hyperparameters (`alpha`) using grid search.
- Evaluate models using:
  - Train-test split
  - The complete dataset
- Compare model performance based on accuracy metrics.

## Key Features

- Uses `GridSearchCV` from scikit-learn for efficient hyperparameter tuning.
- Evaluates models using R² scores to assess prediction accuracy.
- Compares the effects of L1 (Lasso) and L2 (Ridge) regularization:
  - Lasso performs feature selection by setting some coefficients to zero.
  - Ridge shrinks coefficients while keeping all features.

## Dataset

The dataset originally used in this project was removed and is no longer included in this repository. However, the code is fully reusable with any structured tabular dataset suitable for regression modeling.

## Files

- `surrogate_modeling.ipynb`: Jupyter Notebook containing all code for modeling, tuning, and evaluation.
- `README.md`: Project documentation (this file).

## Requirements

- Python 3.7 or higher
- `scikit-learn`
- `numpy`
- `matplotlib` (optional)



