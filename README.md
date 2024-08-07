# Analyzing Search Traffic to Predict Stock Performance of Mercado Libre
## Overview
A growth analyst at Mercado Libre, the leading e-commerce site in Latin America with over 200 million users analyzes the company's financial data and user search data to find innovative ways to drive the company's growth. The specific challenge is to determine if predicting the search traffic can help in successfully trading the company's stock.

## The forecast analysis is divided into four steps:

### Step 1: Find Unusual Patterns in Hourly Google Search Traffic
#### Objective: Identify anomalies or unusual patterns in the hourly Google search traffic data.
#### Tasks: 
1. Load and preprocess the hourly search traffic data.
2. Use statistical methods or visualization techniques to detect outliers and unusual trends.
### Step 2: Mine the Search Traffic Data for Seasonality
#### Objective: Analyze the search traffic data for seasonal trends and patterns.
#### Tasks:
1. Decompose the search traffic data to extract and understand its seasonal components.
2. Use time series analysis tools to identify daily, weekly, and yearly seasonal trends.
3. Visualize the seasonal patterns and interpret their significance.
### Step 3: Relate the Search Traffic to Stock Price Patterns
#### Objective: Determine if there is a relationship between search traffic and stock price movements.
#### Tasks:
1. Obtain historical stock price data for Mercado Libre.
2. Compare the search traffic data with the stock price data to find correlations.
3. Analyze the lagged effects of search traffic on stock prices to identify any predictive power.

### Step 4: Create a Time Series Model with Prophet
#### Objective: Develop a time series model to forecast future search traffic.
#### Tasks:
1. Use the Prophet library to create a time series model based on the search traffic data.
2. Train the model and validate its performance using historical data.
3. Generate forecasts for future search traffic and visualize the results.

### Getting Started
#### Data Collection:

1. Obtain the hourly Google search traffic data and historical stock price data for Mercado Libre.
2. Ensure the data is clean and properly formatted for analysis.

#### Tools and Libraries:

1. Python: The primary programming language for this challenge.
2. Libraries: pandas, numpy, matplotlib, Prophet, and any other relevant libraries for time series analysis and visualization.

#### Environment Setup:

1. Set up a Python environment with the necessary libraries installed.
2. Ensure you have access to a Jupyter Notebook or any other IDE for running your analysis scripts.
3. Clone the Repository:

    [[git clone https://github.com/jackkuppuswamy/prophet-challenge.git](https://github.com/jackkuppuswamy/prophet-challenge))

4. Navigate to the Project Directory:

    cd prophet-challenge

5. Run the Application: Start Jupyter Notebook forecasting_net_prophet.ipynb file to interactively execute, analyze and predict the search traffic and its impact on trading the stock. 
    

# Contributing
Contributions are welcome! Fork the repository, create a branch, make your changes, and submit a pull request.