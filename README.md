# Titanic-task-2
Titanic Dataset Analysis with Logistic Regression
This script demonstrates the application of logistic regression to predict survival on the Titanic. The data preprocessing and modeling steps utilize the pandas, numpy, and scikit-learn libraries.

Overview
This Python script loads the Titanic dataset using pandas. It performs data preprocessing by dropping irrelevant columns and handling missing values in 'Age' and 'Fare'. Additionally, it encodes the 'Sex' column using label encoding. The data is split into training and testing sets using train_test_split from sklearn.model_selection.

Script Overview
The Python script follows these key steps:

Data Loading: Loads the Titanic dataset using pd.read_csv.
Data Preprocessing:
Drops unnecessary columns: 'PassengerId', 'Name', 'Ticket', 'Cabin', 'Embarked'.
Handles missing values in 'Age' and 'Fare' by filling with the mean.
Encodes the 'Sex' column using LabelEncoder.
Data Splitting: Splits the dataset into training and testing sets using train_test_split.
Data Scaling: Utilizes StandardScaler to scale the features.
Model Training: Applies logistic regression from sklearn.linear_model on the training data.
Model Evaluation: Predicts survival on the test set and calculates accuracy and classification report using accuracy_score and classification_report from sklearn.metrics.
Usage
To use this script:

Ensure the 'Titanic-Dataset.csv' file is in the same directory.
Execute the Python script in an environment with pandas, numpy, and scikit-learn installed.
Code
The script can be found in the titanic_logistic_regression.py file in this repository.

Results
The script outputs the accuracy of the logistic regression model and a detailed classification report
