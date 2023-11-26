# Credit Card Fraud Detection Using Machine Learning

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

## About

**Project Owner:** Mohamed Haitham

Credit Card Fraud Detection is a critical application of machine learning to identify and prevent fraudulent credit card transactions. This project explores various techniques and algorithms to achieve accurate fraud detection, leveraging the [Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle.

## Table of Contents
1. [Introduction](#introduction)
2. [Data](#data)
3. [Exploratory Data Analysis (EDA)](#eda)
4. [Data Transformation](#data-transformation)
5. [Model Building on Imbalanced Data](#model-building-on-imbalanced-data)
6. [Model Building on Balanced Data with Undersampling](#model-building-on-balanced-data-with-undersampling)
7. [Model Building on Balanced Data with Oversampling](#model-building-on-balanced-data-with-oversampling)
8. [Model Building on Balanced Data with SMOTE](#model-building-on-balanced-data-with-smote)
9. [Model Building on Balanced Data with ADASYN](#model-building-on-balanced-data-with-adasyn)
10. [Conclusions](#conclusions)
  
## Introduction

Credit Card Fraud Detection is a critical task in the financial industry. This project aims to build robust models capable of identifying fraudulent credit card transactions. We employ various machine learning algorithms and techniques to enhance fraud detection accuracy and reduce false positives.

## Data

We use the [Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle for training and evaluation. This dataset contains a mixture of fraudulent and non-fraudulent transactions, making it suitable for building and testing our models.

## Exploratory Data Analysis (EDA)

Our exploratory data analysis includes:

- Understanding the dataset's structure and features.
- Identifying missing values and handling outliers.
- Visualizing data through univariate, bivariate, and multivariate analyses.

## Data Transformation

We preprocess the data to prepare it for modeling, including feature scaling and encoding categorical variables.

## Model Building on Imbalanced Data

We experiment with various machine learning algorithms, including:

- Logistic Regression
- Naive Bayes
- Decision Tree
- Random Forest
- AdaBoost
- XGBoost
- LightGBM
- CatBoost
- ANN (Artificial Neural Network)

We evaluate model performance on the imbalanced dataset.

## Model Building on Balanced Data with Undersampling

In this section, we balance the dataset through undersampling and re-run the same algorithms as in the previous section to assess their performance.

## Model Building on Balanced Data with Oversampling

Similar to the previous section, we balance the dataset through oversampling and evaluate model performance.

## Model Building on Balanced Data with SMOTE

We employ Synthetic Minority Over-sampling Technique (SMOTE) to balance the dataset and assess model performance.

## Model Building on Balanced Data with ADASYN

We use the Adaptive Synthetic Sampling (ADASYN) algorithm to balance the dataset and evaluate model performance.

## Conclusions

We summarize our findings, discuss the effectiveness of different techniques, and highlight the best-performing models for credit card fraud detection.

## License

This project is licensed under the MIT License. For more details, please refer to the [LICENSE](LICENSE) file.

## Contributions

Contributions to this project are welcome. If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your contributions.
3. Make your changes, test them thoroughly, and adhere to best practices.
4. Create a pull request with a clear description of your changes.

For any questions or concerns, please contact [Mohamed Haitham](medohaitham99@gmail.com).
