# ₿ Crypto API ETL Pipeline Project
This project develops an end-to-end data pipelione to collect and visualizes real-time cryptocurrency market data using the CoinGecko API, Python, MySQL, and Power BI.

## Overview

This project demonstrates a complete data analytics workflow that collects, processes, and visualizes real-time cryptocurrency market data using the CoinGecko API, Python, MySQL, and Power BI.

The goal of this project is to showcase technical skills in API integration, data transformation, SQL database management, and interactive dashboard design. It highlights how market data can be automated, structured, and visualized for decision-making and trend analysis.

## 📈 Visualization

Power BI was connected to MySQL to load data from python. The ETL technical process can be viewed [here](ETL-Process.md). 

Allows users to slice between 1000+ cryptocurrencies and view the symbol, logo, price, volume, price change in the past day, all-time-low, and all-time-high data.

Graphs show the top 10 cryptocurrency rise and loss in terms of percentage in the past 24 hours. The graphs are limited to the top 100 largest coins by market cap to avoid distortion from smaller volume coins with large percentage changes.

## 📊 Power BI Report:
This report can be viewed and interacted with [Here.](https://app.powerbi.com/view?r=eyJrIjoiZTNmZmJiM2ItOTIyNS00NTlmLTk0MmUtNzRmMDQ2MzUxZjdhIiwidCI6IjYyMDRjNjEwLTZmYjUtNGQwNi04YzA0LWEyMWJkMDFmMmU0NSIsImMiOjF9)

<img width="1326" height="768" alt="image" src="https://github.com/user-attachments/assets/9571185f-eb01-4b8d-97d0-ad4ed5a7dcc0" />

## 📈 Metric Analysis
This dashboard tracks key cryptocurrency performance indicators that provide insights into market behavior, volatility, and investment opportunities:

### 💰 Price Metrics
- **Current Price (USD)**: Real-time valuation of each cryptocurrency, enabling comparison across assets and tracking of market movements.
- **24h Price Change (%)**: Measures short-term volatility and momentum. Positive changes indicate bullish sentiment, while negative changes signal bearish trends or profit-taking.

### 📊 Volume Analysis
- **24h Trading Volume (USD)**: Indicates liquidity and market activity. Higher volume suggests strong interest and easier entry/exit for traders. Low volume coins may experience higher price slippage.

### 📉 Historical Performance
- **All-Time High (ATH)**: Shows the peak price and date achieved. Useful for identifying potential resistance levels and measuring distance from historical peaks.
- **All-Time Low (ATL)**: Reveals the lowest price point and date. Helps assess risk/reward potential and recovery strength since bottom.

### 🏆 Market Cap Analysis
- **Market Capitalization**: Total value of circulating supply (Price × Circulating Supply). Used to rank cryptocurrencies and assess relative size and stability.
- **Rank by Market Cap**: Filters help focus on established assets (Top 100) versus emerging/speculative projects outside of the top rankings.

### 🔄 Comparative Metrics
- **Top 10 Gainers/Losers (24h)**: Identifies momentum plays and potential volatility. Limited to top 100 by market cap to filter out pump-and-dump schemes.

## 💼 Business Insights

### 1. 📈 Market Sentiment & Trend Identification
The dashboard reveals broad market sentiment through the Gainers vs. Losers analysis. When the majority of top 100 coins show positive 24h changes, it indicates bullish market conditions (often called "altcoin season"). Conversely, widespread losses suggest risk-off sentiment or market corrections. This helps investors time entry or exit points and adjust portfolio risk exposure.

### 2. ⚠️ Volatility & Risk Assessment
By analyzing 24h price changes alongside trading volume, users can identify highly volatile assets that may present trading opportunities or heightened risk. Coins with large price swings on low volume indicate thin liquidity and potential for manipulation, while high-volume movements suggest genuine market interest.

### 3. 💎 Recovery & Value Opportunities
The ATH/ATL metrics help identify assets trading at significant discounts from historical peaks. Coins near their ATL may represent value opportunities if fundamentals remain strong, while assets near ATH face potential resistance and profit-taking pressure.

### 4. 💧 Liquidity & Trading Execution
Volume analysis is critical for traders planning large positions. High 24h volume indicates deep liquidity, enabling easier order execution without significant price impact (slippage). Low-volume coins may require limit orders or smaller position sizes to avoid adverse price movements.
### 5. 🎯 Market Cap Concentration & Diversification
By filtering through different market cap tiers, investors can assess concentration risk. If Bitcoin and Ethereum dominate total market cap, altcoins may be underperforming. If smaller cap coins show strong gains, it suggests risk appetite is increasing.

### 6. ⚖️ Data-Driven Portfolio Rebalancing
Real-time price and volume data enables systematic portfolio rebalancing. Investors can set rules like "rebalance when any asset deviates >20% from target allocation" or "reduce exposure to assets showing >3 consecutive days of decline with falling volume."

## 💻 Technology

Python – API extraction, data processing (Pandas)

CoinGecko API – Real-time crypto market data

Power BI – Visualization and analytics

MySQL – Data storage and management

VS Code – Development environment
