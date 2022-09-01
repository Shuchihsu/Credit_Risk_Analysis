# Credit_Risk_Analysis

## Overview of Project

In this project, our goal to use machine learning to predict credit risk. We are using supervised machine learning techniques. These six models are: Random Oversampling, SMOTE Oversampling, Undersampling,Combination Sampling and Ensemble Learners(these learners including Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier). We will compare the results, particularly with precision and recall rate, from these models and see which model fit our expectation.

### Results

From the original dataset, the count of low risk is 68470 and for the high risk is 347. This is probably coming from the nature of the loan applicants. If someone would like to apply for a loan, he/she probably has credit or background not too terrible so bring up the low-risk count much higher than the high-risk group. These two groups have a huge gap on the count so it will create bias in the model. To eliminating the bias coming from the imbalance counts, we focus on the functions to make the counts have less gap.

•	**Random oversampling**

**Balanced accuracy score: 0.65

![loading page]( https://github.com/jkmom/Credit_Risk_Analysis/blob/main/Resources/Ada_boost.png)

•	SMOTE Oversampling

Balanced accuracy score: 0.66
![loading page]( https://github.com/jkmom/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png)

•	Undersampling

Balanced accuracy score: 0.54

![loading page](https://github.com/jkmom/Credit_Risk_Analysis/blob/main/Resources/Undersampling.png)

•	Combination

Balanced accuracy score: 0.67
![loading page](https://github.com/jkmom/Credit_Risk_Analysis/blob/main/Resources/Combination.png)

•	Balanced Random Forest 
Balanced accuracy score:0.79
 
![loading page]( https://github.com/jkmom/Credit_Risk_Analysis/blob/main/Resources/balanced_random_forest.png)

•	AdaBoost

Balanced accuracy score:0.93

![loading page]( https://github.com/jkmom/Credit_Risk_Analysis/blob/main/Resources/Ada_boost.png)



### Summary

