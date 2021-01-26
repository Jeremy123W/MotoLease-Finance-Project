# MotoLease-Finance-Project
Applied Finance Project (Capstone) for our client company MotoLease

The objective of this project is to predict consumer loan defaults using several datasets related to credit history. 
The historical datasets used for the study were provided by MotoLease.  MotoLease is a financial services company that 
offers motorcycle leasing programs through authorized dealers.  We constructed 95 features from the datasets and then 
used a two sample K-S test to evaluate the predictive value of each feature.  We then used XGBoost to build gradient 
boosted tree models using a variety of regularization and cross-validation techniques. We also fitted a logistic regression. 
We were able to achieve an ROC AUC of 0.70 and identify key features to help improve the credit scoring model.
