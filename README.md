# Scripting-with-Python
# NYC Air Quality Analysis and Forecasting

## Project Overview
This project analyzes air quality patterns and forecasts future pollution levels in New York City using datasets from [data.gov](https://data.gov) and [nyc.gov](https://nyc.gov). It aims to identify major pollutants, understand their seasonal and regional variations, and assess health impacts. The study also leverages machine learning models to predict air quality trends, providing valuable insights for policymakers, environmental analysts, and public health officials.

## Objectives
- Analyze historical air quality data to identify key patterns and trends.
- Develop predictive models using machine learning techniques such as Gradient Boosting Regressor.
- Correlate pollutant trends with health statistics to assess their impact.
- Create visualizations that effectively communicate findings to stakeholders.

## Methodology
1. **Data Collection & Preprocessing**
   - Sourced pollutant and health data (2009-2022) from NYC government repositories.
   - Handled missing values and outliers.
   - Engineered features like seasonal and temporal indicators.

2. **Exploratory Data Analysis (EDA)**
   - Visualized pollutant distributions and seasonal trends.
   - Conducted correlation analysis to examine relationships between pollutants and weather.

3. **Predictive Modeling**
   - Implemented **Random Forest Regressor** and **Gradient Boosting Regressor (XGBoost)** to forecast pollutant levels.
   - Tuned hyperparameters for optimal performance.
   - Evaluated models using **R-squared** and **Mean Absolute Error (MAE)**.

4. **Health Impact Analysis**
   - Examined correlations between pollutant levels and hospital admissions for respiratory and cardiovascular diseases.
   - Identified key health risks associated with high pollution periods.

## Key Findings
- **PM2.5 and NO2** are the most significant pollutants affecting NYC's air quality.
- Seasonal trends indicate **higher pollutant levels in winter**.
- **Gradient Boosting Regressor achieved an R-squared score of 0.94**, demonstrating strong predictive accuracy.
- **Black Carbon absorbance** was the most critical factor in predicting PM2.5 levels.
- **Health data analysis showed a strong correlation** between high PM2.5 levels and increased rates of cardiovascular and respiratory hospitalizations.

## Conclusion
This project provides valuable insights into NYC’s air quality trends and their health implications. The developed forecasting models offer a reliable tool for proactive air quality management, informing public health strategies and urban planning initiatives. Future work can focus on integrating real-time sensor data and expanding predictive capabilities to other pollutants.

