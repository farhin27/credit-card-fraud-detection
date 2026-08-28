# Credit Card Fraud Detection

## Overview

This project develops a machine learning pipeline to detect fraudulent
credit card transactions.

The project focuses on exploratory data analysis, data preprocessing,
classification model development, and evaluation using metrics suitable
for an imbalanced dataset.

## Dataset

The project uses the Credit Card Fraud Detection dataset available on Kaggle.

Dataset:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

1. Dataset exploration
2. Exploratory Data Analysis
3. Data preprocessing
4. Train-test split
5. Feature scaling
6. Logistic Regression
7. Random Forest
8. Model comparison
9. Confusion matrix analysis

## Models

### Logistic Regression

Used as a baseline classification model with balanced class weights.

### Random Forest

Used as a tree-based classification model with balanced class weights.

## Evaluation Metrics

The models were evaluated using:

- Precision
- Recall
- F1-score
- ROC-AUC

These metrics were selected because the dataset contains a highly
imbalanced distribution between legitimate and fraudulent transactions.

## Results

| Model | Precision | Recall | F1 Score | ROC-AUC |
|---|---:|---:|---:|---:|
| Logistic Regression | 6.10% | 91.84% | 11.44% | 97.22% |
| Random Forest | 96.05% | 74.49% | 83.91% | 95.29% |

Random Forest provided a better balance between precision and recall
in this experiment, while Logistic Regression achieved higher recall.

## Conclusion

The project demonstrates an end-to-end machine learning workflow for
fraud detection and highlights the importance of using appropriate
evaluation metrics when working with highly imbalanced classification data.
