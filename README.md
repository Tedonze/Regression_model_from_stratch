# Regression model from Stratch

Compute linear, ridge and poisson  from stratch in python 

## Linear regression: 
$$\hat\beta = (X^TX)^{-1}X^Ty$$

## Ridge regression : 
$$\hat\beta= (X^{T}X + \lambda I)^{-1}X^Ty $$

## Poisson Regression :  
$$\frac{\partial L(\beta)}{\partial \beta} = X^T(y-\hat y)$$
$$\hat y = \exp(X^T\beta)$$
