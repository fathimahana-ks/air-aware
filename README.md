# AirAware – Predicting and Understanding Air Quality

## Overview
AirAware is a machine learning project designed to analyze air pollutant data and accurately predict the Air Quality Index (AQI). The system leverages multiple pollutant measurements (SO2, NO2, RSPM, SPM) and calculates individual pollutant indices to estimate overall air quality. The project includes comprehensive data preprocessing, exploratory data analysis (EDA), and implements both regression and classification models to forecast AQI levels and categorize air quality into meaningful ranges.

## Features
- Data preprocessing and null value imputation
- Pollutant index calculation for SO2, NO2, RSPM, and SPM
- AQI prediction using Linear Regression, Decision Tree, and Random Forest regressors
- Air quality classification with Logistic Regression, Decision Tree, Random Forest, and K-Nearest Neighbors classifiers
- Visualizations of pollutant distributions and AQI levels across different states
- Model evaluation with RMSE, accuracy, and Cohen’s Kappa score

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Dataset
The project uses an air quality dataset containing pollutant measurements from various states, with attributes such as SO2, NO2, RSPM, SPM concentrations, and corresponding AQI values.

## Getting Started

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/airaware.git
