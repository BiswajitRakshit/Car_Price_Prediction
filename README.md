# Car_Price_Prediction

# Dataset:
This dataset contains information about used cars listed on www.cardekho.com. This data can be used for a lot of purposes such as price prediction to exemplify the use of linear regression and many regression algorithms in Machine Learning. 


I used multiple linear regression, k-nearest neighbours, naïve Bayes and decision trees algorithm in order to predict the prices. 
The comparison of prediction results from these techniques showed that the prices from these methods are closely comparable. 
However, it was found that decision tree algorithm and naïve Bayes method were unable to classify and predict numeric values. 

Car price is considered as the dependent variable while other attributes as the independent variables.

Random Forest is an ensemble learning based regression model. 
It uses a model called decision tree, specifically as the name suggests, multiple decision trees to generate the ensemble model which collectively produces a prediction. 
The benefit of this model is that the trees are produced in parallel and are relatively uncorrelated, thus producing good results as each tree is not prone to individual errors of other trees. 

This uncorrelated behavior is partly ensured by the use of Bootstrap Aggregation or bagging providing the randomness required to produce robust and uncorrelated trees. 
This model was hence chosen to account for the large number of features in the dataset and compare a bagging technique with the following gradient boosting methods.

# Deployment on Heroku:
To deploy the model on Heroku, put your project on GitHub and create a account on Heroku. Please use python as programming language while setting up the account.

# Project Link:
https://car7price7pred.herokuapp.com 


