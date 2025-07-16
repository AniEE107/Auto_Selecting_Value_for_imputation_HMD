# Auto_Selecting_Value_for_imputation_HMD
Focuses on building a robust machine learning pipeline for classification tasks, with a particular emphasis on the automatic selection of optimal imputation strategies for handling missing data.
Using the well-known Titanic dataset as a case study, this project demonstrates how to leverage GridSearchCV to systematically evaluate and select the best imputation methods alongside other model hyperparameters. The goal is to maximize model performance by intelligently addressing missing values.

# Key Highlights:
Automated Imputation Strategy Selection: Implements GridSearchCV to automatically determine the most effective imputation techniques for both numerical and categorical features.
Comprehensive Preprocessing Pipeline: Integrates SimpleImputer, StandardScaler, and OneHotEncoder within a ColumnTransformer to create a streamlined data preprocessing workflow.
End-to-End ML Pipeline: Constructs a complete Pipeline that combines data preprocessing with a LogisticRegression classifier, ensuring a robust and reproducible machine learning process.
Performance Optimization: Demonstrates how hyperparameter tuning across imputation strategies and model parameters can lead to improved classification accuracy.

# Technologies Used:
Python
Pandas (for data manipulation)
NumPy (for numerical operations)
Scikit-learn (for machine learning pipelines, imputation, scaling, encoding, and model selection)
Jupyter Notebook
