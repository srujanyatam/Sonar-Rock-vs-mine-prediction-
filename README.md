**Rock vs Mine Prediction using Logistic Regression**

Introduction

This code is a Python implementation of a Rock vs Mine prediction model using Logistic Regression. The model is trained on a dataset of sonar signals and predicts whether a given signal corresponds to a rock or a mine.

Dataset

The dataset used in this code is a CSV file named "Copy of sonar data.csv" which contains 60 features and a target variable indicating whether the signal is a rock (R) or a mine (M).

Code Overview

The code consists of the following steps:

Importing necessary libraries (NumPy, Pandas, Scikit-learn)
Loading the dataset and exploring its structure and statistical properties
Separating the data into features (X) and target variable (Y)
Splitting the data into training and testing sets
Training a Logistic Regression model on the training data
Evaluating the model's accuracy on the training data
Making a prediction on a new input signal
Printing the prediction result (Rock or Mine)
How to Use

To use this code, simply run it in a Python environment with the necessary libraries installed. Make sure to replace the file path in the pd.read_csv function with the actual path to your dataset file.

Input Format

The input signal should be a tuple or list of 60 numerical values, representing the sonar signal features.

Output

The output will be a string indicating whether the input signal corresponds to a Rock or a Mine.
