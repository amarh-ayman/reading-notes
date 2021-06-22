# Linear Regression

- A predictive analysis technique which uses a model(mathematical equation), that shows the relationship between the output(dependent variable _Y_) and the input (independent variable/s _X_, which determine/s the output).

- Formula(simplest):
  > y = c + b\*x

# How to run Linear regression in Python scikit-Learn?

### What is Scikit-learn?

> a powerful Python module for machine learning. It contains function for regression, classification, clustering, model selection and dimensionality reduction.

- In linear regression Scikit-learn is used mainly for fitting the model and predicting the output.

##### Things to do & functions to use:

    - **Import (LinearRegression) from sklearn.linear_model**
    - create a linear regression object

> - lm.fit() -> fits a linear model

- lm.predict() -> Predict Y using the linear model with estimated coefficients
- lm.score() -> Returns the coefficient of determination (R^2). A measure of how well observed outcomes are replicated by the model, as the proportion of total variation of outcomes explained by the model.

### Training and validation data sets

- data sets should to be split, such that a certain percentage is used for the purpose of training the model(getting the formula) and the remaining percentage (usually less than the training percentage) is used for the purpose of testing and validating the model.

> lm = LinearRegression()
> lm.fit(x_train, y_train)
> pred_train = lm.predict(x_train)
> pred_test = lm.predict(x_test)

#### Residual Plots

> Residual plots are a good way to visualize the errors in your data. If you have done a good job then your data should be randomly scattered around line zero
