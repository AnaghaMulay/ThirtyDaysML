# ThirtyDaysML

Today I had enough time and was kind of bored of reading and impementing the same Regression model since last 3-4 days(kept reading about regression models 2 days before starting the 30 Day challenge).
So I decided to complete all the remaining problems realted to Linear Regression today. After mean square error, also completed problems related to the coeffecient and intercept of linear regression.

### Mean squared error

This measures how close the regression line is to the data points in the dataset. Formula is as follows:

MSE = (1/n) * Σ(actual – forecast)2

### Intercept of linear regression

for multiple independent variables, where linear equation is y = b0 + b1X1 + b2X2 + ...,

b0 is the intercept and it's formula is as follows:

b0 = mean(y) - [b1*mean(X1) + b2*mean(X2) + ...]

Link for Question : https://machinehack.com/practices/intercept-of-a-linear-regression-model-da925/description

### Coeffecient of regression

Here, b1, b2, b3 etc are the coeffecients of independent variables X1, X2, X3, ... etc respectively.

the value of bi where i =1,2,3...(no. of variables that are independent) is given as :

bi = Σ [ (xi – x)(yi – y) ] / Σ [ (xi – x)2]

Link for Question : https://machinehack.com/practices/coefficient-of-a-linear-regression-model-eb4e4/description

These can be directly implemented using the LinearRegression() function from sklearn.linear_model package. This function has attributes coef_ and intercept_ for calculating
coeffecients and intercepts of the linear model respectively. For MSE, I also calculated using my own user defined function apart from mean_square_error() function from the package.

Sample Input for MSE code - [1,2,3,5]
                            [2,3,4,5]
                            
                            
You acn find the solution on the following link : https://github.com/AnaghaMulay/ThirtyDaysML/blob/main/Day_2_Intercept_Correlation_and_MSE.ipynb                            
                            
                            

