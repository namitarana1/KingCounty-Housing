# Real Estate Analysis: King County

Top features that contribute to housing sale prices.

## Home Prices Analysis King County, Washington
**Authors:** Namita Rana, Jeremias Campos, Jose Harper

## Introduction
We were hired to predict the best attributes that influence housing prices in Kings Country, Washington. We must inform our stakeholders which features are the best predictors of home price in todays housing market. 

## Business Understanding
**Stakeholder:** Seattle Bank 

**Business Problem:** Banks give home loans based on the ability of the buyer to afford a home at a certain price point. We want to make sure that the value of the home is eqaul to or less than the mortage amount that will be given to the buyer. 

**Subproblem:**
Houses have many features that help in determining housing prices so we need to narrow the criteria by coming up with a regression model that helps predict the value in Kings County.

**Data Assumptions:** 
-The square footage, amount of bedrooms, and bathrooms of the home is the largest attribute to housing price.


## Data Understanding
We were given data for Kings County houses from 2014-2015. This data includes approximately 24,000 homes, 20 zipcodes, and 21 unique features that contribute to home pricing.


## Modelling
We started by construsting a simple linear regression to form our baseline statistics to get important information such as R^2 value, RSME, F-statistic, colinearity of features, and error measurements that reflect the quality of the regression model.


## Regression Results
After completing a simple linear regression model or baseline model. We noticed a 49% variance in the R^2 value after running the simple regressino model. Next we used the kitchen sink method, which is throwing in all the features/variables into the multiregression model and finding the R^2 until we found the optimum features to predict housing prices. After 5 models we were able to determine that square feet, amount of bedrooms and lot size were the most promanent features to determining housing prices in Kings County, Washington. We were able to get all the way up to 65% variance in our predictive model.


## Conclusion

**Reccomendations for buying homes in Kings County, Washington:**
- Square footage, amount of bedrooms, and water view are the main 3 contributing facotrs to house prices. We were able to predict variance on average of 65%.
Future Steps:
- Use the median prices for each of the 20 unique zip codes
- Get the data for time of year the houses are being sold and at what what price.