# Credit Card Approval Classification Project

## Table of Contents
- [Introduction](#introduction)
- [Business Understanding](#business-understanding)
- [Analytic Approach](#analytic-approach)
- [Data Requirements](#data-requirements)
- [Data Collection](#data-collection)
- [Data Understanding](#data-understanding)
- [Data Preparation](#data-preparation)
- [Modeling](#modeling)
- [Evaluation](#evaluation)

## Introduction
This project focuses on predicting credit card approval decisions using machine learning classification techniques. The goal is to assist banks and financial institutions in making accurate and informed decisions about which credit card applications should be approved.

## Business Understanding
- **Problem:** Banks need to classify applicants as either approved or denied for a credit card based on their financial and personal details.
- **Main Goal:** Develop a reliable classification model that can predict credit card approvals based on applicant information.
- **Main Objective:** Create a model that enhances decision-making by accurately predicting credit card approvals, reducing financial risk for institutions.

## Analytic Approach
We will use machine learning classification algorithms such as Logistic Regression, Decision Trees, and Support Vector Machines (SVM)- kerneling to predict the approval status of credit card applications. 

## Data Requirements
The dataset contains the following features:

| Column              | Description                                                    |
|---------------------|----------------------------------------------------------------|
| Age                 | Applicant's age                                                |
| Experience          | Applicant's years of work experience                           |
| Income              | Applicant's annual income                                      |
| Family              | Number of family members                                       |
| CCAvg               | Average monthly credit card spending                           |
| Education           | Applicant's education level (1 = Undergraduate, 2 = Graduate, 3 = Postgraduate) |
| Mortgage            | Value of the applicant's mortgage                              |
| PersonalLoan        | Whether the applicant has a personal loan (1 = Yes, 0 = No)    |
| SecuritiesAccount   | Whether the applicant has a securities account (1 = Yes, 0 = No) |
| CDAccount           | Whether the applicant has a certificate of deposit account (1 = Yes, 0 = No) |
| Online              | Whether the applicant uses online banking (1 = Yes, 0 = No)    |
| CreditCard          | **Target Variable**: Whether the applicant is approved for a credit card (1 = Approved, 0 = Denied) |

## Data Collection
The dataset is stored in a CSV file named `UniversalBank_SVM.csv` containing applicant data, which will be used to train and test the classification models.

## Data Understanding
This phase involves exploring the dataset to understand its structure, identify missing values, and examine the distribution of different features. Data visualization and statistical summaries will be used to better understand the relationships between features and the target variable.

## Data Preparation
Data preparation includes cleaning the dataset, handling any missing values, encoding categorical variables, normalising data to evaluate the SVM accuracy and splitting the data into training and testing sets. 

## Modeling
In this phase, we will implement several classification algorithms to build predictive models, including:
- Logistic Regression
- Decision Trees
- K Nearest Neighbours 
- Support Vector Machines (SVM) - kernelling using Linear, Poly, RBF & Sigmoid

## Evaluation
The models will be evaluated using metrics such as Accuracy, cross-validation and classification reports. These metrics will allow us to assess the performance of each model in predicting credit card approval decisions.
