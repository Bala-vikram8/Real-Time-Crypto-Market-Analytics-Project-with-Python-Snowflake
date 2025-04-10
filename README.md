# Real-Time Crypto Market Analytics with Python and Snowflake

## Overview
This project performs real-time analytics on cryptocurrency data using Python, Snowflake, and public APIs. The key steps include:
- Fetching live cryptocurrency market data from **CoinCap** and **CoinGecko APIs**.
- Cleaning and transforming raw data into a format suitable for analysis.
- Storing the processed data in **Snowflake**.
- Using **SQL** to create complex queries to analyze cryptocurrency market performance, volatility, liquidity, and more.

## Technologies Used
- **Python** (for data extraction, transformation, and analysis)
- **Snowflake** (for data storage and advanced analytics)
- **SQL** (for querying and generating insights)
- **Pandas** (for data manipulation)
- **Matplotlib** & **Seaborn** (for data visualization)
- **Requests** (for API integration)

## Project Highlights
- **Data Collection**: Extracts real-time data using **CoinCap** and **CoinGecko** APIs.
- **Data Transformation**: Cleans and processes the raw data to remove duplicates, handle missing values, and format dates.
- **SQL Queries**: Executes complex SQL queries on Snowflake to generate insights, including:
  - Top-performing coins by market cap
  - Coins with the highest volatility
  - Liquidity analysis of coins based on trading volume and market cap
- **Data Visualizations**: Visualizes key metrics using **Matplotlib** and **Seaborn**.

## Files Included
- `Real-Time Crypto Market Analytics with Python and Snowflake.ipynb_`: Jupyter notebook containing the analysis and code.
- `coingecko_all_coins.csv`: Sample dataset of coins used for analysis (before cleaning).
- `coingecko_all_coins_cleaned_final.csv`: Cleaned and processed dataset ready for analysis.
