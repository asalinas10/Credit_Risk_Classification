# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).


The purpose of this analyis was to use machine learning as a way to predict healthy anf high risk loans. The model uses information such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and the total debt for each loan as features to predict our intnded outcome. The Logistic Regression model was used to predict the outcome. Furthermore I used a RandomOverSampler to resample the data and that model also did very well with an accuracy score of 0.99.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
Accuracy: 0.99
Precision 0: 1
Recall 0: 0.99
Precision 1: 0.85
Recall 1: 0.91



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
Accuracy: 0.99
Precision 0: 1
Recall 0: .99
Precision 1: 0.84
Recall 1: 0.99
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?

The second one did better as it had a higher recall rate than the the first model.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

Performance does depend on the problem as you would want to be able to identify more unhealthy scores accuratly as those have a much larger impact on interest rates than correctly identifying healthy scores.

If you do not recommend any of the models, please justify your reasoning.

I wouold recomend both models as they both scored very highly in accuracy, precisicon, and recall.