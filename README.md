# House-Price-Prediction
This project uses the XGBoost algorithm to predict house prices based on a dataset of relevant features.

## Introduction
The data is part of an ML competition, *Housing Prices Competition for Kaggle Learn Users* (https://www.kaggle.com/competitions/home-data-for-ml-course).

> **Competition Description**:
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

## Data:
* train.csv - the training set
* test.csv - the test set
* data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here
* sample_submission.csv - a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms

## How to use:
* Clone this repository
* Install the required dependencies
* Run `house-price-prediction.ipynb`

## Dependencies
- xgboost
- pandas
- scikit-learn
- matplotlib
- numpy

## Results
`Output.csv`: The house prices predicted by the model for the `test.csv` dataset. 
