# Treatment Prioritization Model

## Overview
This repository contains code for a Treatment Prioritization model using a machine learning approach. The goal of the model is to prioritize treatments based on the severity of illness using the APR (All Patient Refined) Severity of Illness Code as the target variable.

## Dataset
The model is trained on a dataset containing various features related to patient information, diagnoses, procedures, and other relevant information. The target variable is the APR Severity of Illness Code.

## Preprocessing
1. **Data Cleaning**: Handle missing values, outliers, and any data quality issues.
2. **Encoding**: Encode categorical variables using a combination of label encoding and one-hot encoding.
3. **Feature Engineering**: Create relevant features based on domain knowledge.

## Model Training
1. **Data Splitting**: Split the dataset into training and testing sets.
2. **XGBoost Model**: Attempted to train an XGBoost model for multi-class classification.
3. **Logistic Regression Model**: Attempted to train a logistic regression model for comparison.
4. **Decision Tree Model**: Attempted to implement a decision tree model for interpretability.
5. **Batch Processing**: Implemented batch processing to handle large datasets.
6. **Scaling**: Scaled features using Min-Max scaling.
7. **Evaluation**: None of the mentioned models worked due to memory acquisition issues, leading to crashes with the large dataset.

## Files
- `data_preprocessing.ipynb`: Jupyter notebook containing data cleaning and preprocessing steps.
- `model_training.ipynb`: Jupyter notebook for attempting to train XGBoost, Logistic Regression, and Decision Tree models.
- `requirements.txt`: List of Python dependencies.

## Usage
1. Run `data_preprocessing.ipynb` to preprocess the dataset.
2. The model training section in `model_training.ipynb` may require optimization for memory usage before execution.

## Challenges
The mentioned models faced challenges with memory acquisition, leading to crashes, likely due to the size of the dataset and the complexity of the target variable.
