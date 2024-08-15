# Gender Prediction through Voice Classification

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
This project aims to predict the gender of a speaker based on voice characteristics using machine learning classification models. By analyzing features of the voice, the model can accurately classify whether the speaker is male or female.

## Business Understanding
- **Problem:** Determining the gender of an individual through voice characteristics is important in various applications such as voice recognition systems, personalized assistants, and customer service automation.
- **Main Goal:** Develop a machine learning model to classify gender based on voice features.
- **Main Objective:** Accurately predict gender from voice data to improve user experiences in applications involving speech recognition and automation.

## Analytic Approach
We will experiment with various machine learning classification algorithms such as Logistic Regression, Decision Trees, K Nearest Nighbours and Support Vector Machine (SVM) - kernelling to predict gender based on voice features. 

## Data Requirements
The dataset includes the following features that represent different voice characteristics:

| Column         | Description                           |
|----------------|---------------------------------------|
| meanfreq       | Mean frequency (in kHz)               |
| sd             | Standard deviation of frequency       |
| median         | Median frequency                      |
| Q25            | First quantile (25th percentile)      |
| Q75            | Third quantile (75th percentile)      |
| IQR            | Interquartile range                   |
| skew           | Skewness of the distribution          |
| kurt           | Kurtosis of the distribution          |
| sp.ent         | Spectral entropy                      |
| sfm            | Spectral flatness measure             |
| mode           | Mode frequency                        |
| centroid       | Frequency centroid                    |
| meanfun        | Mean fundamental frequency            |
| minfun         | Minimum fundamental frequency         |
| maxfun         | Maximum fundamental frequency         |
| meandom        | Mean dominant frequency               |
| mindom         | Minimum dominant frequency            |
| maxdom         | Maximum dominant frequency            |
| dfrange        | Range of dominant frequencies         |
| modindx        | Modulation index                      |
| label          | **Target Variable**: Gender (Male/Female) |

## Data Collection
The dataset is provided in a CSV file named `voice.csv`, which contains labeled voice samples along with their corresponding features.

## Data Understanding
In this phase, we will explore the dataset to understand its structure, distribution, and any potential issues such as missing or noisy data. We will analyse the correlation between different features and the target variable (gender) to gain insights into which features are most informative.

## Data Preparation
Data preparation involves cleaning the dataset, handling missing or inconsistent values, normalising/standardising features, and splitting the dataset into training and testing sets for model evaluation.

## Modeling
We will apply different classification models to predict gender, including:
- Logistic Regression
- Decision Trees
- K Nearest Neighbours
- Support Vector Machines (SVM) - kernelling using poly, linear, RBF and Sigmoid

## Evaluation
The models will be evaluated using metrics such as Accuracy, Precision, Recall, and F1-Score. These metrics will allow us to measure the effectiveness of the models in correctly predicting the gender based on voice features.

