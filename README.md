# Classification Metrics - Recap

## Introduction

In this section you learned about the different ways to evaluate classification models such as logistic regression.

## Classification Metrics

While precision, recall, and accuracy are useful metrics for evaluating classifiers, determining an appropriate balance between false positives and false negatives will depend on the particular problem application and the relative costs of each. For example, in the context of medical screening, a false negative could be devastating, eliminating the possibility for early intervention of the given disease. On the other hand, in another context, such as finding spam email, the cost of false positives might be much higher than false negatives -- after all, having a spam email sneak its way into your inbox is probably preferable then missing an important time-sensitive email because it was marked as spam. Due to these contextual considerations, you as the practitioner are responsible for selecting appropriate trade-offs.


## Key Takeaways

* You can evaluate logistic regression models using some combination of precision, recall, and accuracy
* A confusion matrix is another common way to visualize the performance of a classification model
* Receiver Operating Characteristic (ROC) curve and the Area Under the Curve (AUC) can be used to help determine the best precision-recall trade-off for a given classifier
* Class weights, under/oversampling, and SMOTE can be used to deal with class imbalance problems
