# Predict-Employee-Attrition
PROBLEM STATEMENT:
Predict Employee Attrition: Build a classification model to predict whether an employee
is likely to leave a company based on factors such as job satisfaction, salary, work
environment, and years of experience.






METHODOLOGY:
The dataset was first loaded and cleaned by removing any rows with missing values.
Key features selected for prediction were Job Satisfaction, Monthly Income, Years at Company, and Work-Life Balance.
Categorical data was encoded using Label Encoding to prepare it for machine learning.
The target variable, Attrition, was also encoded to binary form (Yes = 1, No = 0).
Data was split into training and testing sets using an 80-20 ratio.
A Random Forest Classifier was used for building the prediction model.
The model was trained on the training data and then tested on unseen data.
Predictions were evaluated using Accuracy, Precision, Recall, and a Confusion Matrix.
Seaborn and Matplotlib were used for visualization of the confusion matrix.

![Screenshot (246)](https://github.com/user-attachments/assets/03696a9c-865a-4e09-81e9-bfd37645e272)
