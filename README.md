# Cross-Validation-techniques
Python Code for different Cross Validation Techniques on heart attack prediction dataset on kaggle.

## Overview (CV techniques) :

### 1. Hold Out Validation Approach :
Simplest split, in this we usually do a train and test split. This means that suppose you have a dataset we try to do train-test split, we train our model with the training      dataset and we validate our model with the test dataset.
### 2. Leave One Out Cross Validation (LOOCV) :
Taken to another extreme, k may be set to the total number of observations in the dataset such that each observation is given a chance to be the held out of the dataset. This is called leave-one-out cross-validation, or LOOCV for short.
### 3. K-Fold Cross Validation :
K-fold cross validation we can make k splits. It split dataset into k consecutive folds (without shuffling by default). Each fold is then used once as a validation while the k-1 remaining folds form the training set.
### 4. Stratified K-fold Cross Validation : 
Stratified k-fold cross-validation is same as just k-fold cross-validation, But in Stratified k-fold cross-validation, it does stratified sampling instead of random sampling. The splitting of data into folds may be governed by criteria such as ensuring that each fold has the same proportion of observations with a given categorical value, such as the class outcome value.
### 5. Repeated Random Test-Train :
This technique is a hybrid of traditional train-test splitting and the k-fold cross-validation method. In this technique, we create random splits of the data in the training-test set manner and then repeat the process of splitting and evaluating the algorithm multiple times, just like the cross-validation method.
