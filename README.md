📂 ####Stroke Prediction

 📌 Overview
 
This project explores a stroke detector  dataset using machine learning models to classify whether (stroke=1 ) or not (0).

Comparing  many classification  model to choose best model  using evaluation metrics, calssification report which shows (recall , precision , F1 sore ) and confusion metrix on both training and testing data.so, provides insights into how well this models makes predictions. 


🎯 Objective

-Build a classification models to predict skroke pepole

-Evaluate the default and  tunned- model

-Choose the perfect model accourding to classification metrics

  📝Data    
  the dataset contains  Features like age, gender, hypertension	,heart_disease	
ever_married, work_type	,Residence_type	 ,avg_glucose_level ,bmi, (Body Mass Index) smoking_status

 ⚙️ Preprocessing

-Removed redundant columns:Unnamed: 0, Unnamed: 1
Handled missing values:
Median imputation for numerical features
Built preprocessing pipeline using:
ColumnTransformer
SimpleImputer
OneHotEncoder , OrdinalEncoding
scaling 

🤖 Model

1- KNN(K-nearest Neighbours)
 using default and tunning the K hyperparameter 
	
2- Logistic Regression 
 using the default and tunning by c , penalty , solver , l1-ratio  hyperparameters 
	
3- Random Forest Classifier 
  using the default and tunning by max depth , min sample split , n-estimator ets  

Evaluated each model using:
Confusion Matrix
Classification Report


📈Results 

🔹Training performance 

Accuracy: 1.00
Precision / Recall / F1-score: 1.00

🔹 Testing Performance

using KNN model 
Accuracy: 0.85
macro-avg recall : .48 
KNN tunned model
Accuarcy .88
macro-avg recall .50

using random Forest classifier 
recall macro-avg increser from .5 (default model) to .54 (tunned-model)

using Logistic regresstion model 
macro-avg recall is .54 and accuracy is .87

🏁 Conclusion

The Logistic Regression model using l2 Regularization  achieved  the best performance than the other models used in this project. Depending on macro-avg recall metric which is more senstive in our dataset than other metrics 









