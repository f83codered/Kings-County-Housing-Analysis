![Image Title](images/kc_house.jpeg)

# Kings County House Price Analysis

**Author**: Filippe Fontenele

## Overview

This project aims to build a model that assists homeowners and real estate agents in identifying key components to add value to their homes while selling. To achieve this, we will analyse data from the King County House Sales dataset using multiple linear regression. The model will examine how renovating different components of a home will impact overall sales and help users make informed decisions.

***

## Business Problem

Homeowners and real estate agents need help to increase home sales profitability. We'll use King County House Sales data to identify renovation opportunities that can raise overall home prices. This info is useful in fluctuating markets to help homeowners and agencies maximize profits.


***

## Data

The dataset contains information about houses in King County, Washington. The data includes various attributes of the houses, such as the number of bedrooms and bathrooms, square footage, and other features that may influence the sale price of the house. The dataset also includes the sale price, which is the target variable that we will use to build a predictive model.
 

***

## Methods

After obtaining the dataset, the data was scrubbed by selecting the most relevant features that would impact house prices. This involved reducing the original predictors, since as many of the features were found to have non-statistically significant and unreliable coefficients. To further improve the model's performance and meet the assumptions of linear regression, the target variable `price` was log-transformed. This helped address issues with the original model. By carefully selecting the most impactful features and transforming the target variable, the final model was able to provide more reliable and accurate predictions of house prices.

***

## Results


We went through 3 models and results show:

- Increase square footage of your living space to maximise price
- Investment in keeping the construction and design of the house up to date to achieve an excellent grade
- As your property grows in space, invest in more bathrooms

***

***



## Conclusions

After this thorough analysis, we can conclude that increasing the square footage of the living space of a property should be priority number one for sellers. It is intuitive, since bigger houses yield higher prices. And with that, comes another conclusion that, although unexpected, it is not fully a surprise. The number of bathrooms plays a bigger role on your house price than your bedrooms. It would be a good idea considering adding extra bathrooms when and where possible once putting a house in the market.
And since King County has a grading system, homeowners should keep their assets up-to-date with current designs and construction codes to have better outcomes when putting their houses in ther market.

***