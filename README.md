# Credit_Risk_Analysis-
## Overview of Project

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.



### Summary
The oversampling, undersampling, and combination (SMOOTEENN) models all had a low accuracy score in the 50-60's range. Accuracy should be between 70-90%. I would not consider these machine learning models for prediction. The Easy Ensemble Classifier sampling has a 93% accuracy which is concern for overfitting the model. I would recommend using the Balanced Random Forest Classifier model as the accuracy is 80.3%
