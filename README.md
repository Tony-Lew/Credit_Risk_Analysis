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
  
### Undersampling
![undersampling](https://github.com/Tony-Lew/Credit_Risk_Analysis/blob/main/Images/Undersampling.png)
  1. Balanced Accuracy:0.6277008271188627
  2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
  3. Recall: High/Low = .61/.45

### Combination Under-Over Sampling
![combo sampling](https://github.com/Tony-Lew/Credit_Risk_Analysis/blob/main/Images/Combo%20Sampling.png)
  1. Balanced Accuracy:0.5295655712277054
  2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
  3. Recall: High/Low = .70/.58

### Balanced Random Forest Classifier
![balanced random forest classifier](https://github.com/Tony-Lew/Credit_Risk_Analysis/blob/main/Images/Balanced%20Random%20Forest%20Classifier.png)
  1. Balanced Accuracy:0.7885466545953005
  2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
  3. Recall: High/Low = .70/.87
 
### Easy Ensemble AdaBoost Classifier
![easy ensemble adaboost classifier](https://github.com/Tony-Lew/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20AdaBoost%20Classifier.png)
  1. Balanaced Accuracy:0.9316600714093861
  2. Precision: The precision is low for High-risk and is high for Low-risk loans.
  3. Recall: High/Low risk = .92/.94

## Summary:

When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the best machine learning model to choose for further credit card analysis.
