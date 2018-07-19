# Let's start Ensembling Methods with Bagging

- In this assignment you will learn to build a BaggingClassifier with DecisionTreeClassifier.

## Write a function `bagging` that:

- Takes input the features and target with default parameters.
- Then fits a bagging classifier with DecisionTreeClassifier with multiple n-estimators values such as in between 1-50.
- Plot a graph with n-estimators and the accuracy of model for train and test sets.
- Use random_state 9 and bootstrap=True
- Use max_samples and max_features to 0.67

### Parameters:

| Parameter | dtype | argument type | default value | description |
| --- | --- | --- | --- | --- |
| X_train | DataFrame | compulsory | | Dataframe containing feature variables for training|
| X_test | DataFrame | compulsory | | Dataframe containing feature variables for testing|
| y_train | Series/DataFrame | compulsory | | Training dataset target Variable |
| y_test | Series/DataFrame | compulsory | | Testing dataset target Variable |
| n_est | int | compulsory | | n_estimators |

### Returns:
None


Note : Please Compare your plot with the bagging_1.png in the images directory

https://github.com/commit-live-students/ensemble_methods_projects/blob/master/images/bagging_1.png
