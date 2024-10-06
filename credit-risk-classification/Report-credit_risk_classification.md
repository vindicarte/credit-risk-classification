*Michael Sanchez*
*Data Analysis and Visualization*
*October 2024*

# Analysis of a Logistic Model on Creditworthiness

## Overview
The purpose of this analysis is to create and analyze a model based loan risk.  The data include the features of loan size, interest rate, borrower income, debt to income ratio, number of accounts, deratory marks, total debt, and loan status of over 19000 people.  The model created utilizes all of the features listed to create a logistic model that will predict the response variable of loan status (0 being ok and 1 being at risk).  The values for the explanatory variables will be standardized using a z-score relative to its mean and standard deviation to prevent any bias that may be occured by larger numbers such as income compared ratios.  Categorical variables like deratory marks have been categorized as 0 - yes and 1 - no.  The logistic model is then created and fitted based on these values and compared to the actual results.  The model can potentially be used to predict the outcome of loan status based on the features a person holds at this establishment.

## Results

- Variable (0:No risk): Precision 1.00 ; recall 0.99 ; f1-score 1.00 ; support(number of values) 18765
- Variable (1:Risk): Precision 0.84 ; recall 0.94; f1-score 0.89 ; support 619
- accuracy: 0.99
- macro average: precision 0.92; recall 0.97 ; f1-score 0.94
- weighted average: precsion 0.99 ; recall 0.99 ;f1-soore 0.99
- total values: 19384

## Summary
With the provided results, the logistic model has shown that there is a 99% accuracy when tested on the provided data.  This implies that any predictions utilizing this model with be accurate based on the features of the account holders.  The only potential issue that may arise from this model is based on the number of accounts at risk and not at risk.  Since the number of not at risk accounts is 18,765 compared to 619 at risk accounts there may be an issue of balancing.  In other words, the large different in values may have some affect in the predictions of the model, however, the value of precision for at risk accounts is still high at 84%.  Overall, this model will provide confidently provide the insights needed to predict what may lead to at risk accounts.

