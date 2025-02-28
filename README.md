### Churn-analysis

This repository contains code that trains a model to predict whether a customer will churn. 
The accuracy of the model is about 81%.

Additionally, the customers are clustered to see if churn can be predicted in that way.
This is not very succesful, as one cluster group has a churn percentage of about 30%, the other about 21%, instead of 100% and 0%.

Applied methods in this script are: machine learning using xgboost, clustering with KMeans, visualization with seaborn, preprocessing (StandardScaler, feature engineering).

The used dataset can be found at: 
https://www.kaggle.com/datasets/blastchar/telco-customer-churn
