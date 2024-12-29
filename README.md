# Credit-Card-Fraud-Transaction
The Credit Card Fraud Detection project utilizes machine learning techniques to identify fraudulent transactions within a dataset sourced from Kaggle. The dataset comprises 284,807 transactions, of which only 0.17% are labeled as fraudulent, highlighting the challenge of class imbalance in this domain. 
# Credit Card Fraud Detection  

## Overview  
This project aims to detect fraudulent credit card transactions using machine learning models. The dataset used is the [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/dalpozz/creditcard-fraud). The goal is to identify fraudulent transactions while minimizing false positives.  

## Table of Contents  
- [Approach](#approach)  
- [Data Preprocessing Steps](#data-preprocessing-steps)  
- [Model Selection](#model-selection)  
- [Evaluation Metrics](#evaluation-metrics)  
- [Installation](#installation)  
- [Usage](#usage)  
- [License](#license)  

## Approach  
The approach involves:  
1. **Data Loading**: Load the dataset and perform initial investigations.  
2. **Data Exploration**: Conduct exploratory data analysis (EDA) to understand distribution and identify patterns.  
3. **Data Preprocessing**: Clean the data, handle missing values, and normalize features.  
4. **Model Training**: Implement various machine learning algorithms and select the best performing model.  
5. **Model Evaluation**: Evaluate models using appropriate metrics that account for class imbalance.  

## Data Preprocessing Steps  
1. **Removing Unnecessary Columns**: Eliminate any irrelevant columns that do not contribute to the model.  
2. **Handling Missing Values**: If there are missing values:  
   - Fill or drop them based on analysis.  
3. **Feature Scaling**: Normalize or standardize features as the dataset is highly imbalanced.  
4. **Encoding Categorical Variables**: Convert categorical variables into a numerical format if necessary.  

## Model Selection  
- **Models Used**:   
  - Logistic Regression  

## Evaluation Metrics  
Because the dataset is imbalanced (fraud cases are much less than legitimate transactions), I focused on:  
- **Accuracy**: Overall correctness of the model.  
- **Precision**: Proportion of true positive results in predicted positives.   
