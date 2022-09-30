# Prediction of Parameters Based on Time Series Data for Road Sensors
## Steps Used
## 1) Importing Libraries for Preprocessing
All the useful libraries were imported to preprocess the data to feed to the models
## 2) Reading the Data
Data was read from the dataset file
## 3) Seperating Data for Each Section
Data for each section was seperated and scanned for missing values and handled accordingly
## 4) Importing Regression Models
Many Regression models were used like CatBoostRegressor, XGBRegressor, AdaBoostRegressor, GradientBoostingRegressor but best performance was given by XGBRegressor
## 5) Applying Regeression Model on Each Section.
XGBRegressor was applied on each section to predict the parameters
## 6) Processing the output
Output was seperated into different lists to calculate RMSE
## 7) Calculating RMSE for each Parameter as well as for all predictions
RMSE was Calculated. RMSE came out to be 25.4836983359801 total
## 8) Comparison between Actual and Predicted values using Line Graphs
Comparison between Actual and Predicted values was shown by plotting various Line Graphs.
