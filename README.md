Employee Attrition Prediction using Logistic Regression
Overview
This project builds a Logistic Regression model to predict employee attrition using an HR analytics dataset. The goal is to identify factors that influence whether an employee is likely to leave the organization.
The original dataset contains 4410 rows and 551 features, which were processed, cleaned, and reduced through feature engineering and preprocessing to improve model efficiency and interpretability.

Dataset
The project uses an HR analytics dataset combined with attendance-related features.

Key characteristics:
  Original shape: 4410 × 551
  Target variable: Attrition (Yes / No)
  Data preprocessing:
    Handling missing values
    Feature engineering from attendance data
    Encoding categorical variables
    Scaling numerical features
Example features used in the model:
  Business Travel
  Department
  Marital Status
  Job Role
  Monthly Income
  Work-life Balance
  Attendance patterns
  Average work hours

Machine Learning Model
The project implements Logistic Regression using Scikit-Learn.

Pipeline Components
  The ML pipeline includes:
    Data preprocessing
    Feature scaling
    Categorical encoding
    Logistic Regression classifier
  Libraries used:
    pandas
    numpy
    scikit-learn
    matplotlib
    seaborn

Model Evaluation
The model was evaluated using:
  Accuracy
  Classification Report
  Confusion Matrix
  ROC-AUC Score


