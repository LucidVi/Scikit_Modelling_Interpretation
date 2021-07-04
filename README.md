# Modelling in Scikit-learn and Feature Interpretation

The purpose of this notebook is to build different types of models and see how they perform on the same data going through the same preprocessing. Going further on this we also study the feature importances of the top performing models, one linear and one non-linear.

When building any sort of model on any data, it is important to be able to build secure and robust Data preprocessing pipelines. We achieve that objective using the sklearn Pipeline. It also makes it easy to quickly go through different types of model and run a GridSearch on them using k-folds method.

Four different models are built, Elastic Net Regression, Support Vector Machine, Decision Trees and XGBoostRegressor.

The Feature interpretation is perfromed on the ElasticNet and XGBoost models.
