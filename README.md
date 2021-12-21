# Diabetes Prediction and Deployment

## Product Link: https://diabetes-prediction-v1.azurewebsites.net/

![image](https://user-images.githubusercontent.com/64850893/146972754-a16a2eae-ebd2-40b6-a896-3eca85158bcd.png)

# 1. Objective

Forecast the probability of diabetes for a given group of patients using 6 Machine Learning classifications models, develop and deploy the web app with HTML, CSS, Flask, and Azure.

# 2. Data

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. 
The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic 
measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. 
In particular, all patients here are females at least 21 years old of Pima Indian heritage.

Link: https://www.kaggle.com/uciml/pima-indians-diabetes-database

# 3. Variable interpretation:

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

1. Naive Bayes.

2. Logistic Regression.

3. KNN.

4. Support Vector Classifier.

5. Decision Tree.

6. Random Forest.

# 5. EDA:

## 5.1 Histogram:

![image](https://user-images.githubusercontent.com/64850893/146966939-479bc57a-ee1b-4a84-bbc9-6475fa59a8cc.png)

## 5.2 Boxplot:

![image](https://user-images.githubusercontent.com/64850893/146967610-934a625c-df02-4f77-bcd9-a94f8130eca1.png)

## 5.3 Correlation:

![image](https://user-images.githubusercontent.com/64850893/146967367-449fbaff-8f1a-4429-a1a0-62b9797a2609.png)

## 5.4 Dependent Variables (Outcome)

![image](https://user-images.githubusercontent.com/64850893/146965415-3a7a8ca6-f3b7-48f3-8ebf-75b29ab6d583.png)

* It is an imbalanced dataset and we will upsample later.

## 5.5 Outcome vs Glucose

![image](https://user-images.githubusercontent.com/64850893/146967740-21141c43-aa62-4422-a0a1-b1c84e0e3594.png)

* It seems like that diabetic people tend to have a greater glucose level.

## 5.6 Outcome vs Blood Pressure

![image](https://user-images.githubusercontent.com/64850893/146968054-26a66179-98ac-405e-9fda-1a041a95db57.png)

* Patients with diabetes tend to have higher blood pressure.

# 6. Modeling

6.1 Upsampling.

6.2 Train-Test-Split.

6.3 Generate data pipelines for production.

6.4 Apply the models and create the confusion matrix.

![image](https://user-images.githubusercontent.com/64850893/146971968-114c283f-a14d-4d67-b823-4fd6159776f4.png)

# 7. Front End development with HTML and CSS

# 8. Back End development with Python and Flask

# 9. Deployment on Azure




