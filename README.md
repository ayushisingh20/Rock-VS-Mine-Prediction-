# ROCK VE MIE PREDICTION
Rock VS Mine Prediction using Logistic regression 


# LOGISTIC REGRESSION

Binary Classification: Logistic regression is used for binary classification tasks with two possible outcomes.It predicts one of two possible outcomes (e.g., Yes/No) and provides probabilities instead of direct class labels.
Sigmoid Function: It employs a sigmoid function to model the probability of the binary outcome, producing values between 0 and 1. Instead of class labels, it predicts the probability of belonging to a specific class. 
Use Case: Logistic regression is commonly used in various fields for tasks like disease prediction, customer churn, and credit risk assessment.


# TYPES OF LOGISTIC REGRESSION 

1.Binary logistic regression: In this approach, the response or dependent variable is dichotomous in nature—i.e. it has only two possible outcomes (e.g. 0 or 1). Some popular examples of its use include predicting if an e-mail is spam or not spam or if a tumor is malignant or not malignant. Within logistic regression, this is the most commonly used approach, and more generally, it is one of the most common classifiers for binary classification.

2.Multinomial logistic regression: In this type of logistic regression model, the dependent variable has three or more possible outcomes; however, these values have no specified order.  For example, movie studios want to predict what genre of film a moviegoer is likely to see to market films more effectively. A multinomial logistic regression model can help the studio to determine the strength of influence a person's age, gender, and dating status may have on the type of film that they prefer. The studio can then orient an advertising campaign of a specific movie toward a group of people likely to go see it.

3.Ordinal logistic regression: This type of logistic regression model is leveraged when the response variable has three or more possible outcome, but in this case, these values do have a defined order. Examples of ordinal responses include grading scales from A to F or rating scales from 1 to 5. 


# LINERAR REGRESSION VS LOGISTIC REGRESSION

Linear Regression:
Task: Linear regression is used for predicting a continuous numeric outcome variable. It's suitable for regression problems, such as predicting prices, temperature, or sales figures.
Output: The output of linear regression is a real-valued number. It aims to model the relationship between the input features and the continuous target variable.
Hypothesis Function: Linear regression uses a linear hypothesis function that predicts a continuous value as a linear combination of input features.
Algorithm: Linear regression models are typically trained using techniques like ordinary least squares (OLS) to minimize the sum of squared errors.
Evaluation: Common evaluation metrics for linear regression include mean squared error (MSE), root mean squared error (RMSE), and R-squared (R2).
Decision Boundary: Linear regression does not have a decision boundary as it's not used for classification tasks.

Logistic Regression:
Task: Logistic regression is used for binary classification tasks, where the goal is to predict one of two possible outcomes (0 or 1). It's suitable for tasks like spam detection, medical diagnosis, and churn prediction.
Output: The output of logistic regression is a probability between 0 and 1, representing the likelihood of the sample belonging to the positive class.
Hypothesis Function: Logistic regression uses a sigmoid (logistic) function to model the probability of the positive class as a function of input features.
Algorithm: Logistic regression models are trained using maximum likelihood estimation (MLE) to maximize the likelihood of observing the data.
Evaluation: Common evaluation metrics for logistic regression include accuracy, precision, recall, F1 score, and the receiver operating characteristic (ROC) curve.
Decision Boundary: Logistic regression uses a linear decision boundary to separate data points of different classes. In two dimensions, this boundary is a straight line; in higher dimensions, it's a hyperplane.

# USE CASE OF LOGISTIC REGRESSION 

Fraud detection: Logistic regression models can help teams identify data anomalies, which are predictive of fraud. Certain behaviors or characteristics may have a higher association with fraudulent activities, which is particularly helpful to banking and other financial institutions in protecting their clients. SaaS-based companies have also started to adopt these practices to eliminate fake user accounts from their datasets when conducting data analysis around business performance.

Disease prediction: In medicine, this analytics approach can be used to predict the likelihood of disease or illness for a given population. Healthcare organizations can set up preventative care for individuals that show higher propensity for specific illnesses.

Churn prediction: Specific behaviors may be indicative of churn in different functions of an organization. For example, human resources and management teams may want to know if there are high performers within the company who are at risk of leaving the organization; this type of insight can prompt conversations to understand problem areas within the company, such as culture or compensation. Alternatively, the sales organization may want to learn which of their clients are at risk of taking their business elsewhere. This can prompt teams to set up a retention strategy to avoid lost revenue.
