# sepsis-prediction
Early Sepsis Detection Using Machine Learning Models and ICU Patient Data

## Project Overview
Sepsis is a life-threatening medical condition that requires early detection to improve patient outcomes.  
The goal of this project is to develop predictive models capable of detecting sepsis using ICU patient data.

The project compares classical machine learning methods with deep learning models to evaluate their performance in early sepsis detection.

## Dataset
The analysis is based on ICU patient data from the PhysioNet Sepsis Challenge dataset.  
The dataset contains time-series information such as:

- vital signs
- laboratory measurements
- demographic variables

## Project Structure

01_data_preprocessing.ipynb  
Data cleaning, handling missing values and preparing features.

02_exploratory_data_analysis.ipynb  
Exploratory data analysis and visualization of key variables.

03_machine_learning_models.ipynb  
Implementation of machine learning models such as Random Forest and XGBoost.

04_lstm_sepsis_early_detection.ipynb  
Deep learning model using LSTM architecture to capture temporal dependencies in patient data.

## Methods
The following models were implemented:

- Logistic Regression
- Random Forest
- XGBoost
- LSTM Neural Network

## Model Evaluation
Models were evaluated using metrics suitable for imbalanced classification problems.

In the context of medical diagnosis, detecting positive cases is particularly important. 
Therefore, special attention was given to metrics that measure the ability of the model 
to correctly identify patients with sepsis.

The following metrics were used:

- ROC-AUC
- Recall

Recall is especially important in this problem because it measures the proportion of 
true sepsis cases that were correctly detected by the model.

## Technologies Used

Python  
Pandas  
NumPy  
Scikit-learn  
XGBoost  
TensorFlow / Keras  
Matplotlib  
