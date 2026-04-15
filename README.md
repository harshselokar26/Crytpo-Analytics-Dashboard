# 📊 Project Overview

- The Real-Time Crypto Analytics Dashboard is designed to monitor and analyze cryptocurrency market data in real time.
- It allows users to:
- Track overall market performance
- Identify top gainers and losers
- Analyze 24-hour price changes
- Monitor market volatility
- View total trading volume
- Filter data by individual cryptocurrencies
- his project demonstrates strong capabilities in:
- Data transformation (Power Query)
- DAX calculations
- Conditional formatting
- Interactive visual design
- Real-time API integration
- Professional dashboard layout structuring

# 🛠 Tools & Technologies Used

- Power BI Desktop
- Power Query (M Language)
- DAX (Data Analysis Expressions)
- CoinGecko API (Live Crypto Data Source)

# 🔄 Data Source

The dashboard uses live cryptocurrency data fetched from the CoinGecko API.

# Key data fields used:

- Coin Name
- Symbol
- Current Price (USD)
-24h Price Change %
- Market Cap
- Market Cap Rank
- Total Volume
- High/Low (24h)
- Last Updated Timestamp
- The dataset refreshes dynamically to reflect near real-time market changes.

📈 Key Features
1️⃣ KPI Cards
✅ Total Market Cap
- Displays overall market capitalization.

✅ 24h Change %
- Shows average market movement in the last 24 hours.
  
# Conditional formatting:

- Green → Positive movement
- Red → Negative movement

✅ Market Status Indicator

Displays:

🟢 BULL MARKET
🔴 BEAR MARKET

- Based on average 24h price change.

✅ Total 24h Volume

Displays overall trading volume in billions.

✅ Market Volatility

Calculated using standard deviation of 24h change percentage to measure risk level.

2️⃣ Top Gainer & Top Loser

- Dynamic DAX measures identify:
- Coin with highest 24h increase
- Coin with highest 24h decrease
- Display both coin name and percentage change

3️⃣ Top 10 Crypto Price Bar Chart

- Clustered bar chart showing:
- Top cryptocurrencies by price
- Sorted in descending order
- Optional dynamic color formatting based on performance

4️⃣ Interactive Data Table

- Displays:
- Name
- Symbol
- Price
- 24h Change %
- Volume
- Market Rank
- Includes conditional formatting:
- Green for gains
- Red for losses

5️⃣ Slicer Filter

- Users can filter the entire dashboard by cryptocurrency name.
- All visuals update dynamically.

📂 Project Structure
Real-Time-Crypto-Analytics-Dashboard/
│
├── CryptoDashboard.pbix
├── README.md
└── screenshots/
💡 Business Use Case

# This dashboard can be used by:

- Crypto traders
- Financial analysts
- Investment researchers
- Portfolio managers
- Blockchain enthusiasts
- It provides a quick snapshot of market health and trading activity.

# 🚀 How to Use

- Open CryptoDashboard.pbix in Power BI Desktop
- Click Refresh
- Use slicers to filter by cryptocurrency
- Analyze KPIs and charts

# 📌 Learning Outcomes

- Through this project, the following skills were demonstrated:
- Real-time data handling in Power BI
- Advanced DAX calculations
- Conditional formatting rules
- Dashboard UX optimization
- Data storytelling
- Financial metric analysis

📷 Preview

<img width="1328" height="730" alt="cryptomain ss" src="https://github.com/user-attachments/assets/e3ca4fbf-126f-4117-bcbe-ac53045a7893" />


<img width="1886" height="971" alt="cryptoss" src="https://github.com/user-attachments/assets/5c061456-9698-4e2d-89f4-4a08b104462a" />


# 👨‍💻 Author

- Ankit Verma
- B.Tech – Computer Science & Engineering
- Data Analytics Enthusiast

# ⭐ Why This Project Stands Out

✔ Real-time API integration
✔ Advanced DAX logic
✔ Professional financial dashboard design
✔ Interactive & user-friendly
✔ Portfolio-ready
