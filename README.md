# EshanRatneshSrivastava_Datahack

## Summary
This project predicts the likelihood of individuals receiving xyz and seasonal flu vaccines using logistic regression. It involves data preprocessing, model training, evaluation with ROC AUC, hyperparameter tuning, and generating predictions for a submission file, ensuring accurate and probabilistic outputs for a multilabel classification problem.


## Model
MultiOutputClassifier with Logistic Regression

## Accuracy
ROC AUC for xyz_vaccine: 0.8344622191967325

ROC AUC for seasonal_vaccine: 0.8564267812388112

## Best Parameter

{'estimator__C': 0.1, 'estimator__solver': 'liblinear'}

### Best Score: 0.8429928427601675