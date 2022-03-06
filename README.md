# Credit Risk Analysis

## Overview of the analysis

> Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes.

In this project, imbalanced-learn and scikit-learn libraries have been used to build models and evaluate them using a resampling method. The data is first oversampled by using randomoversampler and SMOTE algorithms and undersampled with the clustercentroid algorithm. Then, a combination approach is applied to oversample and undersample by using SMOTEENN. At last, the two machine learning models are compared and evaluated by using minimize bias, Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier. 

## Results

Naive Random Oversampling Results
- Balanced Accuracy Test: 65.38%
- Precision: 99%
- Recall: 74%

![](/Resources/1.png)

SMOTE Oversampling Results
- Balanced Accuracy Test: 66.17%
- Precision: 99%
- Recall: 69%

![](/Resources/2.png)

Undersampling Results
- Balanced Accuracy Test: 66.17%
- Precision: 99%
- Recall: 69%

![](/Resources/3.png)

Combination (Over and Under) Sampling Results
- Balanced Accuracy Test: 54.43%
- Precision: 99%
- Recall: 57%

![](/Resources/4.png)

Balanced Random Forest Classifier Results
- Balanced Accuracy Test: 75.89%
- Precision: 99%
- Recall: 86%

![](/Resources/5.png)

Easy Ensemble AdaBoost Classifier Results
- Balanced Accuracy Test: 91.79%
- Precision: 99%
- Recall: 94%

![](/Resources/6.png)

## Summary

As can be seen from the results above, Easy Ensemble AdaBoost Classifier model has the highest accuracy rate and the the precision and recall are high as well. 

As can be concluded, the Easy Ensemble AdaBoost Classifier model is recommended to use. 
