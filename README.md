# Advanced Regression Assignment
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

## Table of Contents
* Importing and understanding the data.
* Missing value treatment and outlier analysis.
* Exploratory data analysis to find out the inference about the data and its correlation with the target variables.
* Transformation of the target variable to handle the data skewness.
* Data preprocessing like Label encoding and creation of dummies.
* Test train split and Feature scaling
* Data modelling using RFE to identify the top 30 variables.
* Ridge and Lasso Regression to find the top feature variables and finding the optimal alpha value

## General Information
Steps followed to build this model:
- Importing Libraries
- Data Understanding
- Data Preparation
- Data Preprocessing
- Data Modeling
- Inference and Recommendation

## Business Objective:

- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions
Variables that are significant in predicting the price of a house:

- LotFrontage : If the house Linear feet of street connected to property area increase then the Price increase.

- BsmtFullBath : If the BsmtFullBath area is more the SalePrice is higher

- Overall Condition: If the Overall Condition is Excellent the SalePrice is higher

- MSZoning_RH : If the house is near residential area then the SalePrice is higher

- Overall quality: If the Overall Condition is Excellent the SalePrice is higher

- Exterior1st_CBlock : If the house Exterior1st is CBlock then price is less.

- Garage Area: If the Garage area is high the SalePrice is higher

- CentralAir: If the CentralAir is Yes the SalePrice is higher


## Technologies Used
- numpy - version 1.18.1
- pandas - version 1.0.1
- matplotlib - version 3.1.3
- seaborn - version 0.10.0
- statsmodels - version 0.11.0
- sklearn - version 0.22.1
- scipy - version 1.4.1


## Contact
Created by Manisha Jena[@manishajena25] - feel free to contact me!
