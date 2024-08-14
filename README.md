# Arctic Ice Extent Forecasting

This repository contains the code and resources used in the study **"Analyzing the Dynamics of Arctic Ice Extent: A Comparative Study of Regression and Time Series Forecasting Methods"** by Ahmed Aman Ibrahim and Bala Krishnan Sekar. The study focuses on predicting Arctic ice extent using various regression models and time series forecasting techniques, emphasizing the need for accurate forecasting in the context of global climate change.

## Introduction

Arctic ice extent is a critical indicator of climate change, impacting global climate systems and sea levels. This project presents a comparative analysis of different forecasting methods, including regression models and time series techniques like ARIMA and SARIMA, to predict Arctic ice extent. The dataset spans from 1978 to 2023, with a focus on understanding the seasonal patterns and long-term trends.

## Results

- **Regression Models:**
  - Linear Regression performed the best among regression models with a Mean Squared Error (MSE) of 0.0628.
  - However, these models struggled with capturing seasonal variations in the data.

- **Time Series Models:**
  - SARIMA with exogenous variables (SARIMAx) performed best with an R² score of 98.92%, effectively modeling both seasonal patterns and long-term trends.
  - The first ice-free year prediction using SARIMA is 2107.


![ACF]("diagrams\acf.png")