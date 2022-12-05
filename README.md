# Life Expectancy Prediction
The current project aims at predicting the life expectancy of a country given its main health indexes using linear regression (Vanilla, Ridge, Lasso) and ensemble methods (Bagging, Random Forest, XGBoost). 
Dico che due parti progetto -> EDA (focus on removing outliers and missing values handling e ) e Modelli
Dico che c'è anche un ppt (che in realtà non c'è ancora)

## Dependencies
Dire di guardare il file requirements.txt

## Dataset
Dire da dove l'ho preso (WhO), che file è (il csv)
E che ho description delle feature nel file Dataset_description.txt

## Models
dico quali ho fatto e dico che li ho salvati nella folder model con i parametri scelti

## Results
EDA has significally improved the performance of the model (MSE on the test set dimished by 21%). -> outliers handling and missing values handling
Ensemble models showed much better performance with respect to linear regression (MSE on the test set dimished by 36%).

The best ensemble model (XGBoost) allowed to reduce MSE on the test set up to 36% with respect to the best regression model (Ridge).




