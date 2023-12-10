Laptop Price Prediction Machine Learning Pipeline

Developed Machine Learning pipeline based on Kaggle Amazon Laptop Dataset.

Preprocessed the continuous data with StandardScaler and categorical data with OneHotEncoder.

Handled continuous missing values with IterativeImputer with LinearRegression or with XGBoost. 

Train Lasso, Ridge, Elastic Net, Random Forest, XGBoost ML algorithm to get the best RMSE. Cross validation using 4 Kfold, except for XGBoost. For XGBoost, the dataset is split into train : validation : test = 60 : 20 : 20, and the rest of the models' dataset is split into (train+validation) : test = 8 :2.

The best model algorithm is XGBoost with RMSE of 344.175. 

Libraries used:

    Python version is 3.11.4
    numpy version 1.24.4
    matplotlib version 3.7.2 
    pandas version 2.0.3
    scikit-learn version 1.3.0
    xgboost version 1.7.6
    shap version 0.42.1

# project-emlberman
