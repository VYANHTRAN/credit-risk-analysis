# Home Credit Default Risk - Kaggle Competition

## Overview

This repository contains the code and resources for the **Home Credit Default Risk** Kaggle competition. The competition aims to predict the probability of a customer defaulting on a loan using diverse datasets provided by Home Credit Group.

[Kaggle Competition Link]([https://www.kaggle.com/competitions/home-credit-default-risk](https://www.kaggle.com/competitions/dseb-64-data-preparation-final-project))

## Problem Statement

Financial institutions need to assess the risk of lending to applicants who lack a significant credit history. This challenge involves building a predictive model to determine a client’s probability of defaulting based on demographic, financial, and transactional data.

## Data Description

The dataset consists of multiple tables containing structured data about loan applications, credit history, and repayment records. Key datasets include:

- **application_train.csv**: Contains demographic and financial data of previous applicants.
- **application_test.csv**: Similar to `application_train.csv` but without the target variable.
- **bureau.csv & bureau_balance.csv**: Contains information about past loans applicants had with other financial institutions.
- **previous_application.csv**: Data on previous loan applications from the same clients.
- **installments_payments.csv**: History of past installment payments.
- **POS_CASH_balance.csv**: Monthly balance snapshots of point-of-sale and cash loans.
- **credit_card_balance.csv**: Monthly balance snapshots of credit cards.

For a complete description of the data, refer to the Kaggle competition page.

## Approach

The project follows a structured pipeline:

1. **Exploratory Data Analysis (EDA)**: Understanding the data, feature distributions, and correlations.
2. **Preprocessing & Cleaning**: Normalization, encoding categorical variables, and handling outliers.
3. **Feature Engineering**: Creating new features and handling missing values.
4. **Modeling**: Training machine learning models, including Logistic Regression, Random Forest, LightGBM, and XGBoost.
5. **Evaluation & Hyperparameter Tuning**: Using metrics like AUC-ROC to assess model performance.

## Repository Structure

The repository contains the following directories: 

1. EDA Home Credit Default: Contains in-depth EDA files for the given dataset.
2. Feature Engineering & Model: Contains the detailed Feture Engineering and Modelling on the given dataset. It is constructed as a pipeline where the we can directly get the Predictions by just giving the inputs to the pipeline, which does all the pre-processing and predictions by itself.
