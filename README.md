## Author

**Alexandre Vidal De Palol**  
Master in Data Science (UOC)  
[GitHub](https://github.com/alexvidi) | [LinkedIn](www.linkedin.com/in/àlex-vidal-de-palol-a18538155)  

This project was developed as part of the Master's Final Project in Data Science, addressing the challenges of prediction in the cryptocurrency market through Big Data Streaming and Machine Learning.

## Advisor

**Rafael Luque Ocaña**  
Professor and researcher specialized in Data Science.  

# Challenges in Cryptocurrency Price Prediction: Implementation of a System with Big Data Streaming and Machine Learning

This repository contains the code, data, and documentation of the Master's Final Project titled: **"Challenges in Cryptocurrency Price Prediction: Implementation of a System with Big Data Streaming and Machine Learning"**. This project aims to design a predictive system to analyze the behavior of the cryptocurrency market, integrating advanced real-time data processing technologies and machine learning algorithms.

## Project Structure

The repository is organized into the following folders:

- **`notebooks/`**: Contains the Jupyter notebooks organized by model and cryptocurrency.
  - `ARIMA_BNB_CODE.ipynb`: Predictive analysis of Binance Coin using ARIMA.
  - `ARIMA_BTC_CODE.ipynb`: Predictive analysis of Bitcoin using ARIMA.
  - `ARIMA_ETH_CODE.ipynb`: Predictive analysis of Ethereum using ARIMA.
  - `PROPHET_CODE.ipynb`: General predictive analysis using Prophet.
  - `TFM_CODE_PIPELINE.ipynb`: Complete implementation of the data pipeline.
- **`data/`**: Contains the data files used in the project.
  - `crypto_db.crypto_data2.json`: Historical data collected from the CoinGecko API.
- **`LICENSE`**: Project license.
- **`requirements.txt`**: List of dependencies required to run the project.

## Technologies and Tools Used

The project employs a comprehensive approach using several key tools and technologies:
- **Data Acquisition**: CoinGecko API for real-time market data.
- **Real-time Processing**:
  - Apache Kafka for data streaming.
  - Apache Spark Streaming for distributed processing.
- **Storage**: MongoDB for storing historical data.
- **Predictive Modeling**:
  - **ARIMA**: A classical model for capturing linear patterns in time series.
  - **Prophet**: A scalable and flexible model for complex trends.
- **Results Visualization**: Matplotlib for detailed charts.

## Methodology

The CRISP-DM (Cross Industry Standard Process for Data Mining) methodology was used to organize the project's phases:
1. **Data Acquisition**: Automated collection from the CoinGecko API.
2. **Data Preprocessing**: Transformation and cleaning using Pandas and Apache Spark.
3. **Exploratory Analysis**: Identification of initial patterns and trends.
4. **Predictive Modeling**: Implementation and comparison of the ARIMA and Prophet models.
5. **Visualization and Evaluation**: Analysis of results and performance metrics (MAE, RMSE, MAPE).

## Installation and Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/alexvidi/TFM_Crypto_Prediction.git
   cd TFM_Crypto_Prediction



