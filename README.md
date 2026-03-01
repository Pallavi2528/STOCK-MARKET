# 📈 Stock Market Analysis Dashboard

## 🚀 **Project Overview**
To analyze historical price trends and trading volumes for major tech stocks (AAPL, MSFT, NFLX, GOOG) to identify market volatility and investment opportunities.

---

## 🛠️ **Tech Stack & Tools**
* **Role**: Business Analyst
* **Tools**: Power BI, MS Excel, DAX
* **Project Level**: Intermediate

---

## 💎 **Key Performance Indicators (KPIs)**
The dashboard monitors these critical market metrics:
* 📊 **Total Trading Volume**: `7.96B`
* 💵 **Average Close Price**: `$215.38`
* 🔝 **Max Stock High**: `$373.83`

---

## 📂 **Dataset Details**
The dataset contains daily historical stock prices for four major tickers:
* **Tickers**: AAPL, MSFT, NFLX, GOOG
* **Key Columns**: Date, Open/Close, High/Low, Adj Close, and Volume

---

## 🏗️ **Dashboard Architecture**
1. **Top Layer**: KPI cards for Total Volume, Average Close, and Highest Price.
2. **Middle Layer**: 
    * **Line Chart**: Price Trend by Date to identify growth patterns and dips.
    * **Clustered Bar Chart**: Daily Price Spread to compare volatility.
3. **Bottom Layer**: Interactive Slicers for Ticker and Date range control.

---

## 📝 **DAX Measures**
Calculations used in the report:

`Total Volume = SUM('stocks'[Volume])`

`Avg Close = AVERAGE('stocks'[Close])`

`Highest Price = MAX('stocks'[High])`

---

## 💡 **Business Insights & Recommendations**
Based on the analysis of the stock data, here are the key takeaways:

* **Trend Identification**: The line chart tracks daily closing prices to help stakeholders spot market trends and potential investment entry points.
* **Volatility Insights**: By comparing High and Low prices, the dashboard highlights the daily price movement across tickers.
* **Interactive Filtering**: Slicers allow stakeholders to filter for specific companies or timeframes for deeper analysis.
* **Volume Analysis**: A total trading volume of `7.96B` shares was analyzed to understand market activity.

---

## ✅ **Conclusion**
This dashboard successfully transforms raw historical stock data into actionable market insights. By centralizing KPIs and implementing interactive filtering, it empowers stakeholders to optimize investment strategies through data-driven decision-making.
