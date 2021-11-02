# 02 Linear Regression using Gradient Descent

Simple Linear Regression.ipynb shows how Simple Linear Regression is applied on a real world data set

Linear Regression using Gradient Descent.ipynb explains what Simple Linear Regression is and how Gradient Descent is used to find the best fit line

----------------------------------------------------------------------------------------------------------------------------------------------------------

The purpose of this project was to get familiar with Simple Linear Regression (LSR) and see how it is used in practice. Simple Linear Regression only has 2 variables:

- X : independent feature
- Y: dependent feature

Simple Linear Regression (SLR) is a regression model that estimates the relationship between one independent feature and one dependent feature using a straigt line.
- Best to apply Linear Regressin after variable standardization
- Uses Gradient Descent Algortihm to find the best fit line

**Y =wX +B**

Y = Dependent feature\
X = Independent feature\
w = weight\
b = Bias

This line calculates the best fit line for your model
- LR.fit(X_train,y_train)
- Which uses gradient descent 

**The score of our Train data should always be higher then our Test data else our model overfits**

## Loss Function
The loss is the error in our predicted of m and c. Our goal is to minimize this error to obtain the most accurance value of m and c.
We will use the Mean Squared Error function to calculate the loss. There are three steps in this function:

1. Find the difference between the actual y and predicted y value(y = mx + c), for a given x.
2. Square this difference.
3. Find the mean of the squares for every value in X.

## The Gradient Descent Algorithm
Gradient descent is an iterative optimization algorithm to find the minimum of a function. Here that function is our Loss Function.
