# Flight-Price-Prediction

Here we are predicting the Flight price based on the Airline.

We have used Several techniques like-
EDA -- Exploratory data analysis (EDA) is used to analyze and investigate data sets and summarize their main characteristics, often employing data visualization methods.

#Handling categorical Data
One can find many ways to handle categorical data . some of them categorical are-

Nominal Data- Data which is not in any order - OneHotEncoder is used.
Ordinal Data- Data which is in order - LabelEncoder is used .

#Feature Selection
Finding out the best feature which will contribute and have good relation with target variable.

Following are the best feature Selection methods-

Heatmap
feature_importance_
SelectKBest


#Fitting Model using RandomForest
1.Split Dataset into train and test set in order to prediction w.r.t X_test

2.If needed we can do Scaling of data

Remember Scaling is not done in RandomForest

3.Import Model

4.Fit the Model

5.Predict w.r.t X_test

6.In Regression check RSME( Root Mean Squared Error ) score .It measures the average difference between values predicted by a model and the actual values.

7.Plot Graph



#Hyperparameter Tuning
Choose following method for Hyperparameter Tuning

RandomizedSearchCV --> Fast
GridSearchCv
Assign hyperparamters in form of dictionary

Fit the model

Check best parameters and best score
