# Machine Learning

Machine learning is a field of artificial intelligence that provides systems the ability to automatically learn and improve from experience without being explicitly programmed.

Following are types of machine learning:

- Classification
- Regression
- Linear Regression
- Logistic Regression
- Decision Tree
- K-Nearest Neighbors
- Support Vector Machines
- Naive Bayes
- Artificial Neural Networks
- Reinforcement Learning
- Robotics
- and many more

## Regression

Regression is a statistical technique used to model the relationship between a scalar response and one or more explanatory variables.

A regression model is used to predict the value of a scalar response variable based on one or more explanatory variables. The label or response variable is called the dependent variable and the explanatory variables are called the independent variables. The lable data type should be numeric.

## Classification

Classification is a statistical technique used to model the relationship between a scalar response and one or more explanatory variables.

A classification model is used to predict the category of the dependent variable (or class) based on one or more explanatory variables.

Examples of Classification

- Iris Flower Classification
- Breast Cancer Classification
- Diabetes Classification
- Heart Disease Classification
- Customer Churn Classification

Examples of Regression

- House Price Prediction
- Stock Price Prediction
- Sales Prediction
- Blood Pressure Prediction
- Temperature Prediction
- Salary Prediction

### Linear Regression

Linear regression is used to model the relationship between a scalar response and one or more explanatory variables.
In other words the trend line must in be in one direction that is called linear.

Type of Linear Regression

- Simple Linear Regression
- Multiple Linear Regression
- Polynomial Linear Regression

Definition of simple linear regression:

Simple linear regression is used to estimate the relationship between two quantitative variables. You can use simple linear regression when you want to know:

How strong the relationship is between two variables (e.g., the relationship between rainfall and soil erosion).
The value of the dependent variable at a certain value of the independent variable (e.g., the amount of soil erosion at a certain level of rainfall).

Formula of simple linear regression:

y = mx + b

Y is the dependent variable
X is the independent variable
m is the slope
b is the y-intercept where x is 0

You can write this formula in the form of y = b0 + b1x

Fit the line of equation

The distance between predicted line and orignal line is called error. Also called residual. It should be minimal.
We will get negative and positive values and we can't do culculations. so we do square of it. so call sqare sum. or square average.

MSE: Mean Square Error
is the average of square of the residuals

RMSE: Root Mean Square Error

is the square root of average of square root of the variance of the residuals.

Coefficient of determination or R-squared R2:
R-squared is a statistical measure of how close the data are to the fitted regression line. It always be between 0 and 1. Where 0 means no correlation and 1 means 100% correlation or best fit.

R2 = 1 - (SSR/SST)

SSR = sum of square of residuals
SST = sum of square of total

Simple Linear Regression Assumptions

- Linearity of residual
- Normality of residual Normal distribution
- Independence of residual

it must have single x and y

### Logistic Regression

Logistic regression is used to model the relationship between a binary response and one or more explanatory variables.

It is only kind of regression that is used to predict categorical data.

example of logistic regression (binary)

- Male / female
- Yes / No
- Positive / Negative

Multiple class logistic regression

- Red / Green / Blue
- London / Paris / London
- Spam / Ham / Spam

Multi label classification
Movie Animal

- English
- Action
- Drama
- Comedy

Linear x (many x1, x2, ... xn) create or output y (single y)

Prediction is based on probability from 0 to 1. where 0 is the lowest probability and 1 is the highest

S or Sigmiod function helps to make prediction

Evaluation metrix for regression

- MSE
- RMSE
- R2
- MAE (mean absolute error)

Evaluation metrix for classification

- Accuracy score 
- Precision score
- Recall score
- F1 score
- Confusion matrix

