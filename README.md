# Traffic Demand Prediction using CatBoost

## Overview

This project predicts urban traffic demand using machine learning techniques on spatio-temporal, environmental, and road-network data.

The objective is to forecast traffic demand at different locations and timestamps to help improve transportation planning and congestion management.

## Dataset

* Training Samples: 77,299
* Test Samples: 41,778

### Features

* Geohash
* Day
* Timestamp
* RoadType
* NumberofLanes
* LargeVehicles
* Landmarks
* Temperature
* Weather

### Target Variable

* Demand

## Exploratory Data Analysis

Performed:

* Missing value analysis
* Demand distribution analysis
* Weather-wise demand analysis
* RoadType analysis
* Lane count analysis
* Geospatial feature analysis

## Feature Engineering

Engineered features include:

* Hour
* Minute
* Rush Hour Indicator
* Evening Peak Indicator
* Geohash Prefix Encoding

## Model

CatBoost Regressor

### Hyperparameters

* Iterations: 2000
* Depth: 8
* Learning Rate: 0.03

## Results

### Model Performance

| Metric | Score |
|----------|----------|
| Validation R² Score | 0.9436 |
| Hackerearth Public Leaderboard Score | 90.8044 |

### Final Model

- CatBoost Regressor
- Iterations: 2000
- Depth: 8
- Learning Rate: 0.03

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-Learn
* CatBoost
* Matplotlib

## Key Learnings

* Feature engineering for time-series and traffic datasets
* Handling categorical variables using CatBoost
* Traffic demand forecasting
* Model evaluation using R² score
* Feature importance interpretation
