# Data-Mining-R-BMW-Pricing-Model-

#Background Information 
Nowadays, many people will choose to buy and sell their used cars. Everyone wants their car to be sold at an ideal price; however, how to determine the ideal price is no easy solution. Therefore, building a pricing model based on historical dataset is the best way to solve this problem. Pricing model has been widely used in many fields. For example, many used car websites such as CarMax use pricing model to determine the price of the used car. Also, the pricing model can be applied in other industries such as insurance  company  to  determine  the  price  of  insurance.  In  this  project,  we  will implement a pricing model to forecast the ideal price of the car in used car market. 

#Data Collection   
The dataset is derived from Kaggle (https://www.kaggle.com/adityadesai13/used-car-dataset-ford-and-mercedes?select=audi.csv ). The whole dataset contains thirteen csv files,  which  provides  details  for  used  cars  in  different  brands.  The  whole  dataset contains almost 100,000 observations and 9 features. For the features of the dataset, there are 3 categorical features and 6 numerical features.  

#The Problem
The pricing model has been widely used in many fields such as used car retailer and insurance  company.  For  the  problem  of  our  project,  we  will  implement  car  value regression model to predict the ideal price of a used car. 

#Possible Solution
First of all, we will do some exploratory data analysis to check the balance of the data and find possible correlation by visualization methods. After EDA process, we plan to do some feature engineering to the whole dataset. For example, we will deal with the missing value in the dataset by replacing these missing values by 0, mean or median. For the categorical data in dataset, we will choose encoding methods such as One-Hot Encoding to encode these categorical data. Also, we will reduce the dimension of the data  by  PCA  and  normalize  data.  Then,  we  will  select  appropriate  model  for  this regression problem. For the selection of the model, we will not only do some classical model such as Linear Regression (L1, L2 norms), SVM, Tree model (Decision Tree, Random  Forest),  but  also  some  advance  model  such  as  XGBoost,  CatBoost  and LightGBM. Also, we will try to use TensorFlow for R to implement Neural Networks model for this project. After training model, we will optimize model by using Grid-Search, Cross-Validation and choose best model by plotting ROC curve. 

#Contributor:
Jiachen Liu (Northeastern University, MS Data Science '21)
Alex Nguyen (Northeastern University, MS Data Analytics Engineering '22)
