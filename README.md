# Credit_Risk_Analysis

## Overview of Project

In this project, our goal to use machine learning to predict credit risk. We are using supervised machine learning techniques. These six models are: Random Oversampling, SMOTE Oversampling, Undersampling,Combination Sampling and Ensemble Learners(these learners including Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier). We will compare the results, particularly with precision and recall rate, from these models and see which model fit our expectation.

### Results

From the original dataset, the count of low risk is 68470 and for the high risk is 347. This is probably coming from the nature of the loan applicants. If someone would like to apply for a loan, he/she probably has credit or background not too terrible so bring up the low-risk count much higher than the high-risk group. These two groups have a huge gap on the count so it will create bias in the model. To eliminating the bias coming from the imbalance counts, we focus on the functions to make the counts have less gap.

•	**Random oversampling**

Balanced accuracy score: 0.65

![loading page]( https://github.com/jkmom/Credit_Risk_Analysis/blob/main/Resources/Ada_boost.png)

•	**SMOTE Oversampling**

Balanced accuracy score: 0.66
![loading page]( https://github.com/jkmom/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png)

•	**Undersampling**

Balanced accuracy score: 0.54

![loading page](https://github.com/jkmom/Credit_Risk_Analysis/blob/main/Resources/Undersampling.png)

•	**Combination**

Balanced accuracy score: 0.67
![loading page](https://github.com/jkmom/Credit_Risk_Analysis/blob/main/Resources/Combination.png)

•	**Balanced Random Forest** 
Balanced accuracy score:0.79
 
![loading page]( https://github.com/jkmom/Credit_Risk_Analysis/blob/main/Resources/balanced_random_forest.png)

•	**AdaBoost**

Balanced accuracy score:0.93

![loading page]( https://github.com/jkmom/Credit_Risk_Analysis/blob/main/Resources/Ada_boost.png)



### Summary

Look at pre(precision), we can see the low risk have almost 1 (100%) in all models and very low rate (around 0.01) with high risk. Means the models are not very good at reading the high risk individuals. We will have a lot of False Positive with prediction high risk applicants. This means we are giving loans to someone they actually have bad credits. 

But if we look at rec(recall), AdaBoost and Random oversampling both have average 0.94 (94%). This means they have low false negative (think(wrong) on someone with bad credit) in the model. 

It depends on the loan institution. If they believe most people can fulfill the loan obligation and don’t want to miss any chance to give out loans, maybe they would use the recall ratio more than precision. 

In the condition I mention above, then AdaBoost and random oversampling will be our recommendation. 
