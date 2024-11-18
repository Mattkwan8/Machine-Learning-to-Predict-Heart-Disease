# Machine-Learning-to-Predict-Heart-Disease

This project aims to predict heart disease using machine-learning classification models. The data is sourced from the "Heart Disease" dataset in the UCI Machine Learning Repository 
In the Importing and Cleaning Section: the dataset is imported and converted into a pandas data frame. It is then cleaned by dropping missing values, adjusting data types and converting the target variable into a binary classification (1 for the presence of heart disease, 0 for absence.
Initial Analysis of data is done through Exploratory Data Analysis reports, Correlation Matrices, Frequency and Contingency tables of categorical attributes and visualization of key relations.
Data is discretized for association rules
FP-Growth and Apriori are run for association rules
Information gain is run for feature selection
Data is split 20/80 and cross-validated with 5-Fold Stratified Cross Validation
Logistic Regression, Random Forest and K-Nearest Neighbours models are trained and used to make predictions
Features selection is used to select the top features to include in a re-run of models
