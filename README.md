# Loan Approval Prediction Using Machine Learning

A machine learning classification project for predicting loan approval based on applicant demographic, financial, credit, and property-related attributes.

## 📌 Project Overview

Loan approval decisions depend on multiple applicant characteristics, including income, credit history, loan amount, education, employment status, and property information.

This project develops and compares multiple classification models to predict whether a loan application is likely to be approved.

The workflow covers:

- Data cleaning and preprocessing
- Exploratory Data Analysis
- Feature engineering
- Categorical variable encoding
- Numerical feature scaling
- Class distribution analysis
- Classification model development
- Model evaluation and comparison
- Feature importance analysis

## 🎯 Objectives

- Analyze factors associated with loan approval.
- Prepare applicant data for machine learning.
- Handle missing and categorical data effectively.
- Engineer useful financial features.
- Compare multiple classification algorithms.
- Evaluate models using multiple classification metrics.
- Identify influential variables for loan approval prediction.

## 📊 Dataset

The project uses a standard Loan Prediction / Loan Eligibility dataset containing applicant information such as:

- Gender
- Married Status
- Dependents
- Education
- Self Employment
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Term
- Credit History
- Property Area
- Loan Status

The target variable is `Loan_Status`, representing whether the loan was approved.

## 🔧 Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Encoding categorical variables
- Scaling numerical variables where appropriate
- Examining class distribution
- Separating features and target variable
- Splitting data into training and testing sets

### Feature Engineering

A derived feature called `TotalIncome` was created by combining:

```text
TotalIncome = ApplicantIncome + CoapplicantIncome
