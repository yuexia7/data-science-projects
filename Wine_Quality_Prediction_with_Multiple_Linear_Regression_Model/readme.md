# Wine Quality Prediction with Multiple Linear Regression Model

## Basic information of the Dataset

This data is about wine features and quality. It contains 1599 rows and 12 columns, which are fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, and quality. The quality is the target variable and the other 11 are independent variables.

## Purpose of the project

The purpose of analysing the wine dataset is to find the main factors that affects the wine quality. It will provide people with good insights about how wine features affect the quality. According to the original dataset, the quality level is from 0 to 10, and the higher the value is, the better the quality.

## Finding the correlation between independent and dependent variables

The correlation between two variables should be 0\~1 or -1\~0. The value 0 means these two variables are not correlated, and value 0.5 means a moderate positive correlation. The value around 0.9 means strong positive correlation and value 1 means perfect relative with each other.

According to the analysis, the correlation between alcohol and quality is 0.5, and the correlation between sulphates and quality are 0.41. These two features have the highest correlation values among all, so alcohol and sulphates are more relevant to affect the target value. When the value of sulphates or alcohol increase, the target value quality would increase as well.
