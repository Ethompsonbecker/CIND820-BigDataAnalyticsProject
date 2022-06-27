# Multiple Linear Regression Analysis
Multiple linear regression is used to predict a dependent variable based on multiple independent variable. It is used to identify how the dependent variable changes when the independent variables change. Multiple linear regression follows the formula 
$$ y = \beta_0 + \beta_1 x_1 + \beta_2 x_2 + \beta_3 x_3 + ... $$

where y is the dependent variable, $\beta_0 $ is the y-intercept, when all independent variables are zero, $\beta_1 , \beta_2 , \beta_3$, ... are the regression coefficients when there is a change in the independent variable while all other variables are held constant, $x_, x_2,x_3$,... are the independent variables.

MLR-1: includes independent variables: SO2,NO2,CO,O3,TEMP,PRES,DEWP,RAIN,WSPM  
MLR-2: includes independent variables: SO2,NO2,CO,O3  
MLR-3: includes independent variables: PM10,SO2,NO2,CO,O3,TEMP,PRES,DEWP,RAIN,WSPM  
MLR-4: includes independent variables: PM10,SO2,NO2,CO,O3  

Table 1: comparison of the R-Squared  percentage values for 4 multiple linear regression analysis
|Trial|$R^2$(MLR-1)|$R^2$(MLR-2)|$R^2$(MLR-3)|$R^2$(MLR-4)|
|-----|-----------|-------------|-------------|----------|
|1|64.587521|	60.519397|	77.163401|	74.984176|
|2|65.518939|	62.895275|	81.834545|	80.553735|
|3|65.570667|	63.107072	|83.001708	|81.828777|
|4|66.074154	|63.396097 |	82.943777	|81.551227|
|5|65.887354|	62.574984|	83.182121|	81.665606|
|6|66.040386	|63.374326|	83.074757	|81.800576|
|7|66.264786|	64.094312|	83.057216|	81.923451|
|8|66.35649	|63.997212|	83.259501|	82.067954|
|9|66.360285|	63.933725|	83.455131|	82.256615|
|10|66.438704|	63.981096|	83.513509|	82.287043|
|11|66.434505|	63.925819|	83.55605	|82.321854|


R-squared shows the "goodness of fit" for a regression model.  
The results for the analysis including PM10 are much higher than those without it. 



Done in Python  
 

