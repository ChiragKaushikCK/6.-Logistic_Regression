# 6.-Logistic_Regression

Logistic regression is a statistical model used for binary classification tasks. This means it predicts the probability of a categorical dependent variable taking on one of two possible outcomes (e.g., yes/no, true/false, 0/1).

Here's a simple breakdown:

It's a "Regression" but for Classification: Despite having "regression" in its name, logistic regression is primarily a classification algorithm. It uses a logistic function (also called the sigmoid function) to output a probability score between 0 and 1.

The Sigmoid Function: This S-shaped curve transforms any real-valued input into a value between 0 and 1. This output can then be interpreted as a probability.

Decision Boundary: Once the probability is calculated, a threshold (usually 0.5) is applied. If the probability is above the threshold, it's classified as one class; if below, it's classified as the other.

Linear Relationship (transformed): It models the log-odds of the dependent variable as a linear combination of the independent variables. This means that while the relationship between the inputs and the probability is non-linear (due to the sigmoid function), the underlying relationship on the log-odds scale is linear.

Example: Predicting if a customer will churn (Yes/No) based on their usage patterns and demographics. The model would output a probability (e.g., 0.8 for churning), and if that's above 0.5, it predicts "Yes, churn."
