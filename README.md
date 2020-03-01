# Decision_Trees

1. It is a non-linear model.

2. Logic tree that functions on feature values.

3. Stops at maximum depth value

As the maximum depth of a particular decision tree keep on increasing, the fineness or the performance increases.
Below are two trees with increasing order of max depths respectively.


a)

![Dtree1](https://user-images.githubusercontent.com/55191934/75621751-671ba400-5bbe-11ea-98e7-67063d960333.PNG)

b)

![Dtree2](https://user-images.githubusercontent.com/55191934/75621753-7864b080-5bbe-11ea-8f63-3bf93faa8d07.PNG)


As the mean squared error keeps on decreasing with increasing number of maximum depths, so does the risk of overfitting and perfomring poorly on unseen data increase. Hence an optimum condition is required to be satisfied.


![Dtree3](https://user-images.githubusercontent.com/55191934/75621771-be217900-5bbe-11ea-82ef-2e23cc247da6.PNG)

Using Grid Search Cross Validation method: which provides an optimum case of max_tree depth value on splitting data into 
train and test data. 



![Dtree4](https://user-images.githubusercontent.com/55191934/75622448-638c1b00-5bc6-11ea-9932-ee619cd19307.PNG)

And hence using the optimum plot via GridSearchCV:

![Dtree5](https://user-images.githubusercontent.com/55191934/75622463-8a4a5180-5bc6-11ea-8be5-3682f9a99202.PNG)


