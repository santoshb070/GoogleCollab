
# Logistic Regression

Logistic Regression also called as a sigmoid function
Sigmoid function is an S-Shaped curve that can take any real valued number and put them in between 0 and 1.
But never exactly at those limits

## Logistic Function = 1 / (1 + e^x-value)

where e is the base of natural algorithm

Below is an example logistic regression equation:

y = e^(b0 + b1*x) / (1 + e^(b0 + b1*x))

Where y is the predicted output, b0 is the bias or intercept term and b1 is the coefficient for the single input value (x). Each column in your input data has an associated b coefficient (a constant real value) that must be learned from your training data.
