Goal is to predict how likely individuals are to receive their xyz and seasonal flu
vaccines. Specifically, you'll be predicting two probabilities: one for xyz_vaccine and
one for seasonal_vaccine.

Labels

For this competition, there are two target variables:
● xyz_vaccine - Whether respondent received xyz flu vaccine.
● seasonal_vaccine - Whether respondent received seasonal flu vaccine.
Both are binary variables: 0 = No; 1 = Yes.

##Approached and techniques I have used: 
First I started with handling the categorical variables and converting them into numeric form with One Hot Encoding 
secondly I started finding missing values and replacing them with mode values if missing values are in reasonal numbers 
Then I perform normalization on the data to convert all the data in range zero to one (0 to 1) 
Then I started building models I have tried many machine learning model and I choosed the one with maximum  roc auc score which is Logistic Regression model.
Then I performed hyperparameter tuning to impove the roc auc score of model 
Then I trained the two model for two output 
Then finally after performing all the steps for given test data I performed the prediction task and stored the prediction in final.csv
