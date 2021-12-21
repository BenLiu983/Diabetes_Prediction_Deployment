# Diabetes Prediction and Deployment

# Product Link: https://diabetes-prediction-v1.azurewebsites.net/

# 1. Objective

Forecast the probability of diabetes for a given group of patients using 6 Machine Learning classifications models, develop and deploy the web app with HTML, CSS, Flask, and Azure.

# 2. Data

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. 
The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic 
measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. 
In particular, all patients here are females at least 21 years old of Pima Indian heritage.

Link: https://www.kaggle.com/uciml/pima-indians-diabetes-database

# 3. Variable intepretation:

![image](https://user-images.githubusercontent.com/64850893/146964353-c0ca0168-51e2-486a-ab76-18e5ff4f6eea.png)

## Independent Variables:

1. Pregnancies：Number of times pregnant.
  
2. Glucose：Plasma glucose concentration a 2 hours in an oral glucose tolerance test.

3. BloodPressure: Diastolic blood pressure (mm Hg).

4. SkinThickness: Triceps skin fold thickness (mm).

5. Insulin: 2-Hour serum insulin (mu U/ml).

6. BMI: Body mass index (weight in kg/(height in m)^2)

7. DiabetesPedigreeFunction: Diabetes pedigree function

8. Age: years.

## Dependent Variables:

Outcome: 1 (diabetes) or 0. 

# 4. Methodology

We will use 6 ML classifications algorithms:

1. Naive Bayes

2. Logistic Regression

3. KNN

4. Support Vector Classifier

5. Decision Tree

6. Random Forest 


# 5. EDA:

## 5.1 Dependent Variables:

![image](https://user-images.githubusercontent.com/64850893/146965415-3a7a8ca6-f3b7-48f3-8ebf-75b29ab6d583.png)

Imbalanced dataset, will upsample later.


