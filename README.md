# Finals Ames_Iowa

## Domain
Data set contains information from the Ames Assessor’s Office used in computing assessed values for individual residential properties sold in Ames, IA from 2006 to 2010.
SOURCES: 
Ames, Iowa Assessor’s Office 

## Problem Statement
Predict the sale price

## Dataset

The Ames Iowa House Prices dataset [Link](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

- Number of samples: 1,451
- Number of attributes: 80 (79 attributes + 1 target (sale price))
- Expected Dataframe Dimensions: 1451 rows x 80 columns
- Column Data Types: category(56), float64(3), int64(21)
- memory usage: 365.6 KB
- Target: SalePrice

## Solution Statement

Fit a regression model using default settings with each of the following kinds of models:

   - ridge regression
   - lasso regression
   - knn
   - decision tree
   - support vector machines
   
Use a cross-validated grid search to refine three of the above models.
Prepare a complexity curve for at least one attribute for each of the three models that you are tuning.

## Benchmark Model

Regression model can have a naive benchmark model of mean value calculation

## Performance/Evaluation Metric

The problem is solved as a Regression Model. Below are few Evaluation Metric/Models that can be used
- Adjusted R Squared
- MSE (mean square error)
