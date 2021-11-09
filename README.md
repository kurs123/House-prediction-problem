# House-prediction-proble
Find the presentation explaining all the steps done to achieve a good model to predict house prices.

<!--  -->The raw data contains attributes of king county houses.
<!--  -->
Algorithms used: Multiple Regression and Decision Tree.

Steps:
  ->EDA
  ->Regression
  ->Feature Transformation : log and square root transformation
  ->Feature Generation     : dummy variables, creating age of the house from the available predictors.
  ->Backward elimination 
  ->Forward selection through regression : using mlxtend library [scoring='r^2]
  ->Decision tree 
  ->Forward selection through decision tree [scoring='RMSE']
  ->For every step doing a 10-fold cv split and recording RMSE and r^2.
  
  ->Using the best model from above steps we get and use it on the test data.
  
