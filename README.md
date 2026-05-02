# nyc-taxi-data-project
NYC Taxi Data Pipeline, Congestion Modeling, and Weather Analysis using Hadoop (HDFS) and PySpark

## Overview
This project analyzes NYC taxi trip data using big data tools such as Hadoop and PySpark. The goal is to understand traffic patterns and predict congestion levels.

## Objectives
- Analyze NYC taxi trip patterns
- Predict congestion levels using machine learning
- Evaluate the impact of weather on traffic conditions

## Tools & Technologies

### Core Technologies
- PySpark
- Hadoop (HDFS)
- Python (Pandas, Matplotlib, Seaborn)

### Development & Collaboration Tools
- Google Colab
- VS Code
- GitHub

## Data Sources
- NYC Taxi Data: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
- Weather Data: 

## Project Features
- Data cleaning and preprocessing using PySpark
- Feature engineering (trip duration, speed, time-based features)
- Random Forest model for congestion prediction
- Integration of weather data
- Data visualization

## Results & Insights
- The model achieved high accuracy when including features like speed and trip duration
- Removing these features reduced accuracy, suggesting potential data leakage
- Weather data did not significantly improve prediction performance
- Congestion is more strongly influenced by trip and time-based factors

## Limitations
- Some features (speed, trip duration) may introduce data leakage
- Weather data was aggregated daily, limiting granularity

## How to Run
1. Open the notebook in Google Colab
2. Mount Google Drive
3. Load datasets from provided paths
4. Run all cells

## Files
- NYC_Taxi_Data_Pipeline.ipynb → Main project notebook
- presentation.pdf → Final presentation
