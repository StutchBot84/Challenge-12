# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of the anaylsis was to predict the precisiona and accuracy of the models to identify the creditworthiness of the borrowers.

* Explain what financial information the data was on, and what you needed to predict.
The data was from existing lending information. It contained info like loan size, interest rate, total debt etc. We needed to predict based off these factors if the loan was Healthy or High risk loan.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
These variables included loan size, total debt, num of accounts.

* Describe the stages of the machine learning process you went through as part of this analysis.
First split the data innto test and training. CReated a logistics model with the original data. Fitted a logistics model by using training data X_train and y_train
Then predicted s logistic regression model with resampled data.The predicted the accuracy.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
Used logistics regression model with resampled training data. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * Precision score for healthy loans was very good i.e. 1.
  * Precisison score for unhealthy loans was less precise only .87. This may be due to the fact that they occur much less often. 
  * This is backed up by the recall score .92 which is TP/(TP-FN).


* Machine Learning Model 2:
  *The precision score for the 2nd model increased to 1 high risk loans but feel by 0.01 for healthy loans. So the model decreased in precision on one side but increased significantly in precision for the other. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* The seond model seems predict best as its precision score is higher overall for both healthy and bad loans. 

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ) However it may be more important for a bank to be cautious and theerefore inncorrectly identify healthy loans as bad loans then the other way around. 

Recommendation: From a abanks perspecktive I might recommedn model 1 as it is more cautious in identifying a higer proportion of loans as unhealthy. 


