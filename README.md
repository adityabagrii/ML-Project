# Bank Marketing Prediction Machine Learning Project

This project leverages advanced machine learning techniques to predict whether a client will subscribe to a bank term deposit based on data from direct marketing campaigns. By employing rigorous data preprocessing, comprehensive feature engineering, and extensive model tuning, the project transforms raw banking data into actionable insights—making it an invaluable tool for enhancing direct marketing strategies.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Dataset Description](#dataset-description)
- [Preprocessing & Feature Engineering](#preprocessing--feature-engineering)
- [Modeling & Evaluation](#modeling--evaluation)
- [Results & Analysis](#results--analysis)
- [Conclusion](#conclusion)
- [Installation & Usage](#installation--usage)
- [References](#references)
- [Authors](#authors)

## Overview

This project focuses on predicting term deposit subscription outcomes using a dataset collected from a Portuguese bank's direct marketing campaigns. The objective is to improve customer targeting by predicting client responses accurately. Four different models were explored—Logistic Regression, Random Forests, XGBoost, and Multi-Layer Perceptron (MLP)—with extensive hyperparameter tuning via grid search to determine the optimal settings.

## Features

- **Robust Data Preprocessing:** Comprehensive handling of missing values, outlier detection, and data normalization.
- **Feature Engineering:** Effective transformation techniques, including log transformations, label encoding, and one-hot encoding.
- **Model Comparison:** Evaluation of four diverse machine learning models with performance metrics like accuracy, precision, recall, and AUC.
- **Visualization:** Detailed graphs, heatmaps, and correlation matrices provide deep insights into the data and model performance.

## Dataset Description

The dataset includes multiple attributes divided into several key groups:

- **Bank Client Data:** Client age, job type, marital status, education, credit default, housing and personal loans.
- **Campaign Details:** Communication type, last contact details, call duration, and previous campaign interactions.
- **Economic Indicators:** Employment variation rate, consumer price index, consumer confidence index, Euribor 3-month rate, and quarterly employee counts.
- **Output Variable:** Indicates whether the client subscribed to a term deposit ("yes" or "no").

## Preprocessing & Feature Engineering

- **Handling Missing Data:** Dropped or imputed missing values based on feature imbalance.
- **Outlier Detection:** Utilized box plots and the Interquartile Range (IQR) method for numerical attributes.
- **Feature Transformation:** Applied log transformations to reduce skewness and scaling techniques (Standard and Min-Max) for normalization.
- **Encoding Strategies:** Leveraged label encoding for ordinal data and one-hot encoding for categorical variables to enhance model interpretability.

## Modeling & Evaluation

Four models were trained and evaluated using grid search for hyperparameter tuning, encompassing over 800 model fits:

1. **Logistic Regression:** Achieved an accuracy of 87.69% but showed lower precision for the minority class.
2. **Random Forest:** Reached an accuracy of 90.84% with a balanced performance.
3. **XGBoost:** Delivered the best performance with an accuracy of 90.98%, excelling in both precision and recall—making it the top choice for this application.
4. **Multi-Layer Perceptron (MLP):** Recorded an accuracy of 88.72% with competitive results.

## Results & Analysis

- **XGBoost Outperformance:** Detailed metrics revealed that XGBoost not only provided high accuracy but also maintained robust precision and recall across classes, making it ideal for banking applications.
- **Model Insights:** Visualizations such as confusion matrices, feature importance graphs, and loss vs. epoch curves were instrumental in understanding the strengths and limitations of each model.
- **Strategic Value:** The findings underscore the potential of machine learning to significantly enhance the effectiveness of telemarketing strategies by accurately targeting potential subscribers.

## Conclusion

The project demonstrates that with meticulous preprocessing and methodical model evaluation, machine learning—especially using XGBoost—can reliably predict client behavior in banking campaigns. These insights can help financial institutions optimize their marketing efforts, reduce unnecessary contact, and improve customer engagement.

## Installation & Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/adityabagrii/ML-Project
