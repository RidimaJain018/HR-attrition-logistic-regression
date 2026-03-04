Employee Attrition Prediction using Logistic Regression<br><br>

Overview<br>
This project builds a Logistic Regression model to predict employee attrition using an HR analytics dataset. The goal is to identify factors that influence whether an employee is likely to leave the organization.<br>
The original dataset contains 4410 rows and 551 features, which were processed, cleaned, and reduced through feature engineering and preprocessing to improve model efficiency and interpretability.<br><br>

Dataset
The project uses an HR analytics dataset combined with attendance-related features.<br>

Key characteristics:<br>
  Original shape: 4410 × 551<br>
  Target variable: Attrition (Yes / No)<br><br>
  Data preprocessing:<br>
    Handling missing values<br>
    Feature engineering from attendance data<br>
    Encoding categorical variables<br>
    Scaling numerical features<br><br>
Example features used in the model:<br>
  Business Travel<br>
  Department<br>
  Marital Status<br>
  Job Role<br>
  Monthly Income<br>
  Work-life Balance<br>
  Attendance patterns<br>
  Average work hour<br><br>

Machine Learning Model<br>
The project implements Logistic Regression using Scikit-Learn.<br>

Pipeline Components<br>
  The ML pipeline includes:<br>
    Data preprocessing<br>
    Feature scaling<br>
    Categorical encoding<br>
    Logistic Regression classifier<br><br>
  Libraries used:<br>
    pandas<br>
    numpy<br>
    scikit-learn<br>
    matplotlib<br>
    seaborn<br><br>

Model Evaluation<br>
The model was evaluated using:<br>
  Accuracy<br>
  Classification Report<br>
  Confusion Matrix<br>
  ROC-AUC Score<br>


