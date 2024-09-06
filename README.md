# Weather Forecasting Using Facebook Prophet

This project focuses on forecasting weather conditions using the Facebook Prophet model, a robust tool for time series forecasting. Prophet is designed to handle seasonal effects and holidays, making it well-suited for predicting weather patterns based on historical data.

## Overview

Weather forecasting is crucial for various applications, from daily planning to long-term climate analysis. This project utilizes the Facebook Prophet model to predict future weather conditions, providing accurate forecasts based on historical weather data.

## Key Components

- **Data Collection**: The dataset consists of historical weather data, including features such as temperature, humidity, precipitation, and other meteorological variables. Data is collected at regular time intervals (e.g., hourly, daily).

- **Data Preprocessing**: The dataset is cleaned and prepared for modeling. This includes handling missing values, ensuring data consistency, and transforming the data into a format compatible with Prophet.

- **Model Training**: The Facebook Prophet model is trained on the preprocessed weather data. Prophet is particularly effective for time series data with strong seasonal patterns and multiple seasonalities.

- **Evaluation**: Model performance is assessed using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). Forecast accuracy is evaluated against a hold-out test set.

- **Visualization**: Forecast results are visualized to compare predicted weather conditions against actual observations. Plots include historical data, forecasted values, and confidence intervals.

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/HadiaTahir/Weather-Forecasting-Using-Facebook-Prophet.git
   ```

2. **Install Dependencies**:
   Ensure you have the required libraries installed. Create a `requirements.txt` file with the necessary packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Code**:
   Execute the main script to train the Facebook Prophet model and generate weather forecasts:
   ```bash
   python main.py
   ```

## Contributions

Contributions are welcome! Feel free to submit issues or pull requests to enhance the project. Your feedback and suggestions are greatly appreciated.

