# Credit-Risk-Modeling-for-Default
Project Overview
This project aims to measure the credit risk of LendingClub, (an American peer-to-peer lending company), by calculating the expected loss of their outstanding loans. Credit risk is the likelihood that a borrower would not repay their loan to the lender. By continually evaluating the risk and adjusting their credit policies, the lender could minimize its credit losses while it reaches the fullest potential to maximize revenues on loan borrowing. It is also crucial for the lender to abide by regulations that require them to conduct their business with sufficient capital adequacy, which, if in low, will risk the stability of the economic system. 

The key metric of credit risk is Expected Loss (EL), calculated by multiplying the results across three models: PD (Probability of Default), LGD (Loss Given Default), and EAD (Exposure at Default). The project includes all three models to help reach the final goal of credit risk measurement.  
**Code and Resources Used**
Python Version: 3.8.5 Packages: pandas, numpy, sklearn, scipy, matplotlib, seaborn, pickle Algorithms: regression (multiple linear), classification (logistic regression)

Dataset Source: https://www.kaggle.com/shawnysun/loan-data-for-credit-risk-modeling


Datasets Information
'loan_data_2007_2014.csv' contains the past data of all loans that we use to train and test our model
'loan_data_2015.csv' contains the current data we will implement the model to measure the risk
'loan_data_defaults.csv' contains only the past data of all defaulted loans
