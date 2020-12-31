# Data Science Notebooks

This repository contains personal projects where I developed machine learning models and performed exploratory data analysis for various data sets. Each project is in its own folder in this repository, and is summarized below.

## Red Wine Quality Prediction (Regression)

I developed a machine learning model to predict a quality rating (between 1 and 10) for measured physical attributes of 1599 different vinho verde red wines from Portugal. The resultant extremely randomized trees model achieved a mean squared error of 0.306 on the test set, in comparison to the 0.66 validation error that was obtained for a dummy model that always predicted the mean value of the training data. The most important feature in this model was alcohol concentration, followed by volatile acidity and sulphates.

## Heart Disease Classification

I developed a machine learning model to predict the occurence of heart disease in patients based on measured risk factors. The resultant logistic regression model correctly classified 81.7 percent of patients, and correctly classified 77 percent of those with heart disease.

## Modeling Ames, Iowa Housing Data (Regression)

I developed a machine learning model to predict the cost of housing for the common Ames, Iowa housing dataset. The resultant stacked model was an ensemble of regularized linear regression and boosted trees models (XGBoost and LightGBM). The result was in the top 12 percent of submissions for this problem on kaggle.
