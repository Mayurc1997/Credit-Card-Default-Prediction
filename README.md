
#Credit-Card-Default-Analysis

## Problem Description​

This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. We can use the K-S chart to evaluate which customers will default on their credit card payments​

## Key Findings from EDA

1.Males have more delayed payment than females in this dataset. Keep in mind that this finding only applies to this dataset, it does not imply this is true for other datasets.
2.Customers with higher education have less default payments and higher credit limits.
3.Customers aged between 30-50 have the lowest delayed payment rate, while younger groups (20-30) and older groups (50-70) all have higher delayed payment rates. However, the delayed rate drops slightly again in customers older than 70.
4.There appears to be no correlation between default payment and marital status.
5.Customers being inactive doesn’t mean they have no default risk. We found 317 out of 870 inactive customers who had no consumption in 6 months then defaulted next month.

## MODEL BUILDING​

# CONCLUSION
To identify the default payment of credit card clients of huge data sets data analysis should be involved. Data analysis allows cultivation and learning based on model build, feature extraction, and various conditions that can improve the trait of customer acquirement. The four machine learning techniques mentioned can analysis the huge data set and to provide the accurate result. The boosting techniques which are included here can perform analysis for imbalanced dataset. By using Predictive analysis model for estimating the default payment and loss of extend and for predicting losses. In this paper, Machine learning technique like Logistic regression, XGBoost, SVC and Random forest were used to detect the fraud in credit card system. Sensitivity, Specificity, accuracy and error rate are used to evaluate the performance for the proposed system. The accuracy for logistic regression, XGBoost, SVC and random forest classifier are 79%,86%,82% and 86% respectively. By comparing all the three method, found that random forest classifier is better than the logistic regression and decision tree. XGBoost provided us the best results giving us a recall of 85% percent(meaning out of 100 defaulters 85 will be correctly caught by XGBoost).
