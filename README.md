# Regularization-with-Ridge-Regression-anad-Lasso-Regression
Regularization pracitce using Rideg Regression and Lasso Regression

# Overview of Regularization

Regularization is a technique used to prevent overfitting and improve generalization of a model. Overfitting occurs when a model learns to capture noise or a random function in the training data, making it perform poorly on unseen data.

Regularization introduces a penalty term to the model’s loss function that discourages complex or large parameter values. This penalty encourages the model to choose simpler hypotheses, which often generalizes better to new, unseen data.

The most common regularization techniques are Ridge Regression and Lasso Regression.

1. **L2 Regression (Ridge Regression)** adds penalty to the loss function proportional to the square of the magnitude of the model’s weight. This penalizes large weights, effectively shrinking them towards zero. 
2. **L1 Regularization (Lasso Regression)** adds a penalty term to the loss function, but instead of using the square of the weight, it uses the absolute value of the weights. Resulting in some of the weights becoming exactly zero, effectively performing feature selection.

The main intuitive difference is L1 regularization tries to estimate the median of the data while L2 regularization tries to estimate the mean of the data. 
