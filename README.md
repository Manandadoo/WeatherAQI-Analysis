# WeatherAQI-Analysis

## 📊 Overview

**WeatherAQI-Analysis** is a data analysis project that explores the relationship between weather parameters and the Air Quality Index (AQI) in Pune from 2017 to 2021. The project performs data cleaning, feature engineering, exploratory data analysis (EDA), and visualization to uncover insights from environmental data.

This project is implemented in Python using a Jupyter Notebook.

## 🧰 Features

- Data ingestion and preprocessing  
- Feature engineering and missing value handling  
- Exploratory Data Analysis (EDA) with visual insights  
- Correlation analysis between weather factors and AQI  
- Trend analysis across years and seasons  
- Time series and pollutant distribution visualizations  

## 📂 Project Structure

```
WeatherAQI-Analysis/
│
├── DE_Project_Final.ipynb            # Final Jupyter notebook for data processing and analysis
├── Pune_2017-21_weather(every_hour).csv  # Hourly weather data for Pune (2017–2021)
├── Pune_AQI_2017-21(hourly).csv      # Hourly AQI data for Pune (2017–2021)
└── README.md                         # Project documentation
```

## 📁 Dataset

The repository includes the two datasets used for this project:

- **Pune_2017-21_weather(every_hour).csv**: Hourly weather data including temperature, humidity, wind, etc.
- **Pune_AQI_2017-21(hourly).csv**: Hourly AQI and pollutant concentration levels.

These datasets are necessary to replicate the analysis and generate the visualizations.

## 🧪 Technologies Used

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## 📊 Visualizations

The notebook includes:
- Correlation heatmaps  
- Line plots of pollutant levels over time  
- Scatter plots for weather-AQI relationships  
- Monthly/yearly AQI trends  

## 🚀 Getting Started

To run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/WeatherAQI-Analysis.git
   cd WeatherAQI-Analysis
   ```

2. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook DE_Project_Final.ipynb
   ```

> 💡 Make sure the CSV files are present in the same directory as the notebook.
