# Breast Cancer Classification Project

## Table of Contents
1. [Introduction](#introduction)
2. [Business Understanding](#business-understanding)
3. [Analytic Approach](#analytic-approach)
4. [Data Requirements](#data-requirements)
5. [Data Collection](#data-collection)
6. [Data Understanding](#data-understanding)
7. [Data Preparation](#data-preparation)
8. [Modeling](#modeling)
9. [Evaluation](#evaluation)

## 1. Introduction
This project aims to develop a machine learning model for the classification of breast cancer tumors into benign or malignant categories. By leveraging data on tumor characteristics, this analysis seeks to aid in the early detection of breast cancer, thus supporting medical professionals in making accurate diagnoses and improving patient outcomes.

## 2. Business Understanding
**Problem:** The primary challenge is to accurately classify breast cancer tumors as benign or malignant based on specific features derived from patient data. Accurate classification is crucial for timely treatment and improved survival rates.

**Main Goal:** Build a robust classification model to predict whether a breast tumor is benign or malignant.

**Main Objective:** Develop and evaluate machine learning model that can effectively classify breast cancer tumors, thereby assisting in early detection and diagnosis.

## 3. Analytic Approach
To address the problem, we will utilize KNearest Neighbours Classification algorithm by tuning its hyperparameter, while checking the overfitting to ensure the model can also predict for test or validation data.

## 4. Data Requirements
The dataset for this project includes the following features:

| Column                        | Description                                       |
|-------------------------------|---------------------------------------------------|
| Id                            | Unique identifier for each record                 |
| Clump_thickness               | Uniformity of the cell size                       |
| Uniformity_Cell_Size          | Uniformity of the cell size                       |
| Uniformity_Cell_Shape         | Uniformity of the cell shape                      |
| Marginal_Adhesion             | Adhesion level of the cells                       |
| Single_Epithelial_Cell_Size   | Size of the epithelial cells                      |
| Bare_Nuclei                   | Presence of bare nuclei in cells                  |
| Bland_Chromatin               | Texture of the chromatin in the nucleus           |
| Normal_Nucleoli               | Appearance of the nucleoli                        |
| Mitoses                       | Number of mitotic cells                           |
| Class                         | Indicates if the tumor is benign (2) or malignant (4) |

## 5. Data Collection
The dataset is sourced from the Breast Cancer Wisconsin (Diagnostic) dataset, and it is stored in a TXT file named `breast-cancer-wisconsin.data.txt`.

## 6. Data Understanding
This phase involves thoroughly exploring the dataset to understand its structure, identify missing values, and examine the relationships between features. Descriptive statistics and visualizations will be used to gain insights into the data.

## 7. Data Preparation
Data preparation is a critical step, including:
- Handling missing values.
- Encoding categorical variables.
- Splitting the dataset into training and testing sets.

## 8. Modeling
The modeling phase involves selecting and applying K Nearest Neighbours algorithm with hyperparameter tuning.

## 9. Evaluation
The models will be evaluated using key performance metrics including:
- **Accuracy**
- **Confusion Matrix**
- **Classification Report**
- **Overfitting Test**
