# Prediction-with-Machine-Learning-for-Economists-Course
Here you can find the description for Prediction-with-Machine-Learning-for-Economists-Course assignments

# Assingment #1

## Description

Build four predictive models using linear regression for earnings per hour.
1. Models: the target variable is earnings per hour, all others would be predictors.
2. Model 1 shall be the simplest, and model 4 the more complex. It shall be OLS. You shall 
explain your choice of predictors.
3. Compare model performance of these models (a) RMSE in the full sample, (2) cross-validated RMSE and (c) BIC in the full sample.
4. Discuss the relationship between model complexity and performance. You may use visual 
aids.

## Files:
1. Python code ('The Assignment 1_ wage_ occupation (1)')
2. Report ('Prediction with Machine Learning for Economists_Assignment 1')
   

## Data Source
The data for this analysis is taken from the Current Population Survey made by the US government to monitor the labour market.
There is a dataset which contains data collected from approximately 30,000 people (Feenberg, Daniel, and Jean Roth, 2007). 

## Technologies Used
Jupiter Notebook, Python

## Models
Log-Level
OLS FE
Models	Dependent variable	Predictors
Model_1	ln_earnings_per_hour 	female
Model_2	ln_earnings_per_hour 	female, age
Model_3	ln_earnings_per_hour 	female, age, Masters, PhD
Model_4	ln_earnings_per_hour 	female, age, Masters, PhD, Married, No_children
