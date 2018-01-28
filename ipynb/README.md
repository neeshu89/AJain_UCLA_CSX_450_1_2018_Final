# AJain_UCLA_CSX_450_1_2018_Final

## Well Defined Problem Statement for Abalone Data Set

### Domain
This problem is drawn from the Abalone dataset from the UCI Machine Learning Database.

This data set has in the past been used to predict the age of the abalone using physical measurements of the abalone rather than the tedious task of dissecting, dying, and inspecting the shell of the abalone.

### Problem Statement
For an abalone, given knowledge about other physical attributes of the abalone, we will be able to use supervised learning to develop a regression model that can predict the age of the abalone

We will be particularly interested in understanding the association between `rings` with `length`, `whole weight` and `diameter`, while also taking into account the `sex` of the abalone. These are measurements that can be easily obtained from the abalone, so a prediction model using these variables would be ideal.

### Dataset and inputs
The dataset to be examined contains 8 measurements for 4177 abalone. See notebook for details


### Solution Statement
A solution to this problem will be a regression model such as a linear regression, a decision tree regressor, or a support vector regressor.


### Benchmark Model
Given that we seek a regression model, we will use a naive benchmark of the mean of number of rings * 1.5 as our target benchmark in predicting age. The ages (rings) are normally distributed.


### Performance Metric
Given that this is a regression task, we can measure the success of our model using the Mean Squared Error.
