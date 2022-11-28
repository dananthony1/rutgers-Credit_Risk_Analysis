# Rutgers-Credit_Risk_Analysis

## Overview of Project

The purpose of this project is to develop and evaluate supervised machine learning models in Python. 

## Results

![NaiveRandomOversampling](/01-NaiveRandomOversampling.png "Naive Random Oversampling")
* Vehicle Length and Ground Clearance provide a non-random amount of variance to the mpg value.

![SMOTEOversampling](/02-SMOTEOversampling.png "SMOTE Oversampling")
* Vehicle Length and Ground Clearance provide a non-random amount of variance to the mpg value.

![Undersampling](/03-Undersampling.png "Undersampling")
* Vehicle Length and Ground Clearance provide a non-random amount of variance to the mpg value.

![CombinationSampling](/04-CombinationSampling.png "Combination Sampling")
* Vehicle Length and Ground Clearance provide a non-random amount of variance to the mpg value.

![BalancedRandomForestClassifier](/05-BalancedRandomForestClassifier.png "Balanced Random Forest Classifier")
* Vehicle Length and Ground Clearance provide a non-random amount of variance to the mpg value.

![EasyEnsembleAdaBoostClassifier](/06-EasyEnsembleAdaBoostClassifier.png "Easy Ensemble AdaBoost Classifier")
* Vehicle Length and Ground Clearance provide a non-random amount of variance to the mpg value.

## Summary and Model Recommendation

* The summary by Manufacturing Lot shows the summary statistic values grouped across each manufacturing lot. All three lots have 
similar means and medians near the value of ~1500. The variance increases across Lot 1 through Lot 3 from 0.98 to 7.47 to 170.29.
* The variance of Lot 3 exceeds the maximum value of 100 pounds per square inch. 