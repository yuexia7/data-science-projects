# Medical Insurance Cost Prediction with Multiple Linear Regression Model

## Basic information about the Medical Insurance Cost Dataset

This dataset shows the records of medical insurance charges for different people with various conditions. It contains 7 variables including the person’s age, gender, BMI, the number of children they have, smoking status, region, and the charges of the insurance. The variable BMI indicates Body Mass Index, which can be used to measure a person’s health condition. If BMI is over 30, the person is considered obese and have higher risk for heart disease, stroke, diabetes etc.

## Multiple regression algorithm

The purpose of this project is to understand the dataset, analyse the relationship between the independent variables (age, sex, BMI, children, smoker, region) and the dependent variable (charge), and find out the main factors that affect the medical insurance charges.

1. Split the X set and y set into training part and testing part for later training the regression model. Split 80% of the data for the training set while 20% of the data for testing set.
2. Create a linear regression model and put multiple independent variables, so it becomes multiple linear regression.
3. Use the model to predict how the values will be at the end.
4. Use R2, MAE, MSE, RMSE to evaluate the model.
   - Method 1 - use all independent variables
   - Method 2 - used nested method
   - Method 3 – used selected independent variables
