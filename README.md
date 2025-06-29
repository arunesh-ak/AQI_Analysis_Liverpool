# Air Quality and Weather Analysis in Liverpool (2022-2023)

This project analyzes how air quality and weather conditions impact the Air Quality Index (AQI) in Liverpool between April 2022 and December 2023. The study focuses on both atmospheric pollutants and weather variables to understand patterns and seasonal trends influencing AQI levels.

## Project Overview

The primary goal of this project is to identify how pollutants like **PM2.5, PM10, CO, NO2, SO2, O3** and weather conditions like **humidity, wind speed, and temperature** affect AQI levels in Liverpool. By leveraging the **Random Forest** algorithm, the project aims to uncover key factors that influence air quality, which can help in predicting future AQI levels. The findings can support local air quality management and public health planning.

### Key Objectives
1. **Analyze pollutant and weather data** to determine their influence on AQI levels.
2. **Identify seasonal trends** and patterns that affect air quality.
3. **Forecast future AQI levels** using machine learning models, specifically the Random Forest algorithm.
4. Provide insights for **improving air quality management** and **public health interventions** in Liverpool.

## Datasets

The project uses datasets that include the following variables:

- **Pollutants**: PM2.5, PM10, CO, NO2, SO2, O3
- **Weather Variables**: Temperature, Humidity, Wind Speed

The data covers the time period from **April 2022 to December 2023**, collected from government sources and weather stations in Liverpool.

## Methodology

### 1. **Data Preprocessing**
   - **Handling Missing Data**: Imputation techniques are applied to handle missing or incomplete records.
   - **Feature Engineering**: Additional features are derived to enhance the prediction model, including interactions between pollutants and weather conditions.

### 2. **Exploratory Data Analysis (EDA)**
   - Visualizations of pollutant levels and weather data trends over the study period.
   - Correlation analysis between pollutants and weather variables.

### 3. **Modeling**
   - **Random Forest Algorithm**: Used to identify key factors influencing AQI and to forecast future AQI levels.
   - Feature importance scores are derived to highlight the most significant variables affecting air quality.

## Key Questions

- **How have AQI levels changed over the past year in Liverpool?**
  This question explores the relationship between AQI and weather parameters such as temperature, humidity, and wind speed.
  
- **How do weather conditions influence AQI and overall air quality?**
  We aim to identify how different weather factors contribute to AQI fluctuations, uncovering potential patterns.

- **Can we predict future AQI levels based on historical trends?**
  By incorporating weather data, we seek to enhance the performance of AQI prediction models. This question assesses whether considering environmental factors leads to more accurate forecasting.

## Results

The analysis identifies patterns and seasonal variations that influence AQI in Liverpool. Key factors like **humidity**, **temperature**, and **PM2.5 levels** are found to have a significant impact on air quality. The Random Forest model demonstrates good predictive capabilities, highlighting the importance of both pollutants and weather variables in forecasting future AQI levels.

## Conclusion

This project provides valuable insights into the relationship between weather conditions and air quality in Liverpool. The results can support better air quality management practices and help in developing policies to mitigate the impact of poor air quality on public health.

## Future Work

- Explore other machine learning models for improved accuracy in predicting AQI.
- Investigate additional environmental factors, such as traffic patterns, to enhance predictions.
- Implement the model as a real-time monitoring and forecasting tool for air quality management.
