# Pima-Indians-Diabetes-Database
A structured Python project for predicting diabetes outcomes using supervised machine learning models. Includes data preprocessing, model training, hyperparameter tuning, evaluation metrics, and visualizations.

## Dataset
- **Source:** [Kaggle - Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database)  
- **Target:** `Outcome` (0 = no diabetes, 1 = diabetes)

## Features
- Handles missing values (zeros → NaN → median imputation)  
- Scales numeric features  
- Models: Logistic Regression, RandomForest, XGBoost  
- GridSearchCV for hyperparameter tuning  
- Evaluation: Accuracy, Precision, Recall, F1, ROC-AUC  
- Visualizations: Confusion matrix, ROC curve, Feature importance
