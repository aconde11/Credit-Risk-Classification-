# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    * The purpose of this analysis is to create and evaluate the accuracy of a data model that predicts credit of potential borrowers from peer to peer lending services. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
* Balanced accuracy score: 95.20%- this means that when taking into account the sensitivity and specificity of the model, the balanced prediction accuracy was 95.2%.
* Precision Score: 92%- this means 92% of predictions were correct.
* Recall Score: 95%- this means that the model was 95% precise in measuring the ture positive values of all positive predictions made.

 *Machine Learning Model 2:
 *Acording to the model, recall score made 1% of mistakes when predicting healthy loans and made 1% of mistakes when predicted non-healthy loans.
 *The model generated an accuracy score of 99% due to a balanced dataset. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

*The logistic regression model fitted with OverSampled data performed much better than the model fitted with Imbalanced data due to the data being balanced and generating a higher accuracy score and a higher recall, indication that the model will make less mistakes when classifying non-healthy loans.

*The lending company would most likely want less false positives due to the high posibility of a lender loosing funds when classifying non-healthy loans as healthy.