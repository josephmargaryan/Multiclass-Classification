A sequence of steps have been caried out to create a voting classifier.
Problem statement: 
- To carry out a machine learning model optimized for multiclass classification
Steps:
- Multiple instances of different boosting algorithms were instantiated, hereby: LGBM, eXGBM, CatBoost
- Hyperparameter tuning was done using Optuna.
- A voting classifier was instansiated to combine the predictions from the various boosting algorithms
- Final predictions were made on the unseen test data
