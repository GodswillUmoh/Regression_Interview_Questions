# Regression_Interview_Questions

## Cheat Sheet
This session provides insights on some relevant issues often asked in regression.
---

## Pros and Cons: Regression
+ [Click Here to view Sheet](https://drive.google.com/file/d/1VmbBvjlPlxhB7eUj1iHGeNgsEXKLtprT/view?usp=drive_link)

---

## Regularization Intuition
+ [Click Here to view Sheet])(https://drive.google.com/file/d/1kdYNH6P9y5aQf13SOJti_-zCdrORAKHT/view?usp=drive_link)

## Solution to Overfitting

### Regularization is the solution to overfitting
> + Regularization in Simple Terms
> Regularization is a technique used in machine learning to prevent overfitting by adding a penalty to the model's complexity. It discourages the model from fitting the noise in the training data, ensuring it generalizes better to unseen data.

### Three Types of Regularization

> 1. L1 Regularization (Lasso Regression):
> + Adds the absolute values of the coefficients as a penalty term to the loss function.
> + Encourages sparsity by shrinking some coefficients to exactly zero, effectively performing feature selection.
> + Penalty: $𝜆∑∣𝑤𝑖∣$
