# Live Cryptocurrency Data Fetching and Analysis
This repository contains an automated script for fetching, analyzing, and storing live data of the top 50 cryptocurrencies. The data is sourced from the CoinGecko API and saved in an Excel file that updates continuously, allowing you to track current prices, market caps, trading volumes, and 24-hour price changes for real-time insights.

## Objective
The goal of this project is to:

- Fetch live data for the top 50 cryptocurrencies.
- Analyze key metrics including market capitalization, trading volume, and 24-hour price change.
- Present the data in an Excel sheet that refreshes automatically.
## Project Structure
### 1. Fetching Live Cryptocurrency Data
Using the CoinGecko API, the script fetches data for the top 50 cryptocurrencies. Key data points include:

- Cryptocurrency Name
- Symbol
- Current Price (in USD)
- Market Capitalization
- 24-hour Trading Volume
- 24-hour Price Change (percentage)
### 2. Data Analysis
The script conducts various analyses, such as:

- Identifying the top 5 cryptocurrencies by market capitalization.
- Analyzing 24-hour price change percentages for market trends.
- Calculating the average price of the top 50 cryptocurrencies.
## Visualizations include:

- A bar chart showing top 5 cryptocurrencies by market capitalization.
- A trend graph of 24-hour price change percentages for the top 10 cryptocurrencies.
### 3. Live-Running Excel Sheet
The Excel sheet stores live cryptocurrency data, continuously updating with the latest data points.

#### Requirements
Install the following Python libraries:

```bash
pip install pandas requests openpyxl matplotlib seaborn scikit-learn
```
#### Usage
To run this script, execute:

```bash
python crypto_analysis.py
```
## Code Overview
### Step 1: Import Libraries
Essential libraries include `pandas`, `requests`, `matplotlib`, `seaborn`, and `openpyxl`.

### Step 2: Fetch Data
The `fetch_live_data` function retrieves data from CoinGecko’s API and stores it in a `DataFrame`.

### Step 3: Data Cleaning
The script checks for and handles missing values and duplicates.

### Step 4: Data Analysis
Using sorting and filtering, the script identifies top-performing cryptocurrencies and visualizes the results using bar charts and line graphs.

### Step 5: Live Excel Update
The `create_excel_with_headers` and `update_excel_sheet` functions manage the creation and live-updating of the Excel file.

## Example Output
The script will output a continuously updated Excel file `live_data.xlsx`, displaying information like:

- Top cryptocurrencies by market cap.
- 24-hour price change trends.
- Average price and market cap benchmarks.
## Insights and Key Takeaways
This project demonstrates real-time data tracking in cryptocurrency markets. Key points include:

- High market cap coins such as Bitcoin and Ethereum provide stable investment opportunities.
- Cryptocurrencies with significant price changes are highly volatile and can present higher risk/reward.

# Files to be uploaded in the repository: 
**Code -->** Assessment Task- Fetching and Analyzing Top 50 Live Cryptocurrency Data Objective.ipynb, Analysis Report.docx, live_data.xlsx


