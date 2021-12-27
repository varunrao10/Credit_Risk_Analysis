# Credit_Risk_Analysis
 Machine Learning

### Module 17 Credit Risk Analysis
**Deliverable1-2:** [resampling](credit_risk_resampling.ipynb) 

**Deliverable3:** [ensemble](credit_risk_ensemble.ipynb) 

## Overview of Credit_Risk_Analysis:
The purpose of this analysis is to understand how the different models of resampling and ensemble differ in calculating precision and recall for the same data set that analyzes whether a loan is low risk or high risk.

## Results:
Balanced Accuracy Scores for all 6 Models:
- RandomOversampler: 0.6627
- SMOTE: 0.6623 
- ClusterCentroids: 0.6623
- SMOTEENN: 0.5447
- BalancedRandomForestClassifier: 0.8017
- AdaBoostClassifier: 0.8017

## Summary:
Out of the 4 resampling models, the randomoversampler model performed the best. Out of the 2 ensemble models, both the balancedrandomforestclassifier and adaboostclassifier models performed the same. Overall the 2 ensemble models performed the best with a balanced accuracy score of 0.8017.

