
# Groundwater Quality classification and prediction using Ensemble Learning algorithms

Data was collected from CGWB website of Government of India. It was in PDF format hence was converted into CSV and Data cleaning was performed further to get desired data. Missing values were imputed using KNN imputer and iterative imputer, KNN imputer performed better, hence, was selected. Further GW was classified using 3 ways for classifying water EWQI, WAWQI and Expert opinion Based WQI. Several Ensemble learning Algorithms were used and compared. Three years og groundwater data from all over india was used and using two years of data, several ensemble models were trained (CatBoost was best performing algorithm) and same model was used for testing another years data.

## 🗂️ Project Overview

The primary objectives of this project were to:
- Import and process order data from CGWB website.
- Clean the data and perform Classification and Prediction on cleaned data.
