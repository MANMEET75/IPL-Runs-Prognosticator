# IPL-Runs-Prognosticator
Applied Regression technique to predict runs of the players in IPL.  
# 1. Exploratory Data Analysis
Firstly Applied Exploratory Data Analysis to gather some of the information regarding the dataset like how many missing values we have, how many numeric and categorical features we have, what kind of distribution we have in the continuous variables, how many outliers we have etc.
# 2. Feature Engineering
Then Performed Feature Engineering to deal with all the problems that we have gathered like taking care of missing values, encoding the categorical variables, etc using Exploratory Data Analysis.
# 3. Feature Selection
Performed Feature selection using Lasso (L1 regularization) to select the best features which are predicting our dependent variable correctly.
# 4. Model Building
Then used algorithms like multiple linear regression, polynomial linear regression, support vector regressor, decision tree regressor, and random forest regressor to check which one is giving more accuracy to us concerning R-Squared values as the random forest giving more accuracy to us without any overfitting therefore we have used random forest regressor to built the model.
