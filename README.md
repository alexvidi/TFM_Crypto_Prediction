# Desafíos en la Predicción de Precios de Criptomonedas: Implementación de un Sistema con Big Data Streaming y Machine Learning

Este repositorio contiene el código, datos y documentación del Trabajo Final de Máster titulado: **"Desafíos en la Predicción de Precios de Criptomonedas: Implementación de un Sistema con Big Data Streaming y Machine Learning"**. Este proyecto tiene como objetivo principal diseñar un sistema predictivo para analizar el comportamiento del mercado de criptomonedas, integrando tecnologías avanzadas de procesamiento de datos en tiempo real y algoritmos de aprendizaje automático.

## Estructura del proyecto

El repositorio está organizado en las siguientes carpetas:

- **`notebooks/`**: Contiene los notebooks Jupyter organizados por modelo y criptomoneda.
  - `ARIMA_BNB_CODE.ipynb`: Análisis predictivo de Binance Coin con ARIMA.
  - `ARIMA_BTC_CODE.ipynb`: Análisis predictivo de Bitcoin con ARIMA.
  - `ARIMA_ETH_CODE.ipynb`: Análisis predictivo de Ethereum con ARIMA.
  - `PROPHET_CODE.ipynb`: Análisis predictivo general utilizando Prophet.
  - `TFM_CODE_PIPELINE.ipynb`: Implementación completa del pipeline de datos.
- **`data/`**: Contiene los archivos de datos utilizados en el proyecto.
  - `crypto_db.crypto_data2.json`: Datos históricos recolectados de la API de CoinGecko.
- **`LICENSE`**: Licencia del proyecto.
- **`requirements.txt`**: Lista de dependencias necesarias para ejecutar el proyecto.

## Tecnologías y herramientas utilizadas

El proyecto emplea un enfoque integral utilizando diversas herramientas y tecnologías clave:
- **Obtención de datos**: API de CoinGecko para datos de mercado en tiempo real.
- **Procesamiento en tiempo real**:
  - Apache Kafka para la transmisión de datos.
  - Apache Spark Streaming para el procesamiento distribuido.
- **Almacenamiento**: MongoDB para almacenar datos históricos.
- **Modelado predictivo**:
  - **ARIMA**: Modelo clásico para capturar patrones lineales en series temporales.
  - **Prophet**: Modelo escalable y flexible para tendencias complejas.
- **Visualización de resultados**: Matplotlib para gráficos detallados.

## Metodología

Se empleó la metodología CRISP-DM (Cross Industry Standard Process for Data Mining) para organizar las fases del proyecto:
1. **Obtención de datos**: Recolección automatizada desde la API de CoinGecko.
2. **Preprocesamiento de datos**: Transformación y limpieza con Pandas y Apache Spark.
3. **Análisis exploratorio**: Identificación de patrones y tendencias iniciales.
4. **Modelado predictivo**: Implementación y comparación de los modelos ARIMA y Prophet.
5. **Visualización y evaluación**: Análisis de resultados y métricas de desempeño (MAE, RMSE, MAPE).

## Instalación y uso

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/alexvidi/TFM_Crypto_Prediction.git
   cd TFM_Crypto_Prediction

