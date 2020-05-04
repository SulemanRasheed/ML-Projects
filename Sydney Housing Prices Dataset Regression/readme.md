# Regression on Sydney House Price Dataset

[Sydney Housing Dataset](https://www.kaggle.com/shree1992/housedata) contains info about housing prices in different cities of USA. And describe them by different attributes like size, city, floors, bathrooms, condition etc. The main aim of the project is to evaluate 4 different type of linear regression algorithms. In this exercise, we'll merely focus on three classification algorithms 
1. Linear Regression (Ordinary Least Square without any Regularization)
1. Ridge Regression
2. Lasso Regression
3. Elastic Net Regression

And to keep things simple, Coefficient of Determination i.e. R-2 is used as evaluation metric. The date and street column provide no useful info so we dropped them for simplicity.

This exercise is a part of Homework 2 of open source [applied ML course taught by Andreas Mueller](https://www.cs.columbia.edu/~amueller/comsw4995s20/schedule/). 

Note: Please make sure that you download the [dataset](https://www.kaggle.com/shree1992/housedata) and check the path of data.csv before using this notebook.