# MachineLearning
Final Project for Machine Learning class. Prediction of prevalence of stroke in a patient.

Stroke Prediction Project

**Overview**
This project is about predicting if an idividual did or did not have a stroke based on various factors. The two machine learning models that are used are Logistic Regression and Support Vector Machines for binary classification

**Data**
Source of Data: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset/data

Attributes
-id: unique identifer not needed in our models
-gender: Male, female, other
-age: age of patient
-hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
-heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
-ever_married: "No" or "Yes"
-work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
-Residence_type: "Rural" or "Urban"
-avg_glucose_level: average glucose level in blood
-bmi: body mass index
-smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"
-stroke: 1 if the patient had a stroke or 0 if not

How to Run

This code is a jupyter notebook file. Download FinalProjCode.ipynb and navigate through Anaconda Navigator to Jupyter Notebook. Once in Jupyter, Navigate to the FinalProjCode file and open it. If there is nothing for the outputs of the code, select Kernel on the top tool bar and select restart and run all.

Results

I found that hyperparameter tunning helped the model more than feature selection. I was able to increase precision and recall when performing hyperparamter tuning.
