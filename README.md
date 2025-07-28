Overview
This project builds a machine learning pipeline to predict whether a loan applicant is a good or bad credit risk based on their financial and demographic data. It uses real-world datasets (application_record.csv and credit_record.csv) and demonstrates end-to-end ML development — from data preprocessing to model evaluation and deployment.

Model Highlights
Model Used: Random Forest Classifier

Accuracy Achieved: ~87%

AUC Score: 0.91

ROC Curve & Confusion Matrix: Visualized

Feature Importance: Interpreted and plotted

Dataset Info
application_record.csv: Contains applicant-level demographic and employment details

credit_record.csv: Contains monthly credit behavior records

Combined to build a binary target: Good (paid on time) or Bad (overdue ≥60 days)

Steps Performed
Data Cleaning & Merging

Feature Engineering

Handling Class Imbalance

Train-Test Split

Random Forest Model Training

Evaluation (Accuracy, Classification Report, ROC, AUC)

Feature Importance Analysis

Results
Model Type: Supervised Classification

Classifier Used: Random Forest

Best Performance:

Accuracy: 87%

AUC: 0.91

F1-Score: High on both classes

Project Notebook
Click here to view the full notebook with code and outputs

Requirements
bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Author
Shiva Ranjan

