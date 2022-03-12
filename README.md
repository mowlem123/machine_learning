# machine_learning
Unit 11
## Files used: 
  -credit_risk_ensemble.ipynb, credit_risk_resampling.ipynb

# Credit Risk Resampling
---------------------------------------
# Credit Risk Resampling Techniques
# Read the CSV into DataFrame
# Split the Data into Training and Testing
## Data Pre-Processing

Scale the training and testing data using the `StandardScaler` from `sklearn`. Remember that when scaling the data, you only scale the features data (`X_train` and `X_testing`).

# Simple Logistic Regression
# Oversampling
1. View the count of the target classes using `Counter` from the collections library. 
3. Use the resampled data to train a logistic regression model.
3. Calculate the balanced accuracy score from sklearn.metrics.
4. Print the confusion matrix from sklearn.metrics.
5. Generate a classication report using the `imbalanced_classification_report` from imbalanced-learn.
### Naive Random Oversampling
### SMOTE Oversampling
# Undersampling
1. View the count of the target classes using `Counter` from the collections library. 
3. Use the resampled data to train a logistic regression model.
3. Calculate the balanced accuracy score from sklearn.metrics.
4. Display the confusion matrix from sklearn.metrics.
5. Generate a classication report using the `imbalanced_classification_report` from imbalanced-learn.
# Combination (Over and Under) Sampling
1. View the count of the target classes using `Counter` from the collections library. 
3. Use the resampled data to train a logistic regression model.
3. Calculate the balanced accuracy score from sklearn.metrics.
4. Display the confusion matrix from sklearn.metrics.
5. Generate a classication report using the `imbalanced_classification_report` from imbalanced-learn.
# Final Questions
​
1. Which model had the best balanced accuracy score?
​
   - Combination/Smote Model
​
2. Which model had the best recall score?
​
    - All Equal
​
3. Which model had the best geometric mean score?
​
    - All Equal.  Logistic Regression had the lowest of all the models. 
​



----------------------------------------------------------------
# Credit Risk Ensemble

# Ensemble Learning

## Initial Imports
## Split the Data into Training and Testing
## Data Pre-Processing
## Ensemble Learners
1. Train the model using the training data. 
2. Calculate the balanced accuracy score from sklearn.metrics.
3. Display the confusion matrix from sklearn.metrics.
4. Generate a classication report using the `imbalanced_classification_report` from imbalanced-learn.
5. For the Balanced Random Forest Classifier only, print the feature importance sorted in descending order (most important feature to least important) along with the feature score
### Balanced Random Forest Classifier
### Easy Ensemble Classifier
### Final Questions

1. Which model had the best balanced accuracy score?

    - EasyEnsembleClassifier

2. Which model had the best recall score?

    - EasyEnsembleClassifier

3. Which model had the best geometric mean score?

    - EasyEnsembleClassifier

4. What are the top three features?

    - total_rec_prncp, total_rec_int, total_rec_inv
    - The fourth and fifth top features were last_pymnt_amnt, and total_pymnt
