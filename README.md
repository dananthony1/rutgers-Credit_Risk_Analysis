# Rutgers-Credit_Risk_Analysis

## Overview of Project

The purpose of this project is to develop and evaluate supervised machine learning models in Python. 

## Results

![NaiveRandomOversampling](/01-NaiveRandomOversampling.png "Naive Random Oversampling")
* The Naive Random Oversampling method has a balanced accuracy score of 0.67.
* The average precision score is 0.99 and the average recall score is 0.60.

![SMOTEOversampling](/02-SMOTEOversampling.png "SMOTE Oversampling")
* The SMOTE Oversampling method has a balanced accuracy score of 0.65.
* The average precision score is 0.99 and the average recall score is 0.68.

![Undersampling](/03-Undersampling.png "Undersampling")
* The Undersampling method has a balanced accuracy score of 0.52.
* The average precision score is 0.99 and the average recall score is 0.40.

![CombinationSampling](/04-CombinationSampling.png "Combination Sampling")
* The Combination Sampling method has a balanced accuracy score of 0.66.
* The average precision score is 0.99 and the average recall score is 0.57.

![BalancedRandomForestClassifier](/05-BalancedRandomForestClassifier.png "Balanced Random Forest Classifier")
* The Balanced Random Forest Classifier method has a balanced accuracy score of 0.79.
* The average precision score is 0.99 and the average recall score is 0.87.

![EasyEnsembleAdaBoostClassifier](/06-EasyEnsembleAdaBoostClassifier.png "Easy Ensemble AdaBoost Classifier")
* The Easy Ensemble AdaBoost Classifier method has a balanced accuracy score of 0.93.
* The average precision score is 0.99 and the average recall score is 0.94.

## Summary and Model Recommendation

* The precision values are similar for all models averaging at 0.99
* The balanced accuracy ranges from 0.52 to 0.93.
* The recall varies from 0.40 to 0.94.
* The Easy Ensemble AdaBoost Classifier has the highest balanced accuracy and recall scores so it is the recommended model.