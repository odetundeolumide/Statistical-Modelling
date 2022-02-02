# Statistical Modelling
This program predicts baseball division winners using logistic regression.

## Technology and Setup
Program written in R version 4.1.2 (2021-11-01) -- "Bird Hippie".  
To run this program, install R studio locally. [Download R Studio](https://www.rstudio.com/products/rstudio/download/)

## Table of Content
* [Data Wrangling] (### Data Wrangling)
* Linear Regression
* Poisson Regression
* Lasso Regression
* Logistic Regression

### Data Wrangling
42 - 145 : Wrangling of the dataset to create tibbles and variables used  
to fit models

### Linear Regression
146 - 243: Fit simple linear regression model using log of mean salary as   
function of year

### Possion model
247 - 344 : Fit poisson model to predict number of runs ade by a player  
using a number of predcitor variables selected.

### Lasso Regression
351 - 424 : Used Lasso regression and cross validation to determine predictor  
variables needed to fit Logistic regression.

### Logistic Regression
429 - 484 : Fit Logistic regression model to predict division league winners 
using training data and validated on test data.
