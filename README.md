# Advanced-ML-Final Project

## Group 23: Right Shark


## Group Member
* Anish Dalal
* Ziyu Fan
* Minchen Wang


## Project Goal
Predict in-app purchases in 7 days and 14 days


## Background
The data for this project was provided by Leanplum Inc and is generating by user activities of a single specific APP spanning from Oct 1st - Dec 14th. It would be good to have the prediction of the user's future behavior ahead, in order to help the company make better marketing stategies.


## Table of Content

Throughout the jupyter notebook, We describe the whole process before fitting the model, including initial dataset exploration, data cleaning, feature engineering, etc. For this binary classification problem, We tried several different classifiers, including Random Forest, Gradient Boosting, etc. As a result, We are able to achieve a binary classifier by Random Forest Model with AUC 0.974. 

### EDA & Preprocess

1. Train label computation
2. EDA on Sessions and Events table
3. Data Cleaning 
3. Dataset train test split

### Feature Engineering

1. Create featrues for train and test sets
2. Check & Handle missing values

### Model Fitting 

1. LightGBM
2. Random Forest
3. Gradient Boosting
