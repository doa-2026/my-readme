####Stroke Prediction 

 ##Overview
 
This project explores a stroke detector  dataset using machine learning models to classify whether (stroke=1 ) or not (0).

Comparing  many classification  model to choose best model  using evaluation metrics, calssification report which shows (recall , precision , F1 sore ) and confusion metrix on both training and testing data.so, provides insights into how well this models makes predictions. 


##Objective

-Build a classification models to predict skroke pepole

-Evaluate the default and  tunned- model

-Choose the perfect model accourding to classification metrics

 Preprocessing
-Removed redundant columns:Unnamed: 0, Unnamed: 1
Handled missing values:
Median imputation for numerical features
Built preprocessing pipeline using:
ColumnTransformer
SimpleImputer
OneHotEncoder , OrdinalEncoding
scaling 

