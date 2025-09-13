# Health-Diabetes-analysis - Classification

## Project Overview
Prediction of whether an individual is Diabetic or not involved variables such as glucose level, number of pregnancies for females, BMI, Insulin level, Diabetes Pedigree function etc. A comparison of a Logistic regression model and  a Rnadom Forest Classifier was determined and the best model was deployed to be used for predictions.

Data sanity checks were performed e.g. missing values, duplicates, data types etc.

Data preprocessing e.g scaling, encoding were also performed in preparation for modeling.

Exploratory Data Analysis step gave an overview of the distribution of variables in the dataset.

Model building and prediction - Logistic Regression and Rnadom Forest Classifier.

Model Deployment - Pipelines were created using the most optimal model from the model prediction step. The model was saved using the joblib.dump function 

import joblib

joblib.dump(pipe, 'model_pipeline.pkl'

Gradio was used to finally deploy the model into an API key for use.
