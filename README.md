# Hospital-readmission-case-study

Overview

This project predicts whether a patient will be readmitted to the hospital using Logistic Regression with L2 regularization.

Dataset

The project uses a hospital readmission dataset containing patient demographic, diagnosis, procedure, hospitalization, comorbidity, and discharge information.

Methodology

Data preprocessing
One-hot encoding of categorical features
Feature standardization
80/20 stratified train-test split
Logistic Regression with L2 regularization
ROC-AUC evaluation
Confusion matrix analysis
Classification threshold analysis
Results
ROC-AUC: 0.507

The model showed limited predictive discrimination on the selected dataset. Threshold analysis demonstrated the trade-off between false positives and false negatives.

Technologies

Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Google Colab
