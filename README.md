# Electrical-Grid-Stability-Prediction

The classification of the stability label of the system (categorical: stable/unstable) is done in this mini-project using a Random Forest Classifier which is an ensemble learning method that gives the best classification outcome. 

# Pseudocode

1. Downloading and loading the Electricity Grid Stability Prediction model from the UCI Machine Learning Repository. 
https://archive.ics.uci.edu/ml/datasets/Electrical+Grid+Stability+Simulated+Data+

2. Preprocessing the dataset using a labelencoder from the sklearn machine learning library of python to transform the categorical target variable. Null values are also checked and removed from the dataset. 

3. Dataset is split using the sklearn preprocessing function called the train_test_split, the random classifier model is loaded and then the training dataset is fit on to the random forest classifier. 

4. The testdata is used for predicting the test data and analysing the evaluation metrics by comparing the test values and the predicted values. 

# Outcome
The random forest classifier is successful enough to give an accuracy of 99.96% on the dataset. 
