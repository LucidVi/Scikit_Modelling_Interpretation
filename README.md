# Modelling in Scikit-learn and Feature Interpretation

The purpose of this notebook is to build different types of models and see how they perform on the same data going through the same preprocessing. Going further on this we also study the feature importances of the top performing models, one linear and one non-linear.

When building any sort of model on any data, it is important to be able to build secure and robust Data preprocessing pipelines. We achieve that objective using the sklearn Pipeline. It also makes it easy to quickly go through different types of model and run a GridSearch on them using k-folds method.

Four different models are built, 
- Elastic Net Regression 
- Support Vector Machine 
- Decision Trees 
- XGBoostRegressor

The Feature interpretation is perfromed on the ElasticNet and XGBoost models.
For this purpose the methods used,
- ICE (Individual conditional expectation)
  * An ICE plot visualizes the dependence of the prediction on a feature for each instance separately, resulting in one line per instance that shows how the predictions change, compared to one line overall which we get in PDP(Partial dependence plots).
- SHAP(SHapley Additive exPlanations) Values
  * The idea of Shapely values originates from Game Theory. We can also think of it like, what is the ‘payout’ that we get from each predictor when it comes to finding the target variable or how much does the accuracy of these predictions change when that one variable in question is added to the model. We will be using SHAP which is an improvement on Shapely values.
