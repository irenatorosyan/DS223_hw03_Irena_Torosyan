# Telco Churn Analysis Readme


This repository contains code for analyzing customer churn in a telecommunications company. The goal of the analysis is to understand the factors affecting churn risk. The analysis includes interpreting coefficients from parametric survival models, identifying valuable customer segments, estimating annual retention budget, and providing suggestions for retention strategies.

Data

The dataset, named telco.csv includes information about Telco customers, such as region, tenure, age, marital status, address, income, education level, retirement status, gender, service subscriptions, and churn status.

Parametric Models

Four parametric survival models (Weibull, Exponential, Log-Normal, Log-Logistic) are fitted to the data, and AIC and BIC values are calculated to compare model performance. The results alongside the corresponding plots are printed for each model.

AFT Models

Weibull, Log-Normal, and Log-Logistic AFT models are fitted to the data, and AIC and BIC values are calculated. The results are printed for each AFT model.

Report

A report of findings is provided in the end of the file. 


Author

Irena Torosyan
