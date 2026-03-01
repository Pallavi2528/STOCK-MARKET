# 📈 Stock Market Analysis Dashboard

## 🚀 **Project Overview**
[cite_start]To analyze historical price trends and trading volumes for major tech stocks (AAPL, MSFT, NFLX, GOOG) to identify market volatility and investment opportunities. [cite: 4, 5, 7]

---

## 🛠️ **Tech Stack & Tools**
* [cite_start]**Role**: Business Analyst [cite: 1]
* [cite_start]**Tools**: Power BI, MS Excel, DAX [cite: 1]
* [cite_start]**Project Level**: Intermediate [cite: 1]

---

## 💎 **Key Performance Indicators (KPIs)**
The dashboard monitors these critical market metrics:
* [cite_start]📊 **Total Trading Volume**: `7.96B` [cite: 17]
* [cite_start]💵 **Average Close Price**: `$215.38` [cite: 20]
* [cite_start]🔝 **Max Stock High**: `$373.83` [cite: 23]

---

## 📂 **Dataset Details**
[cite_start]The dataset contains daily historical stock prices for four major tickers: [cite: 7]
* [cite_start]**Tickers**: AAPL, MSFT, NFLX, GOOG [cite: 9]
* [cite_start]**Key Columns**: Date, Open/Close, High/Low, Adj Close, and Volume [cite: 10, 11, 12]

---

## 🏗️ **Dashboard Architecture**
1. [cite_start]**Top Layer**: KPI cards for Total Volume, Average Close, and Highest Price [cite: 14, 15]
2. **Middle Layer**: 
    * [cite_start]**Line Chart**: Price Trend by Date to identify growth patterns and dips [cite: 27, 28]
    * [cite_start]**Clustered Bar Chart**: Daily Price Spread to compare volatility [cite: 38, 39]
3. [cite_start]**Bottom Layer**: Interactive Slicers for Ticker and Date range control [cite: 49, 50, 51, 56]

---

## 📝 **DAX Measures**
Calculations used in the report:

[cite_start]`Total Volume = SUM('stocks'[Volume])` [cite: 18]

[cite_start]`Avg Close = AVERAGE('stocks'[Close])` [cite: 21]

[cite_start]`Highest Price = MAX('stocks'[High])` [cite: 24]

---

## 💡 **Business Insights & Recommendations**
Based on the analysis of the stock data, here are the key takeaways:

* [cite_start]**Trend Identification**: The line chart tracks daily closing prices to help stakeholders spot market trends and potential investment entry points. [cite: 28]
* [cite_start]**Volatility Insights**: By comparing High and Low prices, the dashboard highlights the daily price movement across tickers. [cite: 39]
* [cite_start]**Interactive Filtering**: Slicers allow stakeholders to filter for specific companies or timeframes for deeper analysis. [cite: 52, 57]
* [cite_start]**Volume Analysis**: A total trading volume of `7.96B` shares was analyzed to understand market activity. [cite: 17, 91]

---

## ✅ **Conclusion**
This dashboard successfully transforms raw historical stock data into actionable market insights. [cite_start]By centralizing KPIs and implementing interactive filtering, it empowers stakeholders to optimize investment strategies through data-driven decision-making. [cite: 108, 109]
