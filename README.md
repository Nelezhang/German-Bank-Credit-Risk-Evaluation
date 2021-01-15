# German-Bank-Credit-Risk-Evaluation
Data: The German credit scoring data is a dataset provided by Prof. Hogmann. The data set has information about 1000 individuals, on the basis of which they have been classified as risky or not.

Goal: Compare the performance of various classification models on predicting the risk of the loans for 1000 individuals.

Approach: Compare the asymmetric cost for train and test set for 4 different classification models.

Major Findings: In this case, predictive power of Logistic Regression > Classification Tree > Neural Network. top 30% of the data with highest propensity will give us the largest net profit(with actual RESPONSE). So we can either set the cutoff value at 0.892(This can also been seen on a ROC curve plot) or use the top 30% of the validation data with top propensity to make a decision.
