### Dataset
We use a data file abalone.csv. Abalones are marine snails. The dataset has been prepared
with the aim of making age predictions easier. Customarily, the age of abalone is determined by
cutting the shell through the cone, staining it, and counting the number of rings through a microscope.
But it is a tedious and time-consuming task. Therefore, other measurements, which are easier to
obtain, are used to predict age.

Attribute information:

Given is the attribute name, attribute type, the measurement unit, and a brief description. The number
of rings is the value to predict: either as a continuous value or as a classification problem.

Name / Data Type / Measurement Unit / Description
1. Length / continuous / mm / Longest shell measurement
2. Diameter / continuous / mm / Diameter of the shell calculated as perpendicular to length
3. Height / continuous / mm / Height of the shell with meat in shell
4. Whole weight / continuous / grams / Weight of whole abalone
5. Shucked weight / continuous / grams / Weight of meat
6. Viscera weight / continuous / grams / Gut-weight (after bleeding)
7. Shell weight / continuous / grams / Weight of the shell after being dried
8. Rings / integer / -- / Number of rings in a shell. (Adding 1.5 to the number of rings gives the
age of abalone in years
---
### Task

Write a python program to split the data from abalone.csv into train data and test data. Train data
contain 70% of tuples and test data contain the remaining 30% of tuples. Save the train data as
abalone-train.csv and save the test data as abalone-test.csv.

1. Use the attribute which has the highest Pearson correlation coefficient with the target attribute
Rings as an input variable and build a simple linear (straight-line) regression model to predict
rings. 

    a. Plot the best fit line on the training data where the x-axis represents the chosen attribute
    value and the y-axis represents Rings.
    
    b. Find the prediction accuracy on the training data using root mean squared error.
    
    c. Find the prediction accuracy on the test data using root mean squared error.
    
    d. Plot the scatter plot of actual Rings (x-axis) vs predicted Rings (y-axis) on the test data.
    
    
2. Build a multivariate (multiple) linear regression model to predict Rings. All the attributes
other than the target attribute should be used as input to the model.

    a. Find the prediction accuracy on the training data using root mean squared error.
    
    b. Find the prediction accuracy on the test data using root mean squared error.
    
    c. Plot the scatter plot of actual Rings (x-axis) vs predicted Rings (y-axis) on the test
    data. 

3. Use the attribute which has the highest Pearson correlation coefficient with the target
attribute Rings as input and build a simple nonlinear regression model using polynomial
curve fitting to predict Rings.

    a. Find the prediction accuracy on the training data for the different values of degree of
    the polynomial (p = 2, 3, 4, 5) using root mean squared error (RMSE). Plot the bar
    graph of RMSE (y-axis) vs different values of degree of the polynomial (x-axis).
    
    b. Find the prediction accuracy on the test data for the different values of degree of the
    polynomial (p = 2, 3, 4, 5) using root mean squared error (RMSE). Plot the bar graph
    of RMSE (y-axis) vs different values of degree of the polynomial (x-axis).
    
    c. Plot the best fit curve using the best fit model on the training data where the x-axis
    represents the chosen attribute value and the y-axis is Rings.


    d. Plot the scatter plot of the actual number of Rings (x-axis) vs the predicted number
of Rings (y-axis) on the test data for the best degree of the polynomial (p). Comment
on the scatter plot and compare it with that of in 1(d).

4. Build a multivariate nonlinear regression model using polynomial regression to predict
Rings. All the attributes other than the target attribute should be used as input to the model.
a. Find the prediction accuracy on the training data for the different values of degree of
the polynomial (p = 2, 3, 4, 5) using root mean squared error (RMSE). Plot the bar
graph of RMSE (y-axis) vs different values of degree of the polynomial (x-axis).
b. Find the prediction accuracy on the test data for the different values of degree of the
polynomial (p = 2, 3, 4, 5) using root mean squared error (RMSE). Plot the bar graph
of RMSE (y-axis) vs different values of degree of the polynomial (x-axis).
(Note: The best fit model is chosen based on the p-value for which the test RMSE is
minimum.)
c. Plot the scatter plot of the actual number of Rings (x-axis) vs the predicted number
of Rings (y-axis) on the test data for the best degree of the polynomial (p). Comment
on the scatter plot and compare it with that of in 1(d)



