# Titanic_survival_prediction
This is a basic Data Science project where we predict the survival of passengers aboard the Titanic using Machine Learning.

# Table of Contents
-Project Description
-Workflow
-Technologies Used
-How to Run
-Results
-Acknowledgements


# Project Description
This project aims to predict whether a passenger survived the Titanic disaster based on features such as age, sex, passenger class, etc. The entire analysis is done step-by-step using Python libraries and machine learning.


# Workflow
1. Importing Dependencies
Libraries used: NumPy, Pandas, Matplotlib, scikit-learn.

2. Data Collection and Processing
-> Loaded Titanic dataset from a CSV file into a pandas DataFrame.
-> Checked the number of rows and columns.
-> Used .info() method to understand the data better.
-> Identified and handled missing values.

3. Data Analysis
-> Generated statistical summaries using .describe().
-> Analyzed the number of passengers who survived and who did not.

4. Data Visualization
-> Created a count plot for the 'Survived' column.
-> Created additional count plots for survival based on gender and ticket class.

5. Data Preprocessing
-> Encoded categorical columns like 'Sex' and 'Embarked'.
-> Separated features and target variable ('Survived').
-> Split the dataset into training and testing sets.

6. Model Training
-> Trained a Logistic Regression model on the training data.

7. Model Evaluation
-> Evaluated the model on the test data.
-> Achieved an accuracy score of 1.0.


# Python Libraries Used:
- Pandas
- NumPy
- Matplotlib
- Scikit-learn


