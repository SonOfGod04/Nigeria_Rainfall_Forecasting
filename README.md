# Nigeria_Rainfall_Forecasting
## Rainfall Forecasting: Comparative Analysis of Machine Learning Algorithms for Time-Series Rainfall Forecasting in Nigeria.

This repository serves as a comprehensive exploration and analysis of various machine learning algorithms for time-series rainfall forecasting specifically tailored to Nigeria's climatic conditions.

### Objective:
The primary objective of this research is to design, implement, and compare the performance of Convolutional Neural Network (CNN), Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU) models for rainfall prediction.

### Specific Goals:
Design robust models leveraging CNN, LSTM, and GRU architectures to predict rainfall patterns in Nigeria.
Conduct a thorough analysis of the designed models using a range of performance evaluation metrics to determine their effectiveness and reliability.

### About the Dataset:
The dataset used for this research encompasses the following key parameters:

- Dew (°C): Dew point temperature in degrees Celsius.

- T (°C): Temperature measured in degrees Celsius.

- P(mb): Atmospheric pressure in millibars.

- v(m/s): Wind speed in meters per second.

- Prec(mm/day): Precipitation level in millimeters per day.

- RH(%): Relative humidity measured in percentage.
  
This repository aims to provide valuable insights and methodologies for rainfall forecasting in Nigeria, contributing to the advancement of predictive modeling in meteorology and climate science.

Feel free to explore the code, datasets, and analysis provided in this repository to gain deeper insights into the application of machine learning in weather forecasting, specifically tailored to Nigerian climatic conditions.

#### Note: Ensure proper citation and attribution if you utilize any part of this research or codebase.

#### Contributor: Ajah, Oguche

![rainfall1](https://github.com/SonOfGod04/Nigeria_Rainfall_Forecasting/blob/main/Screenshot%20(199).png)

## Importing dataset
The first step involved importing the dataset containing detailed meteorological data from various regions in Nigeria. Each dataset was accompanied by comprehensive data summaries to provide insights into the variables and their distributions.
## Data Cleaning
A meticulous data cleaning process was implemented to ensure the dataset's integrity. This included checking for missing data, handling duplicates, and addressing outliers to prepare the dataset for analysis and modeling.
![rainfall1](https://github.com/SonOfGod04/Nigeria_Rainfall_Forecasting/blob/main/Screenshot%20(198).png)
![rainfall1](https://github.com/SonOfGod04/Nigeria_Rainfall_Forecasting/blob/main/Screenshot%20(200).png)
![rainfall1](https://github.com/SonOfGod04/Nigeria_Rainfall_Forecasting/blob/main/Screenshot%20(201).png)
## Exploratory Data Analysis
An extensive exploratory data analysis (EDA) was conducted to gain a deeper understanding of the dataset. Detailed analyses were performed for each state, uncovering important insights and patterns in the meteorological variables.
![rainfall1](https://github.com/SonOfGod04/Nigeria_Rainfall_Forecasting/blob/main/Screenshot%20(202).png)
## Feature Engineering
Feature engineering played a crucial role in enhancing the predictive power of the model. Various techniques were employed to extract relevant features and create new variables that could better capture the dynamics of rainfall patterns in Nigeria. Data normalization was performed to scale the features and ensure uniformity in their ranges, thereby improving the stability and convergence of the models.
![rainfall1](https://github.com/SonOfGod04/Nigeria_Rainfall_Forecasting/blob/main/Screenshot%20(203).png)
## Data splitting/Model Building
The dataset was split into training and testing sets to facilitate model development and evaluation. Several machine learning algorithms, including Convolutional Neural Network (CNN), Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU), were implemented to build predictive models for rainfall forecasting.
![rainfall1](https://github.com/SonOfGod04/Nigeria_Rainfall_Forecasting/blob/main/Screenshot%20(204).png)
## Model Evaluation
The performance of each model was rigorously evaluated using a range of evaluation metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE). This enabled a comparative analysis of the models' accuracy and effectiveness in predicting rainfall patterns in Nigeria.
![rainfall1](https://github.com/SonOfGod04/Nigeria_Rainfall_Forecasting/blob/main/Screenshot%20(205).png)


