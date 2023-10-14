# Rock-VS-Mine-Prediction
Rock VS Mine Prediction using Logistic regression 


# LOGISTIC REGRESSION
Binary Classification: Logistic regression is used for binary classification tasks with two possible outcomes.It predicts one of two possible outcomes (e.g., Yes/No) and provides probabilities instead of direct class labels.
Sigmoid Function: It employs a sigmoid function to model the probability of the binary outcome, producing values between 0 and 1. Instead of class labels, it predicts the probability of belonging to a specific class.
Use Case: Logistic regression is commonly used in various fields for tasks like disease prediction, customer churn, and credit risk assessment.


# STEPS FOR LINEAR REGRESSION MODEL (ROCK VS MINE PREDICTION)

# Importing Dependencies:
Importing necessary libraries such as NumPy, pandas, and scikit-learn for data manipulation, data analysis, and machine learning.

# Data Collection and Processing:
Loading a dataset (sonar data) into a pandas DataFrame. This dataset contains information about objects (sonar readings) and their labels (either "R" for Rock or "M" for Mine).
Displaying the first 5 rows of the dataset to understand its structure.
Checking the number of rows and columns in the dataset (208 rows and 61 columns).
Performing some basic statistical analysis on the dataset, such as mean, standard deviation, etc.
Counting the number of occurrences of "R" (Rock) and "M" (Mine) in the dataset.
Calculating the mean values of each column for "R" and "M" separately.

# Separating Data and Labels:
Separating the dataset into two parts: one containing the data (features) and another containing the labels (the "R" or "M" values). The features are stored in X, and the labels are stored in Y.
Training and Testing Data:

Splitting the data into training and testing sets using train_test_split. This split is stratified, which means it ensures an equal distribution of "R" and "M" labels in both the training and testing sets.
Printing the shapes of the entire dataset, training data, and testing data.

# Model Training - Logistic Regression:
Creating a logistic regression model using LogisticRegression().
Training the model using the training data with the fit method.

# Model Evaluation:
Calculating the accuracy of the model on both the training and testing data using accuracy_score. The accuracy on training data is approximately 83.4%, and the accuracy on test data is approximately 76.2%.

# Making a Predictive System:
Predicting the type ("R" or "M") of an object using a set of feature values. It takes some input data, reshapes it, and uses the trained model to make a prediction.
Printing the predicted label ("R" or "M") and providing a human-readable message indicating whether the object is a "rock" or a "mine" based on the prediction.
This code essentially builds and evaluates a machine learning model for classifying objects into "rock" or "mine" categories based on the given dataset and feature values.
