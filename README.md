# Energy-Anomaly-Detection

## Project Description

This project detects anomalies in energy consumption time series using both statistical and machine learning approaches.

## Dataset

Hourly Energy Consumption Dataset (PJME)

https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption

## Methods

- Data Preprocessing
- Daily Resampling
- Rolling Mean Smoothing
- StandardScaler Normalization
- Z-Score
- Rolling Standard Deviation
- Isolation Forest
- Autoencoder

## Results

| Method | Detected Anomalies |
|---------|-------------------:|
| Z-Score | 20 |
| Isolation Forest | 119 |
| Autoencoder | 161 |

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
