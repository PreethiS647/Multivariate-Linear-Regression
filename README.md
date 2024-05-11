# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1
Import panda as pd

### Step2
Import linear model from sk learn

### Step3
Read the csv file

### Step4
Find the multivariate regression

### Step5
Display the output

## Program:
```

#Developed by: Preethi S
#Register Number: 212223230157

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))




```
## Output:


![image](https://github.com/PreethiS647/Multivariate-Linear-Regression/assets/147313372/7fc6851e-13ab-4cc6-8656-4f3e747fd413)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
