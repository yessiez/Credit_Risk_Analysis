# Credit_Risk_Analysis

## Overview

The purpose of this analysis was to use imbalanced-learn and scikit-learn libraries to build, train, and evaluate the performance of the models in order to accurately predict credit risk.

### The machine learning algorithms used in the analysis:

#### Oversampling

- Naive Random Oversampling
- SMOTE Oversampling

#### Undersampling

- Cluster Centroid Undersampling
- SMOTEENN Sampling

#### Classifying

- Balanced Random Forest Classifying
- Easy Ensemble Classifying

## Results

### Naive Random Oversampling

- Accuracy Score: 64%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 61%
- Recall Low Risk: 68%

![ro](https://github.com/yessiez/Credit_Risk_Analysis/blob/master/visualizations/naiverandom.png?raw=true)

### SMOTE Oversampling

- Accuracy Score: 62%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 60%
- Recall Low Risk: 64%

![smote](https://github.com/yessiez/Credit_Risk_Analysis/blob/master/visualizations/SMOTE.png?raw=true)

### Cluster Centroid Undersampling

- Accuracy Score: 52%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 60%
- Recall Low Risk: 43%

![centroid](https://github.com/yessiez/Credit_Risk_Analysis/blob/master/visualizations/clusteredcentroid.png?raw=true)

### SMOTEENN Sampling

- Accuracy Score: 62%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 69%
- Recall Low Risk: 55%

![smoteenn](https://github.com/yessiez/Credit_Risk_Analysis/blob/master/visualizations/SMOTEENN.png?raw=true)

### Balanced Random Forest Classifying

- Accuracy Score: 79%
- Precision High Risk: 4%
- Precision Low Risk: 100%
- Recall High Risk: 67%
- Recall Low Risk: 91%

![brf](https://github.com/yessiez/Credit_Risk_Analysis/blob/master/visualizations/balanced_random_forest.png?raw=true)

### Easy Ensemble Classifying

- Accuracy Score: 93%
- Precision High Risk: 7%
- Precision Low Risk: 100%
- Recall High Risk: 91%
- Recall Low Risk: 94%

![easyensemble](https://github.com/yessiez/Credit_Risk_Analysis/blob/master/visualizations/easy_ensemble.png?raw=true)

## Analysis