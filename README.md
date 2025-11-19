# Renewable Power Generation and weather Conditions

## Introduction

This notebook documents how we train a LSTM model from a given dataset to forecast renewable energy generation. We also train others regression models for the environmental features. It includes EDA, model training and forecasting.

Regression models include: **Random Forest**, **Gradient Boosting Regressor**, **XGBoost Regressor** and **Linear Regression**.

## About Dataset

**Description:**

Imagine having access to a treasure trove of information that reveals how weather directly impacts renewable energy generation. This dataset, meticulously compiled with hourly measurements, is your key to unlocking those secrets.

**Delving into the Details:**

- Solar Power's Prime Driver: The dataset features "Global Horizontal Irradiance (GHI)" readings, which tell you the exact amount of solar radiation hitting a flat surface every hour. This is crucial, as sunlight is the lifeblood of solar energy production.
- Beyond Sunshine: But weather has more to offer than just sunshine. The dataset also includes data on temperature, humidity, and precipitation – all playing a role in energy production and consumption.
- Time Makes a Difference: By incorporating "dayLength" and "sunlightTime" measurements, you can see how the amount of daylight and sunshine availability directly affects energy generation patterns.

**Use Cases**
- Predict Renewable Energy Output: By analyzing the relationship between weather and past energy generation, you can develop models to predict future output, aiding in grid management and energy planning.

- Understand Energy Demand: Weather can also influence energy consumption. Studying how temperature and other factors affect demand can help optimize energy infrastructure and distribution.

**Provider:** Afroz

Reference: https://www.kaggle.com/datasets/pythonafroz/renewable-power-generation-and-weather-conditions/data

## About this notebook

For this notebook, we refer the source code shared by Afroz on Kaggle as a reference.
(https://www.kaggle.com/code/pythonafroz/renewable-power-gen-prediction-with-time-series/notebook)
