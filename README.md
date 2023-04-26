# Titanic-with-XGBoost
This main model contains of:
- Data Splitting
1. Normal method:
- Preprocessing with ColumnTransformer
- Pipeline with XGBoostClassifier with n_jobs=-1, random_state=42
- Training with RandomizedSearchCV and random_search_params
- Evaluate
2. Polynomial method:
- Preprocessing with ColumnTransformer and poly=2
- Pipeline, Training, and Evaluate like normal method
