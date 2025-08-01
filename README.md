# Credit Risk Prediction

This project predicts credit risk using historical loan application and credit behavior data. After preprocessing and feature engineering, we applied Decision Tree and Random Forest models.

## Dataset

- `application_record.csv`
- `credit_record.csv`

## Models & Results

| Model         | Accuracy | F1-score (Class 1) | ROC AUC |
|---------------|----------|--------------------|---------|
| Decision Tree | 98.15%   | 0.25               | 0.71    |
| Random Forest | 98.24%   | 0.24               | 0.77    |

Random Forest slightly outperformed in ROC AUC, making it better for identifying high-risk borrowers.

## Tools

- pandas, numpy, scikit-learn, matplotlib, seaborn

[View Notebook](https://nbviewer.org/github/shivar25/credit-risk-repository/blob/main/credit_risk_prediction%20.ipynb)
