# idm_assignment_2
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
2. **Logistic Regression Model**: Train a logistic regression model.
3. **Batch Processing**: Implement batch processing to handle large datasets.
4. **Scaling**: Scale features using Min-Max scaling.
5. **Evaluation**: Evaluate the model performance using relevant metrics (e.g., accuracy).

## Files
- `data_preprocessing.ipynb`: Jupyter notebook containing data cleaning and preprocessing steps.
- `model_training.ipynb`: Jupyter notebook for training the Logistic Regression model.
- `requirements.txt`: List of Python dependencies.

## Usage
1. Run `data_preprocessing.ipynb` to preprocess the dataset.
2. Run `model_training.ipynb` to train the Logistic Regression model.

## Requirements
Ensure you have the required Python packages by installing them using:
```bash
pip install -r requirements.txt
