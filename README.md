Project Title: Diabetes Prediction & Risk Factor Analysis

Overview:
This project utilizes a Kaggle-sourced dataset containing medical and demographic information—such as BMI, HbA1c levels, and blood glucose—to predict the likelihood of diabetes in patients. The analysis focuses on comparative modeling to identify the most accurate predictors for medical diagnosis.

Key Features:

Data Preprocessing: Handled class imbalance (reducing the dataset from ~100k to ~17k observations for parity), converted categorical variables into numeric dummies, and performed extensive data cleaning.

Feature Selection: Implemented LASSO, RIDGE, and Correlation techniques to reduce overfitting and address multicollinearity.

Machine Learning Modeling: Developed and compared multiple classification models, including Decision Trees, Naive Bayes, KNN, SVM, Logistic Regression, XGBoost, and Random Forest.

Performance Metrics: Evaluated models based on Accuracy and the Kappa metric, with a specific focus on high recall to minimize false negatives in medical screening.

Results:
The Random Forest model achieved the highest performance with 91% accuracy and a Kappa score of 0.82. Feature importance analysis identified HbA1c level and blood glucose level as the most significant indicators of diabetes
