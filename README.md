# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1
import pandas as pd

Step2
import pandas as pd.

Step3
Get the value of X and y variables.

Step4
Create the linear regression model and fit.

Step5
predict the CO2 emission of a car where the weight is 2300kg, and the volume is 1300cm.

## Program:
```

Implementation of Multivariate Linear Regression
developed by:SUSHMITHA S
REG. NO.:212224230282
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars.csv")
x=df[['Weight','Volume']]
y=df['CO2']
regr=linear_model.LinearRegression()
regr.fit(x,y)
print('Coefficients: ',regr.coef_)
print('Intercept:',regr.intercept_)
predictedCO2=regr.predict([[3300,1300]])
print('Predicted CO2 for the corresponding weight and volume',predictedCO2)



```

### Insert your output

![Screenshot 2025-05-10 141231](https://github.com/user-attachments/assets/1ef96120-0778-4c25-9367-898f0a9091bb)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
