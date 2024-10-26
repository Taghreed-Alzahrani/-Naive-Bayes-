# -Naive-Bayes-
project Title: Diabetes Prediction Using Gaussian Naive Bayes

Authors: 
Taghreed Alzahrani
Jori Bajahnoun

Date: 26/10/2024

Overview:
This project aims to predict whether a patient has diabetes based on various medical diagnostic measurements. The prediction model uses the Gaussian Naive Bayes algorithm, which is effective for classification tasks, especially with normally distributed data.

Included Files: Naive_Bayes_Classifier.ipynb: A notebook containing Python. Naive_Report.pdf: A report about the task. 

Dataset:
The dataset contains diagnostic measurements for female patients of Pima Indian heritage who are at least 21 years old. The goal is to predict whether or not a patient has diabetes based on specific medical predictor variables.

How to Install and Run the Project:
Prerequisites
Python: Version 3.6 or higher
Jupyter Notebook or Google Colab or any Python IDE

Installation Steps
Install Required Libraries: Use pip to install necessary libraries.
pip install pandas matplotlib scikit-learn

Download the Dataset: Obtain the dataset from https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database.
Save the dataset as diabetes.csv in the project directory.

Open the Project:

Jupyter Notebook: Open the notebook file.
Python IDE:
Open your preferred Python IDE.
Create a new Python file and copy the provided code into it.

Run the Code: Execute each cell sequentially to perform the following:
Load the dataset and display the first few rows.
Check the dataset information and drop any rows with missing values.
Define the feature set (X) and target variable (y).
Split the dataset into training and testing sets (80% training, 20% testing).
Create an instance of the Gaussian Naive Bayes model and fit it to the training data.
Predict outcomes for the test data and evaluate the model's performance using accuracy, F1 score, and a classification report.
Display a confusion matrix to visualize the classification results.
