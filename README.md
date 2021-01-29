# Seattle Housing Predictions
![alt text](https://github.com/alwaysongoogle247/housing_predictions/blob/main/images/house.jpg "Logo Title Text 1")
## Overview
Performed data cleaning, data analysis, feature engineering, feature selection and stats, to create a regression model that best predicted housing prices in Seattle, WA.

## Business Problem
For real estate agents to accurately predict the price of a home they must know what affects the price. 
In this project we are going to try and answer that.

Does the ratio of bedrooms to bathrooms affect the price?

Does square footage affect the price?

Or maybe if it has a basement or not? 

## Process
#### Explored Data
Cleaned data by scouring for missing values and dropping unwanted variables. In addition got acquainted with the data by performing statistical analysis to understand correlations between variables(features). 

#### Feature Engineering/Selection
Created features, dummy variables and interactions between binary features and continous ones to find features that affect the price

#### Create/Train Model
Utilized sklearn's linear regression library to train the model with selected features

#### Predict
Once the best model was picked the model was used to predict on a holdout

## Findings
It was found that the zipcode, condition and square footage were the biggest drivers of the price.
