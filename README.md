# credit-risk-analysis
Credit risk prediction using a Random Forest classifier to identify likely loan defaults. Includes data cleaning, feature engineering, model training, and performance evaluation (accuracy, ROC-AUC).
# Credit Risk Prediction & Classification

## Project Overview

This project develops machine learning models to predict whether a credit-card customer will default on their payment in the following month.

The analysis uses the UCI Default of Credit Card Clients dataset, containing 30,000 customer observations and 23 predictor variables covering credit limits, demographic characteristics, repayment history, bill amounts and payment amounts.

## Objective

- Predict next-month credit-card payment default
- Compare Logistic Regression and Random Forest
- Evaluate model performance using precision, recall, F1-score and ROC-AUC
- Analyze classification threshold trade-offs
- Identify important predictors of default

## Dataset

*Source:* UCI Machine Learning Repository  
*Dataset:* Default of Credit Card Clients

- 30,000 observations
- 23 predictor variables
- Target: default payment next month

## Models

### Logistic Regression

Used as an interpretable baseline classification model.

### Random Forest

Used to capture non-linear relationships between customer characteristics and default risk.

## Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC

Particular attention was given to the default class because false-negative predictions can be important in credit-risk applications.

## Key Findings

Random Forest achieved higher ROC-AUC and better default-class recall than Logistic Regression, despite having lower overall accuracy.

The analysis also examined classification thresholds to understand the trade-off between precision and recall.

## Tools

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
