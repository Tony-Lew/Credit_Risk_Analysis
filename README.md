# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques were used to train and evaluate models with unbalanced classes. Various libraries and algorithms were used to build and evaluate models using resampling including:

  1. imbalanced-learn
  2. scikit=learn
  3. RandomOverSampler
  4. SMOTE algorithms
  5. ClusterCentroids algorithm
  6. SMOTEENN algotithm
  7. BalancedRandomForestClassifier (bias reduction model)
  8. EasyEnsembleClassifier (bias reduction model)
  
## Purpose:

  1. Explain how a machine learning algorithm is used in data analytics.
  2. Create training and test groups from a given data set.
  3. Implement the logistic regression, decision tree, randomon forest, and support vector machine algorithms.
  4. Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
  5. Compare the advantages and disadvantages of each supervised learning algorithm.
  6. Determine which supervised learning algorithm is best used for a given data set or scenario.
  7. Use ensemble and resampling techniques to improve model performance.

## Results:

Here are the results for the six machine learning modules.

### Naive Random Oversampling
![naive random oversampling](https://github.com/Tony-Lew/Credit_Risk_Analysis/blob/main/Images/Naive%20Random%20Oversampling.png)
  1. Balanced Accuracy:0.6293939430565123
  2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
  3. Recall High/Low risk = .57/.68

### Smote Oversampling
![smote oversampling](https://github.com/Tony-Lew/Credit_Risk_Analysis/blob/main/Images/Smote%20Oversampling.png)
  1. Balanced Accuracy:0.6277008271188627
  2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
  3. Recall High/Low risk = .62/.63
  
####
