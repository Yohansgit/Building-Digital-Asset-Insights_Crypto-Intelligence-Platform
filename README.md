## Digital Asset Insights – Crypto Intelligence Platform

# Digital Asset Insights

# Objective
To build a real-time and historical cryptocurrency intelligence dashboard using Microsoft Fabric and Power BI.  This evaluation helps decision-makers analyze price trends, trade movement and market capitalization using live and curated data pipelines.

# Problem Statement
The crypto market is decentralized, volatile, and lacks consolidated analytical tools for real-time tracking. Our project aims to bridge this gap by building a unified data solution using Microsoft Fabric.

# Tools & Technologies
Data Ingestion: REST APIs (CoinGecko, Yahoo Finance)
Real-time Streaming: Microsoft Fabric Eventstream
Data Processing: Notebooks (Python, PySpark, Pandas)
Storage: Lakehouse, Warehouse
Transformation: Dataflows
Visualization: Power BI (dark theme)

# Cryptocurrencies Tracked
Bitcoin (BTC)
Ethereum (ETH)
Dogecoin (DOGE)
XRP
Stellar (XLM)
Monero (XMR)
USD Coin (USDC)
TRON (TRX)
NEM (XEM)
Litecoin (LTC)

# Project Architecture
End-to-End Flow:
API / Eventstream → Notebook (transformation) → Lakehouse → Dataflow → Warehouse → Power BI
 
Each component is modular and reusable, allowing the pipeline to scale horizontally (more coins, new data sources) and vertically (role-based reporting, alerts).

# Folder / File Structure  
crypto-insights-project/
├── notebooks/                # Ingestion & transformation scripts  
├── dataflows/               # Power Query M transformations   
├── dashboard/               # Power BI report (.pbix)   
├── documentation/           # README, architecture diagram   
└── config/                  # API keys, table mappings   

# Setup Instructions
Fabric workspace set up
Configure CoinGecko API (no key needed, but rate-limited)
Launch notebook: CryptoIngest.ipynb to fetch data
Save ingested data to Lakehouse tables
Use Dataflow to transform tables for reporting
Link Fabric Warehouse to Power BI
Load .pbix file or create visuals from Warehouse tables
Enable real-time refresh using Eventstream
Sample Tables Created
crypto_price_history – Historical OHLC + volume data
live_market_snapshot – Streaming price + volume every 30s
crypto_name_symbol_map – Metadata about coins

# Dashboard Overview
Real-time price feed
Historical trend charts
Volume spikes & volatility analysis
Dark theme layout for better focus
Ready for role-based slicing (e.g., by user type)

# Known Limitations
CoinGecko API has rate limits
Data may be delayed if Eventstream is paused
Sentiment data is not yet integrated
Dashboard not yet mobile-optimized

# Future Enhancements
Add more coins for testing scalability
Implement role-based dashboards
Improve performance monitoring and refresh scheduling

# Team and credits
Microsoft Fabric Project
Developed by: 
Emma Imujaru
Racheal Otieno	 
Yohannes Setotaw	
Camilla Odika  
Fred Willis Ochako


