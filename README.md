# Treatment Prioritization Model

## Overview
This repository contains code for a Treatment Prioritization model using a machine learning approach. The goal of the model is to prioritize treatments based on the severity of illness using the APR (All Patient Refined) Severity of Illness Description as the target variable.

## Dataset
The model is trained on a dataset containing various features related to patient information, diagnoses, procedures, and other relevant information. The target variable is the APR Severity of Illness Description.

## Preprocessing
1. **Data Cleaning**: Handle missing values, outliers, and any data quality issues.
2. **Encoding**: Encode categorical variables using a combination of label encoding and one-hot encoding.
3. **Feature Engineering**: Create relevant features based on domain knowledge.

## Model Training
1. **Data Splitting**: Split the dataset into training and testing sets.
2. **XGBoost Model**: Train an XGBoost model for multi-class classification.
3. **Logistic Regression Model**: Train a logistic regression model for comparison.Though i tried both models neither of them worked as system crashed due to memory.
4. **Batch Processing**: Implement batch processing to handle large datasets.
5. **Scaling**: Scale features using Min-Max scaling.
6. **Evaluation**: Evaluate the model performance using relevant metrics (e.g., accuracy).

## Files
- `data_preprocessing.ipynb`: Jupyter notebook containing data cleaning and preprocessing steps.
- `model_training.ipynb`: Jupyter notebook for training both XGBoost and Logistic Regression models.
- `requirements.txt`: List of Python dependencies.

## Usage
1. Run `data_preprocessing.ipynb` to preprocess the dataset.
2. Run `model_training.ipynb` to train both XGBoost and Logistic Regression models.

## Requirements
Ensure you have the required Python packages by installing them using:
```bash
pip install -r requirements.txt
