## Predictive Modelling of Sign Language Acquisition

A machine learning project exploring whether **cognitive, interactional and demographic features** can predict American Sign Language (ASL) learning progress in children using the ASL-PLAY dataset.

### Key Features

* Performed data preprocessing including **imputation, scaling and outlier handling**
* Built and compared **Linear Regression, Random Forest and LSTM** models
* Evaluated models using **MAE, MSE, RMSE and R²**
* Optimised model hyperparameters to improve predictive performance
* Random Forest achieved the strongest overall performance with **R² ≈ 0.53**
* Used feature importance to identify **child age, adult object touch and adult gaze** as influential predictors

**Tech:** Python · Pandas · NumPy · Scikit-learn · TensorFlow/Keras · Machine Learning · LSTM

Dataset:

Source: ASL-Play dataset from Databrary (https://osf.io/3w8ka/files/osfstorage)

Collected by: NYU Infant Action Lab (Karen Adolph et al.)

Structure:

24 families

Two sessions per family

Each session stored as a separate CSV file

Additional demographics file with child and caregiver information
