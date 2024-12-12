---
# Copyright Notice
All rights reserved. This code is proprietary and may not be copied, distributed, or used without explicit permission from the owner.
---

# Wildfire_Smoke_ML_Prediction_2023
Author: Michael R. Martin

## Purpose:
The purpose of this program is to predict *Air Pollutant Levels* (**PM2.5 levels**) in the atmosphere, specifically targeting wildfire smoke emission impacts using various machine learning techniques. It achieves this by analyzing a range of environmental and meteorological features that influence wildfire smoke behavior and **PM2.5** emissions. The features include vapor pressure deficit, maximum temperature, precipitation, and other drought and moisture indices.

Key aspects of the program include:

1. **Data Handling and Visualization**: Historical big data from 1996 to 2020, which is loaded and visualized for trend observation and correlations in features affecting wildfire smoke levels.
2. **Data Processing**: Input variables undergo rescaling and reshaping through statistical analysis to optimize for machine learning models in dictionary.
3. **Machine Learning Model Training**: The program employs multiple Machine Learning techniques through Gradient Boosting, AdaBoost, Random Forest, Decision Tree, K-Nearest Neighbors, Ridge, and SVR, to predict wildfire smoke levels.
4. **Model Performance Evaluation**: Each model is trained on the training dataset and tested on test data, with performance metrics generated to assess predictive accuracy and model suitability.

By iterating with additional ML and deep learning techniques in future versions, this program aims to refine the accuracy and reliability of wildfire smoke predictions, helping in proactive air quality management during wildfire events.

## Program Developed in 2023
- This program encompasses starting code created for wildfire smoke prediction using Machine Learning methods.
- Further ML practices such as Deep Learning are added in subsequent versions of this code.

**Input variables:**
- vapor pressure deficit (VPD)
- Temperature (max)
- Precipitation
- Potential evapotranspiration (PET)
- evapotranspiration (ET)
- Palmer Drought Severity Index (PDSI)
- Evaporative Demand Drought Index (EDDI)
- soil moisture
- water equivalent drought index (SWEI)
- Outcome or target variable:
- *OUTPUT*: Wildfire Smoke Emissions (**PM2.5**)

## Code Info:
After input variables are initialized, input variables and emission big data are read (from 1996 to 2020) before being visualized.
After rescaling the and reshaping through statistical analysis, several ML models are trained with the training datasets. Models included are:
'Gradient Boost': GradientBoostingRegressor(random_state=0),
    'Ada Boost Regressor'
    'Random Forest Regressor'
    'Decision Tree Regressor'
    'KNeighbors Regressor': KNeighborsRegressor(),
    'Ridge'
    'SVR'
Linear regression statistics are then calculated and displayed to the user after training and prediction with train and test data respectively.
