# Support Vector Regression

We fed the structural features into a support vector regression model.

To avoid overfitting, we applied regularization to the regression model and estimated the out-of-sample performance on enantiomeric pairs that the model was not trained on.

The results for strictly using Mordred features were as follows:

![mordred](./modelresults/mordred.png)

With a correlation metric value of 0.56:

![mordredc](./modelresults/modred_correlation.png)

The results for strictly using Morgan features were as follows:

![morgan](./modelresults/morgan.png)

With a correlation metric value of 0.57:

![morganc](./modelresults/morgan_correlation.png)

