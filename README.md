# Cryptocurrency Price Tracker

This project fetches real-time cryptocurrency price data using the CoinGecko API and visualizes the 24-hour price change for multiple cryptocurrencies.

## Features
- Retrieves current price, market cap, 24-hour volume, and percentage change for selected cryptocurrencies.
- Uses the CoinGecko API to fetch data.
- Displays the 24-hour price change using a bar chart.

## Requirements
Ensure you have Python installed along with the following dependencies:

```sh
pip install pandas matplotlib pycoingecko
```

## Usage
1. Run the script to fetch and display cryptocurrency data:
   ```sh
   python script.py
   ```
2. The script will:
   - Retrieve data for Bitcoin, Ethereum, Binance Coin, and Polkadot.
   - Print the retrieved data in tabular format.
   - Plot a bar chart representing the 24-hour price change.

## Code Overview
- **CoinGecko API Initialization**: Connects to the API and checks connectivity.
- **Data Fetching**: Retrieves price details for selected cryptocurrencies.
- **Data Processing**: Formats and structures the retrieved data in a Pandas DataFrame.
- **Visualization**: Uses Matplotlib to plot the 24-hour price change.

## Example Output
- Printed cryptocurrency data in tabular format.
- A bar chart displaying price changes, where:
  - **Blue** bars indicate a positive change.
  - **Red** bars indicate a negative change.

## License
This project is open-source and available under the MIT License.

