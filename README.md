# Linear-Regression
1. First, use boston.corr() to show what features are correlated with each other.
2. The columns don't have any labels. This happens with some datasets. According to the
column values shown in https://www.kaggle.com/c/boston-housing, you need to label the
columns.
Note:
a. only label 13 columns (the Kaggle website has 14 labels for the columns), remove
the last one of 'medv' and use boston.corr() again if you are loading data from
Kaggle.
b. Medv column is already removed in sklearn.datasets package.
3. First, please split the data into two datasets as “training” dataset and “test” dataset by
train_test_split() with trainset of 80% and test of 20%. According to the hold-out method
taught in the classes, please train the model by linear regression.
4. Then, please predict new values using the test set.
5. Please print the coefficients for your model.
6. The sign of a regression coefficient tells you whether there is a positive or negative
correlation between each independent variable and the dependent variable. What do a
positive coefficient and a negative coefficient indicate respectively? (State your answer in a
text cell).
