# 🚀 Digital Asset Insights – Crypto Intelligence Platform

## 📌 Overview
Digital Asset Insights is a real-time and historical cryptocurrency analytics platform built using **Microsoft Fabric** and **Power BI**. It enables users to monitor market behavior, analyze trends, and track live trading activity through a unified data pipeline.

---

## 🎯 Objective
Build a scalable crypto intelligence dashboard that:
- Aggregates real-time and historical data  
- Enables trend and volatility analysis  
- Supports modular and scalable data pipelines  
- Delivers insights via interactive dashboards  

---

## ⚠️ Problem Statement
The cryptocurrency market is:
- Decentralized  
- Highly volatile  
- Lacking unified analytics platforms  

This project addresses these challenges by creating a centralized, scalable solution using Microsoft Fabric.

---

## 🛠️ Tech Stack

- **Data Ingestion:** REST APIs (CoinGecko, Yahoo Finance)  
- **Streaming:** Microsoft Fabric Eventstream  
- **Processing:** Python, PySpark, Pandas  
- **Storage:** Lakehouse, Warehouse  
- **Transformation:** Power BI Dataflows (Power Query M)  
- **Visualization:** Power BI (Dark Theme Dashboard)  

---

## 📊 Cryptocurrencies Tracked
- Bitcoin (BTC)  
- Ethereum (ETH)  
- Dogecoin (DOGE)  
- XRP  
- Stellar (XLM)  
- Monero (XMR)  
- USD Coin (USDC)  
- TRON (TRX)  
- NEM (XEM)  
- Litecoin (LTC)  

---

## 🏗️ Architecture

### End-to-End Flow


### Design Principles
- Modular and reusable components  
- Scalable pipeline architecture  
- Supports both real-time and batch processing  

---

## 📁 Project Structure
crypto-insights-project/  
├── notebooks/ # Ingestion & transformation scripts  
├── dataflows/ # Power Query transformations  
├── dashboard/ # Power BI report (.pbix)  
├── documentation/ # README & architecture diagrams  
└── config/ # API keys, mappings  

---

## ⚙️ Setup Instructions

1. Create a Microsoft Fabric workspace  
2. Configure CoinGecko API (rate-limited, no key required)  
3. Run notebook:  


4. Save data to Lakehouse tables  
5. Build transformations using Dataflows  
6. Connect Warehouse to Power BI  
7. Load `.pbix` or create visuals  
8. Enable real-time refresh using Eventstream  

---

## 🧱 Data Model

| Table Name | Description |
|-----------|------------|
| crypto_price_history | Historical OHLC + volume |
| live_market_snapshot | Real-time price updates (30s interval) |
| crypto_name_symbol_map | Cryptocurrency metadata |

---

## 📈 Dashboard Features
- Real-time price tracking  
- Historical trend visualization  
- Volume and volatility analysis  
- Dark theme UI  
- Role-based filtering (planned)  

---

## ⚠️ Known Limitations
- API rate limits (CoinGecko)  
- Possible delays if Eventstream pauses  
- No sentiment analysis  
- Not optimized for mobile  

---

## 🔮 Future Enhancements
- Add more cryptocurrencies  
- Integrate sentiment analysis (NLP)  
- Implement role-based dashboards  
- Improve performance monitoring  
- Mobile optimization  

---

## 👥 Team
Microsoft Fabric Project  

- Yohannes S.  
- Emma I.  
- Racheal O.  
- Camilla O.  
- Fred W.  

---

## 💡 Key Highlights
- End-to-end data engineering pipeline  
- Real-time + batch processing architecture  
- Strong use of Microsoft Fabric ecosystem  
- Scalable and modular design  
- Business-focused data visualization  

---
4. Save data to Lakehouse tables  
5. Build transformations using Dataflows  
6. Connect Warehouse to Power BI  
7. Load `.pbix` or create visuals  
8. Enable real-time refresh using Eventstream  

---

## 🧱 Data Model

| Table Name | Description |
|-----------|------------|
| crypto_price_history | Historical OHLC + volume |
| live_market_snapshot | Real-time price updates (30s interval) |
| crypto_name_symbol_map | Cryptocurrency metadata |

---

## 📈 Dashboard Features
- Real-time price tracking  
- Historical trend visualization  
- Volume and volatility analysis  
- Dark theme UI  
- Role-based filtering (planned)  

---

## ⚠️ Known Limitations
- API rate limits (CoinGecko)  
- Possible delays if Eventstream pauses  
- No sentiment analysis  
- Not optimized for mobile  

---

## 🔮 Future Enhancements
- Add more cryptocurrencies  
- Integrate sentiment analysis (NLP)  
- Implement role-based dashboards  
- Improve performance monitoring  
- Mobile optimization  

---

## 👥 Team
Microsoft Fabric Project  

- Yohannes S.  
- Emma I.  
- Racheal O.  
- Camilla O.  
- Fred W.  

---

## 💡 Key Highlights
- End-to-end data engineering pipeline  
- Real-time + batch processing architecture  
- Strong use of Microsoft Fabric ecosystem  
- Scalable and modular design  
- Business-focused data visualization  

---

