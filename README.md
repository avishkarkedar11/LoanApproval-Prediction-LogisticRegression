# CIE2 – Activity 2: Loan Approval Prediction using Logistic Regression

## Project Overview
This project uses Logistic Regression, a supervised Machine Learning algorithm, to predict whether a loan application will be Approved or Rejected.

## Objectives
- Understand Logistic Regression.
- Perform data preprocessing.
- Handle missing values.
- Encode categorical variables.
- Apply feature scaling.
- Train and test the model.
- Evaluate model performance.
- Predict loan approval for new applicants.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## Dataset
Dataset: Loan Prediction Dataset

File: `loandataset.csv`

Source: [Kaggle Loan Prediction Dataset](https://www.kaggle.com/datasets/ninzaami/loan-predication)

## Work Completed
- Dataset loading and exploration.
- Missing value handling.
- Categorical encoding.
- Feature scaling.
- Training and testing split (80:20).
- Logistic Regression model training.
- Loan status prediction.
- Confusion matrix.
- ROC curve.
- Actual vs Predicted graph.
- Loan status distribution graph.
- New applicant prediction.

## Model Evaluation Results

| Metric | Result |
|---|---:|
| Accuracy | 86.18% |
| Precision | 0.84 |
| Recall | 0.9882 |
| F1 Score | 0.9081 |
| ROC-AUC | 0.8523 |

## Decision Log
I selected a decision threshold of 0.50 because it helps identify most approved loan applications correctly. I focused on reducing false negatives so eligible applicants are not wrongly rejected.

## Conclusion
The Logistic Regression model achieved 86.18% test accuracy and successfully classified loan applications into Approved and Rejected categories.

## Repository Contents
- Jupyter Notebook
- Dataset
- README.md
- Confusion Matrix
- ROC Curve
- Actual vs Predicted Graph
- Loan Distribution Graph
- Decision Log

## Reference
[Complexiota](https://github.com/complexiota)