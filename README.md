# Implementation of Univariate Linear Regression
## Aim:
To implement univariate Linear Regression to fit a straight line using least squares.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the independent variable X and dependent variable Y.
2.	Calculate the mean of the X -values and the mean of the Y -values.
3.	Find the slope m of the line of best fit using the formula.
   ![Screenshot 2024-01-01 133627](https://github.com/23004345/Univariate-Linear-Regression/assets/138849203/55679efe-3c11-45d7-9d5b-dd8e905ec2a8)

4.	Compute the y -intercept of the line by using the formula:
   ![Screenshot 2024-01-01 133750](https://github.com/23004345/Univariate-Linear-Regression/assets/138849203/439a3746-bca0-4c8b-88e9-ff95c6036d8f)
  
5.	Use the slope m and the y -intercept to form the equation of the line.
6.	Obtain the straight line equation Y=mX+b and plot the scatterplot.
## Program:

import numpy as np

import matplotlib.pyplot as py

x=np.array([0,1,2,3,4,5,6,7,8,9])

x=np.array([9,8,7,6,5,4,3,2,1,0])

x_mean=np.mean(x)

y_mean=np.mean(y)

num,denom=0,0

for i in range (len(x)):

num+=(x[i]-x_mean)

print(m,b)

y_pred=(m*x)+b

print(y_pred)

py.scatter(x,y,color='pink')

py.scatter(x,y_pred,color='blue')

py.show()

## Output
![Screenshot 2024-01-01 134803](https://github.com/23004345/Univariate-Linear-Regression/assets/138849203/4c6d91af-5596-4499-a3de-51e19bda22cd)

## Result
Thus the univariate Linear Regression was implemented to fit a straight line using least squares.
