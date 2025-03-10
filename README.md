Overview

This project aims to predict stock prices using historical data and machine learning techniques within Snowflake. It involves fetching stock data, storing it in Snowflake, running automated workflows using Apache Airflow, and performing financial analytics to derive insights.

Features

Stock Data Ingestion: Fetches historical stock data (last 180 days) using yfinance.

Data Storage: Stores data in Snowflake for efficient querying and analysis.

Automated Data Pipeline: Uses Apache Airflow to update stock prices daily.

Machine Learning Forecasting: Predicts stock prices for the next 7 days using Snowflake ML functions.

Financial Analysis: Includes trend analysis, volatility analysis, and portfolio optimization.

Technology used
Apache Airflow: For orchestrating the ETL process.
Snowflake: For data storage, processing, and machine learning.
Alpha Vantage API: For fetching stock price data.
Python: The primary programming language used for the implementation.

Prerequisites

Apache Airflow: Ensure you have Apache Airflow installed and configured in your environment.
Snowflake Account: You need access to a Snowflake account and have the necessary privileges to create databases and schemas.
Alpha Vantage API Key: Obtain an API key from Alpha Vantage and store it in Airflow's Variables as vantage_api_key.

Steps

1. Clone the repository:

git clone https://github.com/yourusername/Stock-Price-Prediction-Analytics.git
cd Stock-Price-Prediction-Analytics

2. Install dependencies:

 pip install -r requirements.txt
 
3. Configure your Airflow connection for Snowflake:

Go to the Airflow UI.
Navigate to Admin > Connections.
Add a new connection with the following parameters:
Conn Id: snowflake_conn
Conn Type: Snowflake
Fill in your Snowflake account information (user, password, account, etc.).


Usage

Run data ingestion: Fetch and store stock data in Snowflake.

Schedule DAGs: Automate daily stock price updates with Airflow.

Run ML Forecasting: Predict future stock prices within Snowflake.

Analyze Results: Perform financial analysis and visualize insights.

Results & Insights

The project generates stock price predictions and evaluates trends.

It provides insights into stock volatility and optimal portfolio allocation.

Contributions

Feel free to fork this repository and contribute by submitting pull requests.

License

This project is licensed under the MIT License.

Author

Akhilesh

Acknowledgments

Apache Airflow
Snowflake
Alpha Vantage



