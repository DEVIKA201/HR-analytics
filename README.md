# HR-analytics
Project done as part of camp organised by ICFOSS (2023)

Analyzing HR data of an unnamed company to understand the salary statistics and predict the satisfaction level of the emplpoyees using Logistic Regression models. I've also calculated the accuracy of the model thus formed using confusion matrix and random forest classifier.
Here, the visualisation was done on the basics of the salary that were provided to the employees of that company. Through that, we were able to understand the difference in salaries of the employees that are likely to retain or leave that company. From it, we were able to draw the following conclusions:

*Satisfaction Level: Satisfaction level seems to be relatively low (0.44) in employees leaving the firm vs the retained ones (0.66)
*Average Monthly Hours: Average monthly hours are higher in employees leaving the firm (199 vs 207)
*Promotion in Last 5 Years: Employees who are given promotion are likely to be retained at firm

Later, the correlation features and output variables were removed from the copy of the data set under analysis and dummy variables were introduced to remove the categorical data(salary:high,low,medium)
This dataset is then fitted into the Logistic regression model and thus the y_pred was found. The accuracy of the same is also calculated.
