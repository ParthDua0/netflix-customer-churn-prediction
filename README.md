# Netflix Customer Churn Prediction 

A machine learning project built in Python utilizing Scikit-learn pipelines to predict subscriber churn with **89.70% Accuracy** and an **AUC score of 0.9682**.

## Key Features Implemented:
* **Robust Preprocessing:** Handled categorical encoding (`OneHotEncoder`) and continuous feature scaling (`StandardScaler`) dynamically inside a unified `ColumnTransformer`.
* **Data Leakage Protection:** Wrapped structural engineering and models within an end-to-end Scikit-Learn `Pipeline`.
* **Hyperparameter Optimization:** Utilized `GridSearchCV` paired with 5-Fold Cross-Validation to optimize regularization thresholds.
* **Explainable AI:** Extracted logistic regression coefficients to pinpoint top risk factors (like `last_login_days` and `Gift Card` usage) vs. loyalty anchors (like `avg_watch_time_per_day`).
