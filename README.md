
# Weather Data Analysis and Prediction Model (2019-2023)

## Overview

This project analyzes the weather data for February across five years (2019-2023) using machine learning techniques and various visualization methods. The dataset includes temperature, precipitation, and wind speed, with the goal of identifying trends and making predictions.

## Table of Contents

- [Introduction](#introduction)
- [Data Cleaning](#data-cleaning)
- [Data Exploration](#data-exploration)
- [Model Creation](#model-creation)
- [Results](#results)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)

## Introduction

This project explores the climate patterns for February across multiple years. The dataset covers:

- **Temperature (°C)**
- **Precipitation (mm)**
- **Wind Speed (km/h)**

The combined data for five years is used to study climate trends and build predictive models for temperature.

## Data Cleaning

To ensure consistency, the data underwent a series of cleaning steps:

1. Renaming columns for uniformity.
2. Filling missing values using forward fill.
3. Formatting the Date column to a consistent format across all datasets.

## Data Exploration

After cleaning the data, we calculated basic statistics to understand the average values for temperature, precipitation, and wind speed during February over the years. These summary statistics helped identify the overall climate trend.

- **Average Temperature**: Derived across all years.
- **Average Precipitation**: The mean precipitation values.
- **Average Wind Speed**: The average wind speed measured.

## Model Creation

A linear regression model was built to predict the temperature based on the precipitation and wind speed. Both the **statsmodels** and **sklearn** libraries were used for modeling:

- **Statsmodels OLS Regression**: Used to calculate the relationship between features.
- **Sklearn Linear Regression**: Applied to evaluate the predictive performance of the model.

## Results

- **Mean Squared Error**: A measure of how well the model performed in predicting temperature.
- **Model Coefficients**: The impact of precipitation and wind speed on the temperature.

## Visualizations

Several visualizations were created to compare the weather trends across the years:

1. **Line Plot**: A line chart comparing temperature, precipitation, and wind speed for February from 2019 to 2023.
2. **Heatmap**: A heatmap showing the average daily temperature for each year in February, highlighting any significant variations.
3. **Candlestick Chart**: A candlestick chart visualizing the daily temperature fluctuations and precipitation impact over the five-year period.
4. **Bar Chart**: A bar chart comparing the average temperature for February in each of the five years.

## Conclusion

This project illustrates the use of weather data for February from 2019 to 2023 to build a predictive model for temperature and visualize trends in precipitation and wind speed. The findings help understand how weather patterns evolve over time and allow for future predictions based on historical data.



[Run the Notebook on Google Colab](https://colab.research.google.com/drive/1dc2lXxl0-_5F22z1eQAGZz-Q0tX0nGO1?usp=drive_link)

