Overview

This project aims to predict stock prices using historical data and machine learning techniques within Snowflake. It involves fetching stock data, storing it in Snowflake, running automated workflows using Apache Airflow, and performing financial analytics to derive insights.

Features

Stock Data Ingestion: Fetches historical stock data (last 180 days) using yfinance.

Data Storage: Stores data in Snowflake for efficient querying and analysis.

Automated Data Pipeline: Uses Apache Airflow to update stock prices daily.

Machine Learning Forecasting: Predicts stock prices for the next 7 days using Snowflake ML functions.

Financial Analysis: Includes trend analysis, volatility analysis, and portfolio optimization.

Tech Stack

Programming Language: Python, SQL

Data Source: yfinance

Database: Snowflake

Orchestration: Apache Airflow

Machine Learning: Snowflake ML functions

Visualization: Matplotlib, Seaborn

Installation & Setup

Prerequisites

Ensure you have the following installed:

Python 3.x

Apache Airflow

Snowflake Account

Required Python Libraries: yfinance, pandas, snowflake-connector-python, matplotlib, seaborn

Steps

Clone the repository:

git clone https://github.com/yourusername/Stock-Price-Prediction-Analytics.git
cd Stock-Price-Prediction-Analytics

Install dependencies:

pip install -r requirements.txt

Set up Snowflake credentials.

Configure Airflow DAG for automated execution.

Run the pipeline.

Project Structure

Stock-Price-Prediction-Analytics/
│── data/                      # Contains sample data files
│── dags/                      # Airflow DAGs for automation
│── scripts/                   # Python scripts for data ingestion & processing
│── models/                    # ML models and forecasting logic
│── notebooks/                 # Jupyter notebooks for analysis
│── reports/                   # Project reports and insights
│── README.md                  # Project documentation

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



