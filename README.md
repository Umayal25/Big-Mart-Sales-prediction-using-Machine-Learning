
# BigMart Sales Prediction using Machine Learning

## Overview

Welcome to the BigMart Sales Prediction project! This project leverages machine learning algorithms to predict sales for BigMart stores. By analyzing various factors such as item characteristics and store attributes, we aim to provide accurate sales forecasts. This project is not only a technical endeavor but also aims to benefit society by helping retailers optimize inventory management and improve customer satisfaction.

## Table of Contents

1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Benefits](#benefits)
4. [Use Cases](#use-cases)
5. [Machine Learning Algorithms](#machine-learning-algorithms)
6. [Evaluation Metrics](#evaluation-metrics)
7. [How to Run the Project](#how-to-run-the-project)
8. [Contributing](#contributing)
9. [Screenshots](#screenshots)

## Introduction

The BigMart Sales Prediction project aims to provide accurate sales predictions using machine learning techniques. Accurate sales predictions can help retailers manage inventory efficiently, reduce waste, and improve profitability. This project serves as a useful tool for data scientists, analysts, and retail managers to understand sales patterns and make informed decisions.

## Project Overview

This project involves:

- Data preprocessing and feature engineering.
- Implementing various machine learning algorithms.
- Evaluating model performance using metrics like RMSE.
- Developing a web application using Flask for easy interaction.

## Benefits

- **Inventory Management:** Helps in managing stock levels efficiently, reducing overstock and stockouts.
- **Customer Satisfaction:** Ensures that popular items are always in stock, improving customer satisfaction.
- **Cost Reduction:** Reduces costs associated with excess inventory and storage.
- **Sales Optimization:** Provides insights to maximize sales and profitability.

## Use Cases

- **Retail Management:** Helps store managers and owners predict future sales and manage inventory accordingly.
- **Supply Chain Optimization:** Assists in optimizing supply chain operations by forecasting demand.
- **Marketing Strategies:** Aids in developing targeted marketing strategies based on predicted sales trends.
- **Financial Planning:** Supports financial planning and budgeting by providing accurate sales forecasts.

## Machine Learning Algorithms

The project implements several machine learning algorithms, including:

1. **XGBoost**
2. **Linear Regression**
3. **Lasso Regression**
4. **Ridge Regression**
5. **GradientBoostingRegressor**
6. **Random Forest Regressor**

These algorithms are compared based on their performance, with the best model being used for the final predictions.

## Evaluation Metrics
1. Mean Absolute Error (MAE): Measures the average magnitude of errors in a set of predictions, without considering their direction. Lower values indicate better accuracy.
2. Mean Squared Error (MSE): Measures the average squared difference between the estimated values and the actual value. Lower values indicate better accuracy.
3. Root Mean Squared Error (RMSE): The square root of the mean squared error. It provides an estimate of the standard deviation of the prediction errors. Lower values indicate better accuracy.
4. R-squared (R2): Indicates the proportion of the variance in the dependent variable that is predictable from the independent variables. Values closer to 1 indicate a better fit.

## How to Run the Project

### Prerequisites

- Python 3.12.2 (64-bit)
- Required Python libraries: numpy, pandas, matplotlib, sklearn, xgboost, flask

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/bigmart-sales-prediction.git
    cd bigmart-sales-prediction
    ```

2. Create and activate a virtual environment:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

### Running the Project

1. Start the Flask web application:

    ```bash
    python app.py
    ```

2. Open your web browser and navigate to `http://localhost:5000`.

3. Use the web interface to input item and store details and get sales predictions.

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request. For major changes, please open an issue first to discuss what you would like to change.

## Screen Shots
![image](https://github.com/Umayal25/Big-Mart-Sales-Prediction-Using-Machine-Learning/assets/92157178/822d2b61-2353-44d7-adde-e365567dc1db)

![image](https://github.com/Umayal25/Big-Mart-Sales-Prediction-Using-Machine-Learning/assets/92157178/68a63c39-742f-4df0-8f46-ba51ff644dd3)
