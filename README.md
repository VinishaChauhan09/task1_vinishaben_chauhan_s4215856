# Case Studies in Data Science – Individual Task 1

This repository contains the machine learning analysis used for Part 1.3 of Individual Task 1.

## Datasets

### Heart Disease
Source: UCI Machine Learning Repository  
https://archive.ics.uci.edu/dataset/45/heart+disease

The dataset contains 303 observations and 13 predictor variables. The target was converted into a binary classification variable representing the presence or absence of heart disease.

### Diabetes 130-US Hospitals
Source: UCI Machine Learning Repository  
https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008

The dataset contains 101,766 hospital encounters and 50 original variables. The analysis predicts whether a patient is readmitted within 30 days.

## Machine Learning Models

Two classification algorithms were applied separately to both datasets:

- Decision Tree
- k-Nearest Neighbours (kNN)

## Evaluation Metrics

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion matrices

## Files

- `Heart_Disease_Analysis.ipynb` – Heart Disease preprocessing, modelling, evaluation and feature importance.
- `Diabetes_Analysis.ipynb` – Diabetes readmission preprocessing, modelling, evaluation and feature importance.

## Key Results

For the Heart Disease dataset, kNN achieved the strongest overall performance, including an accuracy of 0.885 and ROC-AUC of 0.953.

For the Diabetes dataset, kNN achieved high overall accuracy but very low recall for 30-day readmissions. The Decision Tree provided substantially higher recall and was therefore more useful for identifying potential early readmission cases.

## Author

Vinishaben Amitkumar Chauhan  
RMIT University  
Master of Data Science
