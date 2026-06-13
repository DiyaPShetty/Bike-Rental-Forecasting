# Bike Rental Forecasting

## Project Overview

Bike-sharing systems play an important role in sustainable urban transportation. However, sudden fluctuations in rental demand can lead to station imbalance, where stations either run out of bikes or have insufficient docking spaces.

This project focuses on forecasting hourly bike rental demand using historical bike-sharing data. By analyzing rental patterns and seasonal trends, the system predicts future demand and helps improve resource allocation and operational planning.

---

## Problem Statement

Managing bike availability is a major challenge in bike-sharing systems. Demand varies significantly throughout the day, especially during peak commuting hours.

The objective of this project is to analyze historical rental data, identify recurring patterns, and develop a forecasting model capable of predicting future bike rental demand.

---

## Dataset

* Dataset: UCI Bike Sharing Dataset
* Data Type: Hourly bike rental records
* Features Used: Date, Time, Rental Count and related temporal information

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

---

## Methodology

1. Data Collection and Extraction
2. Data Cleaning and Preprocessing
3. Missing Value Handling using Linear Interpolation
4. Exploratory Data Analysis (EDA)
5. Time Series Forecasting
6. Model Evaluation using Mean Absolute Error (MAE)

---

## Models Implemented

The following forecasting approaches were developed and compared:

* Simple Average Model
* Moving Average Model
* Linear Trend Model
* Hourly Seasonal Index Model

The Hourly Seasonal Index model achieved the best performance and was selected as the final forecasting approach.

---

## Results

* Successfully forecasted hourly bike rental demand.
* Identified daily rental patterns and peak usage hours.
* Achieved a Mean Absolute Error (MAE) of approximately 40.52 using the Seasonal Index model.
* Generated future demand projections based on historical trends.

---

## Repository Structure

```text
Bike-Rental-Forecasting/
│
├── BikeRentalForecastingFinal.ipynb
├── README.md
├── requirements.txt
├── data/
└── docs/
```

---

## Team Members

* Greeshma
* Diya P Shetty
* Felicia Fernandes

---

## Future Improvements

* Weekend and holiday-specific forecasting
* Weather-based demand prediction
* Station-level demand forecasting
* Integration with real-time data sources

---

## License

This project was developed for academic and learning purposes.
