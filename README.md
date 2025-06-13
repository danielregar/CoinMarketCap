**📈 Crypto Market Analysis (Top 10 Coins)**

This project uses the **CoinMarketCap API** to pull real-time data on the top 10 cryptocurrencies and perform exploratory data analysis (EDA) using **Python, pandas, and seaborn**.

**⚠️ Note:**

- Data was pulled on 2025-06-13
- Analysis is limited to the top 10 coins, and findings are not generalizable to the entire crypto market.

**🔧 Technologies Used**

- Python (pandas, requests, matplotlib, seaborn)
- CoinMarketCap API
- Jupyter Notebook

**📦 Data Source**

Data was fetched from the CoinMarketCap API using the following parameters:
- start=1
- limit=10 (Top 10 coins)
- convert=USD

**📊 Visual Analysis & Key Findings**

**1. 📉 Price Change Percentage (1h, 24h, 30d)**

To better understand short-term and long-term market behavior, we visualized the percentage change in cryptocurrency prices over three time intervals using **seaborn.catplot():**

- **✅ 1h Change**

This graph captures the most immediate market movements. It helps identify sudden shifts or momentum in the last hour. For example, coins like **DodgeCoin** and **Cardano** showed notable gains in this snapshot.
  ![image](https://github.com/user-attachments/assets/b2a61949-70f2-46b0-a1e5-7e9b2f8efac7)

- **📅 24h Change**

This visualization reveals daily volatility, offering a quick view of how major assets moved over the past day. 
  ![image](https://github.com/user-attachments/assets/8189d71c-d855-4d7f-93f2-ab57b125cee0)

- **📆 30d Change**

This chart reflects longer-term trends. Cryptocurrencies like **Dogecoin** and **Cardano** had significant declines over the month.

![image](https://github.com/user-attachments/assets/6845e340-6e46-4ca1-bfa2-0aee860f7e4d)

🕒 **Note**: These observations are based on the top 10 cryptocurrencies by market cap as of **2025-06-13**. This is a limited snapshot and should **not be generalized to the entire market.**

**2. 🔁 Number of Market Pairs per Cryptocurrency**

This bar chart visualizes the number of market pairs available for each top 10 cryptocurrencies. A market pair refers to a trading pair listed on exchanges (e.g., BTC/USDT, ETH/USD), and this metric gives insight into each asset’s availability and integration in the market.

![image](https://github.com/user-attachments/assets/e7cb7216-b5a9-4184-8294-d1a125e5b033)

**🧐 Key Insights:**

- **Tether** (USDT) dominates significantly, with over **120,000 market pairs**, indicating its widespread use as a base trading currency across global exchanges.

- **USDC**, another stablecoin, also shows a strong presence, supporting its growing adoption as a trusted medium of exchange.

- Leading coins like **Bitcoin** and **Ethereum** have a solid number of pairs, showing their high demand and liquidity.

- Other altcoins such as **XRP, BNB, Solana,** and **Cardano** have fewer market pairs in comparison, yet still play important roles in the ecosystem.

📌 This helps to understand liquidity potential and trading flexibility. Cryptocurrencies with more market pairs tend to be more accessible, tradable, and integrated across multiple platforms.

**3. 🔍 Correlation Analysis: Market Pairs vs Market Cap**

This heatmap illustrates the **correlation coefficient** between the number of market pairs and the market capitalization of the top cryptocurrencies.
![image](https://github.com/user-attachments/assets/7ab0ff1c-40e7-404a-84b8-038cf8e51c41)

**📊 What Does It Show?**
- The correlation coefficient is **-0.02**, which indicates a very weak negative correlation between the number of market pairs and market capitalization.

- Market cap and market pair count operate independently in most cases, driven by different use cases — one reflecting value, the other accessibility.

**4. 💸 Top Cryptos by 24h Trading Volume**

This chart highlights the cryptocurrencies with the **highest 24-hour trading volume**, showing which coins are most actively traded across exchanges.
![image](https://github.com/user-attachments/assets/d0d9f9b2-f247-478e-8866-af8ffdf7fa68)

**📊 Key Observations:**
- **Tether (USDT)** leads by a wide margin, with over $100 billion in daily trading volume in the past 24h.

- **Bitcoin (BTC)** and **Ethereum (ETH)** follow, reflecting their strong market presence and popularity among traders.

- **USDC** also shows high volume, underscoring its role as an alternative stablecoin.

- Tokens like **XRP, Solana, and BNB** exhibit moderate volume.

**5. 🥇 Cryptocurrency Market Dominance**

This chart shows how much of the total crypto market capitalization is held by each major cryptocurrency. It gives a high-level view of which coins dominate the market.

![image](https://github.com/user-attachments/assets/07f70c93-1be4-4707-91df-1fa830306575)

**🧩 Key Takeaways:**
- **Bitcoin (BTC)** continues to reign supreme with over 60% market dominance, reaffirming its role as the foundation of the crypto ecosystem.

- **Ethereum (ETH)** is the clear runner-up, with approximately 15% dominance.

- Stablecoins like **Tether (USDT)** and **USDC** also feature in the top ranks.

- The remaining assets — **XRP, BNB, Solana,** etc. — contribute relatively small shares.
