# Life Expectancy Prediction
The current project aims at predicting the life expectancy of a country given its main health indexes using linear regression (Vanilla, Ridge, Lasso) and ensemble methods (Bagging, Random Forest, XGBoost). 
The first part of the project is focused on exploratory data analysis (outliers and missing values handling), while the second part is focused on implementing different models to accomplish the project aim.

## Dependencies
A list of the packages used for this project is included in the file requirements.txt

## Dataset
The dataset used (Life_Expectancy_Data.csv) is a public dataset made available by the World Health Organization (WHO) for the purpose of health data analysis. 20 predictor variables for 193 countries from year 2000 to 2015 were considered to predict life expectancy. A description of the dataset features is included in the file Dataset_description.txt

## Models
dico quali ho fatto e dico che li ho salvati nella folder model con i parametri scelti

## Results
EDA has significally improved the performance of the model (MSE on the test set dimished by 21%). -> outliers handling and missing values handling
Ensemble models showed much better performance with respect to linear regression (MSE on the test set dimished by 36%).

The best ensemble model (XGBoost) allowed to reduce MSE on the test set up to 36% with respect to the best regression model (Ridge).




