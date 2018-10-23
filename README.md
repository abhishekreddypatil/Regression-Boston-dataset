# Regression-Boston-dataset
Learning to apply the machine learning basics of regression on the Boston Dataset.
Here we will apply the Multiple Linear regression for all the available features and see the resulting ROOTMEANSQUARE error.
we will then reduce the features not so important by the BACKWARD ELIMINATION method and check the RMSE value again!!

Regression with SVR
We applied SVR for the same dataset and predicted the X_test results! The error was a bit less than MultipleLinear Regression,Feature scaling is necessary for SVR

Regression with DecisionTree
We applied DecisionTree regressor for the dataset and found the error to be still less than the SVR

Regression with RandomForest
We applied RandomForest regressor for the dataset and found the error to be still less than the DecisionTree and as the n_estimators increase the error reduces, but as n_estimators increase the overfitting takes place!!

Another thing to remember is the Backward elimination method is only applied to MultipleLinear regression to know which feature is more important of all the independent variables!!
