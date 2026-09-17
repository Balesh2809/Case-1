This project is part of the Machine Learning Essentials CA1.

The objective of this case study is to predict whether a patient will be readmitted to the hospital within 30 days using patient-related features.

The machine learning algorithm used is Logistic Regression with L2 Regularization.

Target Variable
0 → No readmission within 30 days
1 → Readmission within 30 days
The model is evaluated using classification metrics, ROC-AUC, a confusion matrix, and a hypothetical clinical cost analysis of false negatives and false positives.

🎯 Objectives
The main objectives of this project are:

Load and explore the patient dataset.
Handle missing values.
Encode categorical variables.
Standardize numerical features.
Split the dataset into training and testing sets.
Train a Logistic Regression model.
Apply L2 regularization.
Evaluate the model using Accuracy, Precision, Recall, F1 Score and ROC-AUC.
Analyze the Confusion Matrix.
Compare the hypothetical costs of False Negatives and False Positives.
Demonstrate classification threshold adjustment.
📂 Project Structure
Case_Study_1_Hospital_Readmission/
│
├── casestudy1.ipynb
├── dibetic_data.csv
└── README.md
