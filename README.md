# AI-Powered-Crypto-Market-Analyzer
The AI-Powered Crypto Market Analyzer is an end-to-end automation pipeline that combines real-time cryptocurrency price data, AI-driven sentiment analysis,  predictive modeling to deliver actionable market intelligence.   data pipeline engineering,  AI forecasting for the financial domain using free and open-source 



Features

📊 Real-Time Data: Fetches live Bitcoin (BTC) price data from the CoinGecko API.

🤖 AI Sentiment Analysis: Uses Hugging Face NLP models to analyze sentiment from crypto news.

📈 Price Forecasting: Predicts short-term BTC prices using Facebook Prophet.

🛠 Data Pipeline: Structured ingestion and storage via Python, Pandas, and SQLite.

🎨 Visualization: Interactive insights with Matplotlib, Seaborn, and WordCloud.

📑 Automated Reporting: Generates PDF reports (FPDF) combining charts, forecasts, and sentiment insights.

⚡ Multi-Stage Workflow: AI validation layers ensure accuracy and reliability.


🛠 Tech Stack

Languages: Python

AI/ML: Hugging Face Transformers, Prophet

Data: Pandas, SQLite, CoinGecko API

Visualization: Matplotlib, Seaborn, WordCloud

Automation & Reporting: FPDF, Prefect (optional for orchestration)

📂 Project Structure
AI-Crypto-Market-Analyzer/
│── crypto_analyzer.ipynb    # Main Colab notebook
│── btc_prices.csv           # BTC price dataset (generated)
│── crypto.db                # SQLite database
│── AI_Crypto_Report.pdf     # Final generated report
│── README.md                # Project documentation

🚀 How to Run on Google Colab

Open the notebook in Google Colab.

Install dependencies:

!pip install requests transformers wordcloud fpdf matplotlib seaborn prophet


Run the cells step by step to:

Fetch BTC price data

Perform sentiment analysis

Generate visualizations

Forecast BTC prices

Export AI_Crypto_Report.pdf

📊 Sample Visuals

BTC Price Trend (30 Days)
📈

Sentiment Analysis of News
📊

Crypto News Word Cloud
☁️

BTC Price Forecast (Next 7 Days)
🔮

📑 Example Report

The pipeline automatically generates a PDF report containing:

Market overview

BTC price trends

Sentiment distribution

WordCloud visualization

7-day BTC forecast

📌 Report Name: AI_Crypto_Report.pdf
