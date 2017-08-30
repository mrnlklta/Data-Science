A data-set of weather data collected for a period of three years in San Diego is used for the analysis. Used the 9am sensor data as features here to predict the humidity at 3 pm.

Performed train_test_split model to split the data-set, used GridSearchCV to find the optimum parameter values, used KFold cross-validation to evaluate the predictive model and finally used DecisionTreeClassifier to classify the humidity as high or low. Applied accuracy_score metrics to find the accuracy of the model.
