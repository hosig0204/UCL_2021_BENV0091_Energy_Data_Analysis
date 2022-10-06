# A Simple Machine Learning Projet for Energy Data Analysis

## 1. Welcome!
This is a repository for a simple machine learning project developed for the EDA (Energy Data Analysis) module coursework under the programme MSc.ESDA (The Bartlett Energy Institute, UCL). In this repository, python notebooks for data post-processing, machine learning and visualisations are stored with sequential numnbers. You may follow all notebooks along with sequence numbers.

## 2. What data?
For the project, household energy consumption data from South Korea has been used. This data encompasses various household  characteristics versus annual energy consumption as heat unit. You may not familiar with variable names in the data set. Please, refer to "Table of Variables". If you want to explore datasets more, you can visit following web-application of data dashboard.

<p align="center">Link: <a href= "https://holee21.pythonanywhere.com">Web App built on pythonanywhere</a></p>

<p align="center"><img src="https://github.com/hosig0204/dash_deploy/blob/master/static/images/var_table.png" width="700"></p>

## 3. Regarding the Project
The machine learning project in this repository aims to predict annual houshold energy consumption as heat unit from various household characteristics such as area of house, housing type and family size. Through data post-processing (Notebooks 001 ~ 004), raw survey datasets of three years (2016 ~2018) were cleaned and processed for further machine learning steps. Then, two machine learning regression models were tried: Lasso-regularized Linear Regression (Notebook 005) and Neural Network Regression (Notebook 006). For each model, 10 fold Cross Validation (CV) was performed to defined optimized hyperparameters. Visualisations for model evaluation are also available in each notebook.