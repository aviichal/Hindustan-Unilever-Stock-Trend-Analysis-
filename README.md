# Hindustan Unilever Stock Trend Analysis 

## Problem Statement

This Power BI dashboard provides an in-depth analysis of Hindustan Unilever's (HUL) stock trends, helping investors and analysts gain insights into stock performance over time. The dashboard includes visualizations on stock price movement, volume trends, moving averages, and other key metrics to assist in making informed investment decisions. The analysis also highlights patterns, anomalies, and correlations to better understand stock behavior.


### Steps followed 
Step 1: Data Loading

Imported stock price data into Power BI Desktop from a CSV file.Verified data integrity by checking for missing values, duplicate entries, and incorrect data types.

Step 2: Data Cleaning and Preprocessing

Used Power Query Editor to handle missing values and format date fields properly.Checked "Column Distribution", "Column Quality", and "Column Profile" to ensure consistency.Removed any unnecessary columns to optimize performance.

Step 3: Data Transformation

Created a calculated column for Daily Price Change using DAX.Computed Moving Averages (SMA, EMA) to observe trend smoothing.Added Volatility Measures, such as Standard Deviation of stock prices over a rolling window.

Step 4: Data Visualization

Used Line Charts to track the stock price movement over time.Created a Candlestick Chart for a detailed OHLC (Open-High-Low-Close) view.Added Volume Analysis using a Bar Chart to identify spikes in trading activity.Implemented Slicers for filtering by date ranges and time periods.Used a KPI Card to display Current Closing Price and % Change.Added a Sector Benchmark Comparison chart to compare HUL’s performance with industry peers.

Step 5: Time-Series Analysis

Implemented Moving Average Convergence Divergence (MACD) to analyze momentum shifts.Added Relative Strength Index (RSI) visualization to identify overbought/oversold conditions.Used trendlines to highlight patterns and support/resistance levels.

Step 6: Publishing and Sharing

Published the report to Power BI Service for easy accessibility.Created Dashboard Snapshots to highlight key insights for stakeholders.
# Key Insights

Stock Price Trends:

The stock shows periodic uptrends and corrections in response to market conditions.Strong support levels were observed at ₹X and resistance at ₹Y.

Volume and Price Correlation:

Higher trading volumes were seen during specific earnings announcements and market events.Spikes in volume often precede price breakouts or sharp corrections.

Moving Averages & RSI:

50-day SMA & 200-day SMA crossovers indicate bullish/bearish trends.RSI consistently above 70 indicates overbought conditions, while below 30 signals overselling.

Volatility & Risk Analysis:

Periods of high volatility correspond with macroeconomic events or earnings reports.
Standard deviation analysis suggests price deviations of X% over a 30-day window.

  ### Report Snapshots
  ![Image](https://github.com/user-attachments/assets/40288bd6-06b2-4feb-ad2a-1b05887e455b)
  ![Image](https://github.com/user-attachments/assets/3ac1e7a3-00ec-4cce-b2bf-5efb6a4d2925)
  ![Image](https://github.com/user-attachments/assets/b1776af2-779a-449a-8fba-3d21e6bd6703)
 
 ### Future Enhancements
 
 Integration of real-time stock price feeds.

Incorporation of predictive modeling using machine learning.

Comparative analysis with other FMCG stocks.

Sentiment analysis of news and social media trends impacting HUL stock.
 ### Conclusion
 
This Power BI report provides a comprehensive overview of Hindustan Unilever’s stock performance, enabling investors and analysts to make data-driven decisions. By leveraging multiple visualizations and technical indicators, the dashboard ensures better stock trend analysis and strategic investment planning

