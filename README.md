# Brazil_Municipalities

This exploratory data analysis project aims to determine factors affecting the unequal development of Brazil at the municipality level. 

The relationship between explanatory variables and GDP per capita is modelled by a multi-linear regression model, where some variables undergo transformation to better fit the model. To account for spatial autocorrelation between municipalities, Geographically Weighted Regression is adopted in formulating the linear model. 

We find that the coefficient estimates for the explanatory variables remain statistically significant even in local linear models. 

We observe a variation in residuals between municipalities of different sizes. The actual values of GDP per capita in large areas are more than the predicted values and the actual values of GDP per capita in small areas fall below the predicted values.

In this project, we will utilize the data analysis tools and representations:
1. Correlation Plots of all variables
2. Histogram Plots of explanatory variables
3. Multi-Linear Regression Model (Global and Local - Geographically Weighted Regression)
4. Assumption Testing for the Linear Regression Models
5. Choropleth Maps of GDP per capita, residuals and standard errors
