# 📊 Real-Time Crypto Analytics Dashboard

A professional **Power BI cryptocurrency analytics dashboard** that uses live market data from the **CoinGecko API** to provide an interactive view of cryptocurrency prices, market performance, trading volume, volatility, and 24-hour market movements.

The dashboard is designed to help users quickly understand overall crypto-market conditions and drill down into individual cryptocurrencies using interactive filters.

---

## 🚀 Project Overview

The **Real-Time Crypto Analytics Dashboard** transforms cryptocurrency market data into an interactive financial analytics dashboard using **Power BI, Power Query, and DAX**.

The dashboard provides insights into:

* 📈 Overall cryptocurrency market performance
* 💰 Total market capitalization
* 📊 24-hour price movements
* 🏆 Top gaining cryptocurrencies
* 📉 Top losing cryptocurrencies
* 💹 Trading volume
* ⚡ Market volatility
* 🔎 Individual cryptocurrency analysis
* 📋 Detailed cryptocurrency market table

The project demonstrates practical skills in **data extraction, transformation, analytical calculations, dashboard design, and financial data visualization**.

---

## 🛠️ Tech Stack

| Technology           | Purpose                                     |
| -------------------- | ------------------------------------------- |
| **Power BI Desktop** | Dashboard development and visualization     |
| **Power Query (M)**  | Data extraction and transformation          |
| **DAX**              | Calculated measures and analytical logic    |
| **CoinGecko API**    | Cryptocurrency market data source           |
| **REST API**         | Retrieval of live crypto market information |

---

## 🔄 Data Pipeline

```text
CoinGecko API
      │
      ▼
Cryptocurrency Market Data
      │
      ▼
Power Query
      │
      ├── Data Cleaning
      ├── Data Transformation
      └── Data Preparation
      │
      ▼
DAX Calculations
      │
      ├── Market KPIs
      ├── Gainers / Losers
      ├── Volatility
      └── Market Metrics
      │
      ▼
Interactive Power BI Dashboard
```

---

## 📡 Data Source

The dashboard uses cryptocurrency market data retrieved from the **CoinGecko API**.

### Key Data Fields

* Coin Name
* Symbol
* Current Price (USD)
* 24-hour Price Change %
* Market Capitalization
* Market Cap Rank
* Total Trading Volume
* 24-hour High
* 24-hour Low
* Last Updated Timestamp

The dataset can be refreshed to reflect updated cryptocurrency market conditions.

---

# 📈 Dashboard Features

## 1. 💰 Market KPI Cards

The dashboard provides high-level market indicators through interactive KPI cards.

### Total Market Cap

Displays the overall cryptocurrency market capitalization.

### 24h Change %

Shows the overall market movement over the previous 24 hours.

Conditional formatting is used to distinguish market movement:

* 🟢 Green → Positive movement
* 🔴 Red → Negative movement

### 24h Growth

Provides an additional view of market growth based on the available cryptocurrency data.

### Total 24h Volume

Displays the overall trading volume across the analyzed cryptocurrencies.

### Market Volatility

Volatility is calculated using the **standard deviation of 24-hour price changes**, providing an indication of market risk and price fluctuations.

---

## 2. 🏆 Top Gainer & Top Loser

Dynamic DAX calculations identify the cryptocurrencies experiencing the largest movements.

### Top Gainer

Displays the cryptocurrency with the highest 24-hour increase.

### Top Loser

Displays the cryptocurrency with the largest 24-hour decrease.

This allows users to immediately identify the strongest and weakest performers in the dataset.

---

## 3. 📊 Top 10 Crypto Price Chart

An interactive bar chart displays the **top 10 cryptocurrencies by price**.

Features include:

* Cryptocurrency name
* Current price in USD
* Descending price order
* Performance-based visual formatting

This provides a quick comparison of cryptocurrency prices.

---

## 4. 📋 Interactive Cryptocurrency Table

The detailed table provides a complete snapshot of the analyzed cryptocurrencies.

| Field        | Description                   |
| ------------ | ----------------------------- |
| Name         | Cryptocurrency name           |
| Symbol       | Trading symbol                |
| Price        | Current USD price             |
| 24h Change % | Price movement over 24 hours  |
| Volume       | Trading volume                |
| Market Rank  | Cryptocurrency market ranking |

Conditional formatting highlights market performance:

* 🟢 Positive returns
* 🔴 Negative returns

---

## 5. 🔎 Interactive Cryptocurrency Filter

The dashboard includes an interactive **Name slicer** that allows users to select individual cryptocurrencies.

When a cryptocurrency is selected, the dashboard visuals dynamically update to reflect the selected data.

---

# 🎨 Dashboard Design

The dashboard uses a dark financial-dashboard theme with:

* KPI cards
* Interactive slicers
* Data tables
* Bar charts
* Conditional formatting
* Consistent typography
* Green/red performance indicators
* Structured visual hierarchy

The layout is designed to make important market information visible at a glance.

---

# 📷 Dashboard Preview

### Main Dashboard

![Crypto Analytics Dashboard](https://github.com/user-attachments/assets/e3ca4fbf-126f-4117-bcbe-ac53045a7893)

### Detailed Dashboard View

![Crypto Dashboard](https://github.com/user-attachments/assets/5c061456-9698-4e2d-89f4-4a08b104462a)

---

# 📂 Project Structure

```text
Real-Time-Crypto-Analytics-Dashboard/
│
├── Real-Time Crypto Analytics Dashboard.pbix
├── README.md
│
└── screenshots/
    ├── crypto-dashboard.png
    └── crypto-dashboard-detail.png
```

---

# 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/Real-Time-Crypto-Analytics-Dashboard.git
```

### 2. Open the Power BI file

Open:

```text
Real-Time Crypto Analytics Dashboard.pbix
```

using **Power BI Desktop**.

### 3. Refresh the data

In Power BI Desktop:

```text
Home → Refresh
```

This refreshes the cryptocurrency dataset from the configured data source.

### 4. Explore the dashboard

Use the cryptocurrency slicer and interact with the dashboard visuals to analyze:

* Prices
* Market movements
* Trading volume
* Market rankings
* Gainers and losers
* Volatility

---

# 💼 Business Use Cases

This dashboard can be useful for:

* 📈 Crypto traders
* 💼 Financial analysts
* 🔬 Investment researchers
* 📊 Portfolio managers
* ⛓️ Blockchain enthusiasts
* 💰 Cryptocurrency market researchers

It provides a consolidated view of cryptocurrency market activity and makes large amounts of market data easier to interpret.

---

# 🧠 Key DAX & Analytics Concepts

The project demonstrates practical use of DAX for:

* KPI calculations
* Identifying maximum/minimum performers
* 24-hour price movement analysis
* Market volatility calculations
* Dynamic filtering
* Ranking cryptocurrencies
* Conditional formatting
* Aggregating market metrics

A key analytical component is market volatility, calculated using the **standard deviation of 24-hour percentage changes**.

---

# 📚 Key Learning Outcomes

Through this project, I developed practical experience with:

* Real-time API-based data integration
* Power Query data transformation
* DAX analytical calculations
* Financial data analysis
* Conditional formatting
* Interactive dashboard design
* Data visualization
* Data storytelling
* KPI development
* Power BI dashboard optimization

---

# ⭐ Why This Project Stands Out

* 🔄 **API-driven cryptocurrency data**
* 📊 **Interactive Power BI dashboard**
* 🧮 **DAX-based analytical calculations**
* ⚡ **Market volatility analysis**
* 🏆 **Dynamic gainers and losers**
* 🔎 **Interactive cryptocurrency filtering**
* 🎨 **Professional financial dashboard design**
* 📈 **Real-world financial analytics use case**

---

# 🔮 Future Improvements

Potential future enhancements include:

* Historical price trend analysis
* Candlestick charts
* Moving averages
* RSI and other technical indicators
* Cryptocurrency price alerts
* Portfolio tracking
* Historical volatility trends
* Automated scheduled refresh
* Additional cryptocurrency exchanges
* Advanced forecasting and price prediction
* Power BI Service deployment

---

# 👨‍💻 Author

**Harsh Selokar**

B.Tech — Computer Science & Engineering

Backend / Data Analytics Enthusiast

---

## ⭐ If you found this project useful

Consider giving the repository a ⭐ on GitHub!

