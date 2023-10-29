# idm_assignment_21.	Data Preprocessing:
	I have a dataset with multiple columns, including categorical and numerical features. Some categorical features have been encoded using label encoding, while others were transformed in a specific way (e.g., extracting numeric values from the "Length of Stay" column).
	I dropped rows with certain values (e.g., rows where "Gender" is 'U' or "Race" is 'Unknown') to clean the data.
2.	Correlation Analysis:
	I created a correlation matrix to explore the relationships between features and the target variable ("APR Severity of Illness Description").
	The correlation heatmap is used to visualize these relationships.
3.	Data Splitting:
	The dataset is split into a training set and a test set using the train_test_split function. This is important for evaluating the model's performance on unseen data.
4.	Random Forest Model:
	I created a Random Forest Classifier model with the following hyperparameters:
	n_estimators: Number of trees in the forest (100).
	max_depth: Maximum depth of each tree (7).
	random_state: Random seed for reproducibility (42).
5.	Model Training:
	I fit the model to the training data using model.fit(X_train, y_train), where X_train contains the feature matrix and y_train contains the target labels. The label encoding of the target variable is done to ensure that it's in a suitable format for the model.
6.	Model Prediction:
	I make predictions on the test data using model.predict(X_test).
7.	Accuracy Calculation:
	I calculated the accuracy of the model by comparing the predicted labels (y_pred) with the true labels in the test set (y_test). The accuracy_score function is used for this purpose.
8.	Accuracy Output:
	The final accuracy of the model is printed.

An accuracy of 0.64 means that the model correctly predicts the severity of illness in 64% of the cases in the test set. 

