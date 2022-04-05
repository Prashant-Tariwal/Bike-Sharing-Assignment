# Project Name
> Bike Sharing Assignment.
- Github link : https://github.com/Prashant-Tariwal/Bike-Sharing-Assignment

## Table of Contents
*  Objective
*  Conclusion
*  Dataset characteristics - day.csv have the following fields 
*  Step followed for case study
*  Data Cleaning
*  Exploratory data analysis. 
*  Rescaling the features
*  Model building
*  Model Comparison and insights
*  Final model interpretation
*  VALIDATE ASSUMPTIONS
*  Model Evaluation
*  Linear Regression Subjective Questions

## General Information
Understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

To understand which variables are significant in predicting the demand for shared bikes.
To understand how well those variables describe the bike demands.
To model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Conclusions
As per our final Model, the below predictor variables influences bike booking :

Temp (Temperature), Windspeed, Season_Summer, Season_Winter, Year_2019, Month_Sept
Weekday_Sunday, Workingday_Yes, Weather_Good/Clear, Weather_Moderate/Misty

## Technologies Used
import numpy as np
import pandas as pd
import warnings
warnings.filterwarnings('ignore')
import matplotlib.pyplot as plt
import seaborn as sns
import sklearn
import statsmodels.api as sm
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import MinMaxScaler
from sklearn.feature_selection import RFE
from sklearn.linear_model import LinearRegression
from statsmodels.stats.outliers_influence import variance_inflation_factor
from sklearn.metrics import r2_score


## Contact
Created by Prashant Tariwal    (prashanttariwal@gmail.com)