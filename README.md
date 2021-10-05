# Statistical-Analysis-for-Linear-Regression
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


