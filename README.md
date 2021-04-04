# Credit_Risk_Analysis

## Overview of Analysis

The purpose of the current analysis is to analyze credit card risk for the company LendingClub. LendingClub is a peer-to-peer lending services company with large credit card datasets. The task is to oversample the data using RandomOverSample, SMOTE, ClusterCentroids, SMOTEEN, BalancedRandomForestClassifier, and EasyEnsembleClassifier from the imbalanced-learn and scikit-learn libraries in Python to investigate credit risk.

## Results

### RandomOverSample
- Balanced Accuracy Score: .64
- Precision
    - High Risk: .01
    - Low Risk: 1.00
- Recall
  - High Risk: .71
  - Low Risk: .56

### SMOTE Oversampling
- Balanced Accuracy Score: .66
- Precision
  - High Risk: .01
  - Low Risk: 1.00
- Recall
  - High Risk: .63
  - Low Risk: .68

### Undersampling
- Balanced Accuracy Score: .66
- Precision
  - High Risk: .01
  - Low Risk: 1.00
- Recall
  - High Risk: .63
  - Low Risk: .68

### SMOTEENN
- Balanced Accuracy Score: .64
- Precision
  - High Risk: .01
  - Low Risk: 1.00
- Recall
  - High Risk: .71
  - Low Risk: .57

### BalancedRandomForestClassifier
- Balanced Accuracy Score: .79
- Precision
  - High Risk: .03
  - Low Risk: 1.00
- Recall
  - High Risk: .70
  - Low Risk: .87

### EasyEnsembleClassifier
- Balanced Accuracy Score: .92
- Precision
  - High Risk: .05
  - Low Risk: 1.00
- Recall
  - High Risk: .93
  - Low Risk: .90

## Summary
Out of all of the oversampling analysis, the test that derived the best balanced accuracy score was the EasyEnsembleClassifier with .92. The test with the highest precision for identifying high risk credit was the RandomOverSample, SMOTE Oversampling, UnderSampling, and the SMOTEEN all with a score of .01. The test with the lowest risk precision for identifying credit was all of the tests above except for the EasyEnsembleClassifier. The test that identified the best high risk credit recall were the RandomOverSample and the SMOTEEN with .71. The test that identified the lowest credit risk recall was the EastEnsembleClassifier which was .90. 
