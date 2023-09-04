# Module 12 Challenge Summary

## An overview of the analysis: 

In this analysis we will be comparing two machine learning models to try and predict credit quality of a mortgage borrower. To do so, we will be using logistical regression with the original data given and also oversampled data. To understand the differences and which model will work better, we will review the balanced accuracy scores and the precision and recall scores of both machine learning models.

## The results: 

* The original model is better at predicting healthy loans. When reviewing the accuracy report and precision score we see a score of 95%, however since this data is imbalanced, the number of healthy loans will outweigh the number of high-risk loans. 
* When reviewing the imbalanced classification report we can infer that the model predicts healthy loans 100% of the time and high-risk loans 85% of the time. 
* The largest difference between the resampled data and the original data is that the recall score for high-risk loans increased from 91% to 99%. This means that the resampled model does a better job at predicting which loans are actually high-risk instead of mislabeling them as healthy.
* In any case, the mislabeling of high-risk loans as healthy would be costly for the lender. If a borrower defaults on the loan, the mortgage company is going to lose money.

## A summary: 

In summary, the resampled model is preferable in this case based on the higher recall score and similar precision compared to the original model. 
