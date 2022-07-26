# Air Pollution in Beijing: What Causes Particulate Matter?
CIND 820 - Big Data Analytics Project   
Erica Thompson-Becker  
501144405    
  
  
PM2.5, fine particulate matter, smaller than 2.5 micrometers, also known as particle pollution.  A great risk to the health of the planet and all life on it. Once a particle is inside the body, it is very hard to expel and may get trapped in the lungs or bloodstream. Knowing the causes of this deadly pollution can help to decrease the source and the publics exposure. 

Three regression models are attached to help solve this problem. Multiple linear regression, ridge regression and random forest regression are used and compared to find the best model and see how PM2.5 depends on other air pollutants and meteorological effects. 


Initial Analysis was done usign R programming Language
  - InitialAnalysis folder contains univariate and bivariate analysis done in R
  
Data Preparation 
  - data preparation file contains the code used to prepare the data to be used in the regression analysis
  - the data sets created during this stage are located in the data set folder and has a markdown file explaining which each data set is made of
  - due to the time series for the cross validation the train and test sets were separated manually using rolling cross validation on 3 month test (blocked cross-validation is also being considered) 

Regression Analysis was done using Python Programming Language    
- each folder contains code and results of the code and analysis 

  - MLR folder contains multiple linear regression analysis 
  
  - Random Forest folder contains Random forest regression analysis 

  - a third folder will be created once the next regression analysis is preformed



      



