# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

Summarr Report:


Machine Learning Model 1:

Accuracy: 0.99

It correctly classifies 99% of the instances.
Precision:

For healthy loans ('0'): 1.00
Perfectly identifies true positives with no false positives.
For high-risk loans ('1'): 0.87
Moderately effective in identifying high-risk loans with some false positives.
Recall:

For healthy loans ('0'): 1.00
Perfectly identifies all instances of healthy loans with no false negatives.
For high-risk loans ('1'): 0.89
Moderately effective in identifying high-risk loans with some false negatives.
Machine Learning Model 2:

Accuracy: 0.99

Correctly classifies 99% of the instances.
Precision:

For healthy loans ('0'): 0.99
Almost perfect at identifying true positives with few false positives.
For high-risk loans ('1'): 0.99
Almost perfect at identifying high-risk loans with few false positives.
Recall:

For healthy loans ('0'): 0.99
Almost perfect at identifying nearly all instances of healthy loans with few false negatives.
For high-risk loans ('1'): 0.99
Almost perfect at identifying high-risk loans with few false negatives.
Both models exhibit high accuracy and excellent precision and recall scores, making them well-suited for identifying healthy and high-risk loans. They are highly reliable in minimizing false positives and false negatives, demonstrating their effectiveness in credit risk assessment.