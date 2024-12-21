# Crypto API Data Analysis

This project is designed to analyze the prices and performance of cryptocurrencies. Data is fetched from an API, processed, stored, and analyzed. The results are visualized to help users better understand the cryptocurrency market.

## Features
- *Data Fetching via API*: Retrieve cryptocurrency data such as prices, percentage changes, and other metrics.
- *Data Storage*: Save the fetched data in CSV format for further analysis.
- *Data Analysis*: Analyze performance changes over specific time intervals.
- *Data Visualization*: Visualize price trends and percentage changes using graphs.

## Requirements
- Python 3.7 or higher
- The following Python libraries:
  - requests
  - pandas
  - matplotlib
  - seaborn

## Installation
1. Clone or download the project to your local machine.
2. Install the required Python libraries:
   ```bash
   pip install requests pandas matplotlib seaborn
   ## Usage

1. *API Key*:  
   The project uses the CoinMarketCap API. Obtain an API key and specify it in the relevant file.

2. *Execution*:  
   Run the Python file to fetch, save, and analyze the data.

3. *Visualization*:  
   The analyzed data will be displayed through graphs.

---

## Outputs

- *CSV File*:  
  All cryptocurrency data is saved in CSV format.

- *Graphs*:  
  - *Time-Series Graphs*: Show price changes for a specific cryptocurrency over time.  
  - *Performance Graphs*: Compare percentage changes across different time intervals.

---

## Notes

- The project uses the free version of the CoinMarketCap API. Be mindful of the API call limits.
- Data is fetched every minute and appended to the existing CSV file.
