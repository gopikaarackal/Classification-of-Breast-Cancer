# Classification-of-Breast-Cancer using Logistic Regression and KNN
dataset : Breast Cancer Wisconsin Diagnostic Dataset
Tool : Python
##DESCRIPTION
For the above dataset a binary logistic regression model is built as there are two classes(M and B). The model got good accuracy of 95% which correctly classified signifiant number of observations in the training dataset.
Also the Logistic Regression Model has an AUC close to 1.
For the same dataset a KNN model is also built with number of neighbors = 19. It has an overall accuracy = 92%. This model made significant number of misclassifications for the class "M" which reduced the overall acccuracy.However the precision for this class is significantly high
Also this Model too has an AUC close to 1.
Before building both the models basic data exploration and preprocessing was carried out in python.
Viewed the dataset and understood about the features and observations, data types, checked for null values and dropped insignificant columns.
Checked correlation between different variables and found out there are variables that are highly correlated with other variables.
So dropped varaibles that are correlated with a corr coefficient greater than 0.85
Also the target variable is tranformed to numerical using label encoder and the x variables are standardized using standard scaler
