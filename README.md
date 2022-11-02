# Project Name: Advanced-Regression
> Predict House Price


## Problem Statement:
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Steps
- Reading, understanding and visualising the data
- Preparing the data for modelling (split training and testing data, rescaling etc.)
- Train the model
- Residual Analysis
- Predictions and evaluation on test set


## Conclusions
Though the model performance by Ridge Regression was better in terms of R2 values of Train and Test, it is better to use Lasso, since it brings and assigns a zero value to insignificant features, enabling us to choose the predictive variables.
It is always advisable to use simple yet robust model.

Hence the equation:
Log(Y) = C + 0.125(x1) + 0.112(x2) + 0.050(x3) + 0.042(x4) + 0.035(x5) + 0.034(x6) + 0.024(x7) + 0.015(x8) + 0.014(x9) + 0.010(x10) + 0.010(x11) + 0.005(x12) - 0.007(x13) - 0.007(x14) - 0.008(x15) - 0.095(x16) + Error term(RSS + alpha * (sum of absolute value of coefficients)¶


## Technologies Used
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- statsmodels


## Contact
Created by [@Rameshkatiyar] - feel free to contact me!
