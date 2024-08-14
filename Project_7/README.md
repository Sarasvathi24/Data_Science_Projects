# Diabetes Prediction using Binary Classification Model

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
This project aims to build a classification model to predict whether a patient has diabetes based on various health metrics. The model will assist healthcare providers in making informed decisions about diabetes diagnosis and treatment.

## Business Understanding
- **Problem:** The goal is to predict the likelihood of a patient having diabetes based on medical features.
- **Main Goal:** Develop a reliable classification model that can accurately predict diabetes status.
- **Main Objective:** Create a tool that can support medical professionals in early detection of diabetes, thereby improving patient outcomes.

## Analytic Approach
To solve the problem, we will apply two classification algorithms, Decision Trees and KNN Classifier to identify which model best predicts diabetes status based on the features in the dataset.

## Data Requirements
The dataset for this project includes the following features:

| Column                  | Description                                              |
|-------------------------|----------------------------------------------------------|
| Pregnancies              | Number of pregnancies                                    |
| Glucose                  | Plasma glucose concentration over 2 hours in an oral glucose tolerance test |
| BloodPressure            | Diastolic blood pressure (mm Hg)                         |
| SkinThickness            | Triceps skin fold thickness (mm)                         |
| Insulin                  | 2-Hour serum insulin (mu U/ml)                           |
| BMI                      | Body mass index (weight in kg/(height in m)^2)           |
| DiabetesPedigreeFunction | Diabetes pedigree function (a function that represents likelihood of diabetes based on family history) |
| Age                      | Age of the patient (years)                               |
| Outcome                  | Class variable indicating whether the patient has diabetes (1) or not (0) |

## Data Collection
The dataset is provided in a CSV file named `diabetes_classification.csv`, containing relevant health metrics of patients and their diabetes status.

## Data Understanding
This phase involves exploring the dataset, identifying any missing or anomalous values, and understanding the relationships between the different features. Initial exploration will include summary statistics and visualization of the data distribution.

## Data Preparation
Data preparation includes cleaning the dataset by handling missing values, transforming features, normalising data and splitting the data into training and testing sets. Feature engineering might be performed to enhance model performance.

## Modeling
During the modeling phase, we will experiment with two classification algorithms: KNN Classifier and Decision Tree Classifier.
These models will be trained and tested on the dataset to determine which one provides the best performance in terms of classification accuracy.

## Evaluation
The models will be evaluated using performance metrics such as Accuracy, Precision, Recall, F1-Score, Confusion Matrix and Classification Report. These metrics will help determine the effectiveness and reliability of the predictive models.
