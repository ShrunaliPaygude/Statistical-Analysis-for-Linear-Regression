# National Football League Case-Study: Statistical-Analysis-for-Linear-Regression
We have National Football league data which is provided in the data section, and we have to construct statistical analysis for linear regression and answer some questions related to the data.
I will be using Minitab for the analysis part, you can use R or SAS for the same!
For any queries regarding using minitab, please get in touch with me via https://github.com/ShrunaliPaygude

a. Fitting a multiple linear regression model relating the number of games won to the
team’s passing yardage (x2), the percentage of rushing plays (x7), and the opponents’
yards rushing (x8).

![image](https://user-images.githubusercontent.com/47711486/136078159-9578e24b-8b83-41be-a0f5-dbe8f73d76aa.png)
![image](https://user-images.githubusercontent.com/47711486/136078244-cffc8a08-57de-4f38-87a7-2455732b79dc.png)

As we see above, we have fit a multiple linear regression model relating the number of games
won to the team ’ s passing yardage ( x2 ), the percentage of rushing plays ( x7 ), and the
opponents ’ yards rushing ( x8 ).
The regression equation for the model is:
y= -1.81 + 0.003598 x2 + 0.1940 x7 - 0.00482 x8

# Testing for significance of variance
b. Constructing the analysis-of-variance table and test for significance of regression.

![image](https://user-images.githubusercontent.com/47711486/136078398-daa50789-d9bb-4446-af3a-55b086c01c61.png)

Above we can see the analysis of the variance table for the given multiple linear regression
model.
Looking at P-value for the Regression, we see that the p-value is less than 0.05. This shows
that we reject the null hypothesis and the Regression is significant.

# T-test statistics:

c. Calculate t statistics for testing the hypotheses H0: β2 = 0, H0: β7 = 0, and
0. What conclusions can you draw about the roles the variables x2, x7, and x8
the model?
![image](https://user-images.githubusercontent.com/47711486/136078530-cbbe31a0-3a57-4f1b-835a-fddb4b7f68bb.png)
![image](https://user-images.githubusercontent.com/47711486/136078557-73c52cc0-ee19-4aea-a9c7-e8810070d675.png)


Above is the statistics for testing the hypothesis H0 : β2 = 0, H0 : β7 = 0, and H0 : β8 = 0.
Looking at the p-values for x2, x7 and x8, we can conclude that all the p-values are less than
0.05. This means that all of the variables contribute to making the multiple linear regression
significant.
1. For H0 : β2 = 0: T-value: 5.18
Looking at p-value, <0.05, we reject the null hypothesis.
Therefore the regression is significant at 5%.
2. For H0: β7 = 0: T-value: 2.20
Looking at p-value, <0.05, we reject the null hypothesis.
Therefore the regression is significant at 5%
3. ForH0: β8 = 0: T-value: -3.77
Looking at p-value, <0.05, we reject the null hypothesis.
Therefore the regression is significant at 5%

# Calculating R2

d. Calculate R2 and for this model.
e. Using the partial F test, determine the contribution of x7 to the model. How is this
partial F statistic related to the t test for β7 calculated in part c above?

![image](https://user-images.githubusercontent.com/47711486/136078701-824cfcba-e724-4649-8623-254eb08d14fa.png)


For x7,
F-test: 4.83, p-value: 0.038
X7 contributes as: Looking at p-value, <0.05, we reject the null hypothesis.
Therefore the regression is significant at 5%

************************************************************************************************************************************
# Pinot wine case study and Statistical Analysis

The quality of Pinot Noir wine is thought to be related to the properties of clarity, aroma,
body, flavor, and oakiness. 
Which is a good regressor?

![image](https://user-images.githubusercontent.com/47711486/136080156-1d448d2b-6d61-4320-9b9f-b58ccd5832f8.png)

After fitting multiple linear regression model relating wine quality to these regressors, we get the
model equation as :
Y = 4.00 + 12.34 x1 + 0.483 x2 + 0.273 x3 + 1.168 x4 - 0.684 x5

# Testing for significance of regression. What conclusions can we draw?

![image](https://user-images.githubusercontent.com/47711486/136080311-96d97c09-0404-4047-9767-6cf45214fcb8.png)

Looking at the p-value for the regression, we see that the value is less than 0.05. These findings
help us state that we reject the null hypothesis and our regression is significant.

Conclusions:
The level of significance is 0.05
MSR=22.3081
MSE=1.3515
Fstat= MSR/MSE=16.5061
There is a linear relationship between the variable Y and variable x1, x2, x3, x4, x5

# Using t tests to assess the contribution of each regressor to the model and discussing the findings.

![image](https://user-images.githubusercontent.com/47711486/136080496-6c871ce9-37b8-4f59-bc46-73f3458b0a98.png)

The null and alternative hypothesis of each regressor is as follows,
H0:β1=0
H1:β1キ0


x1:
P-value =0.187>0.05, we fail to reject the null hypothesis
T-test=1.35
X1 is not statistically linear of the dependent variable.


X2:
P-value =0.086>0.05, we fail to reject the null hypothesis
T-test=1.77
X2 is not statistically linear of the dependent variable.


X3:
P-value =0.418>0.05, we fail to reject the null hypothesis
T-test=0.82
X3 is not statistically linear of the dependent variable.


x4:
P-value =0.001<0.05, we reject the null hypothesis
T-test=3.84
X4 is statistically linear of the dependent variable.


X5:
P-value =0.017<0.05, we reject the null hypothesis
T-test=2.52
X5 is statistically linear of the dependent variable.


So only x4 and x5 are statistically significant variables to the model.
We can rewrite the equation as:
Y= 1.168X4-0.684X5

# Calculating R2 and RAdj 2 for this model. Comparing these values to the R2 and RAdj 2 for the
# linear regression model relating wine quality to aroma and flavor. Discussing the results.

R-sq and R2 for the model is:

![image](https://user-images.githubusercontent.com/47711486/136080801-34691574-3445-4961-85e8-e5c93052373d.png)

R-sq: 72.06%
R-sq adj: 67.69%

Now, for linear regression model relating wine quality to aroma and flavor

![image](https://user-images.githubusercontent.com/47711486/136080941-de4227fb-72ef-4283-84a7-985d5a733525.png)

R-sq: 65.86%
R-sq adj: 63.9%
Looking at the above values, we can conclude that there is not much difference between both
the values of R sq and R sq adj for the model and when only relating wine quality to aroma and
flavor.




