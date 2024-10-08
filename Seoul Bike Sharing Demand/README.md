# Seoul Bike Sharing Demand Prediction

## 1. Introduction
Currently, rental bikes are introduced in many urban cities to enhance mobility comfort. It is important to make rental bikes available and accessible to the public at the right time to minimize waiting times. Ensuring a stable supply of rental bikes is a major concern, which requires predicting the bike count required each hour. 

This project aims to predict the demand for rental bikes in Seoul based on several factors, including weather conditions and date information.

## 2. Dataset Description
The dataset contains the following features:

| Variable Name            | Role    | Type       | Description                           | Units    | Missing Values |
|--------------------------|---------|------------|---------------------------------------|----------|----------------|
| **Date**                  | Feature | Date       | Date of observation                   | -        | No             |
| **Temperature**           | Feature | Numeric    | Hourly temperature                    | Celsius  | No             |
| **Humidity**              | Feature | Numeric    | Hourly humidity                       | %        | No             |
| **Windspeed**             | Feature | Numeric    | Hourly wind speed                     | m/s      | No             |
| **Visibility**            | Feature | Numeric    | Hourly visibility                     | 10m      | No             |
| **Dewpoint**              | Feature | Numeric    | Hourly dew point temperature          | Celsius  | No             |
| **Solar radiation**       | Feature | Numeric    | Hourly solar radiation                | MJ/m^2   | No             |
| **Snowfall**              | Feature | Numeric    | Hourly snowfall                       | cm       | No             |
| **Rainfall**              | Feature | Numeric    | Hourly rainfall                       | mm       | No             |
| **Bikes Rented**          | Target  | Numeric    | Number of bikes rented per hour       | Count    | No             |

## 3. Project Structure
This project is divided into the following steps:
1. Data exploration and preprocessing
2. Feature engineering and selection
3. Model training and evaluation
4. Predictions on future data
5. Visualization of results

## 4. Model and Tools Used
- **Python**: The primary programming language
- **Jupyter Notebook**: For interactive data exploration
- **Libraries**: 
  - `pandas` for data manipulation
  - `scikit-learn` for model development and evaluation
  - `matplotlib` and `seaborn` for data visualization
