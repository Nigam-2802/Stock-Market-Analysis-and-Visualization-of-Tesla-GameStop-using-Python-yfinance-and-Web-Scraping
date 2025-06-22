# Stock-Market-Analysis-and-Visualization-of-Tesla-GameStop-using-Python-yfinance-and-Web-Scraping

🔍 Overview
This project explores the historical stock performance and revenue trends of Tesla (TSLA) and GameStop (GME) using:

Real-time stock data from the yfinance API

Historical revenue data scraped from Macrotrends

Interactive visualizations via plotly

📦 Tools & Libraries Used
Python 3.x

yfinance – to fetch stock market data

pandas – for data manipulation

plotly – for interactive plotting

BeautifulSoup – for web scraping revenue data

requests – for making web requests

📊 Features
Fetch and visualize historical stock prices for Tesla and GameStop

Web scrape quarterly revenue data from Macrotrends

Clean and preprocess data for analysis

Generate interactive line charts for:

Stock Price trends

Revenue trends

Display structured outputs using .head() and .tail() for insights

🔧 Setup Instructions
Clone the Repository (if applicable):

bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install Required Packages:

bash
Copy
Edit
pip install yfinance pandas plotly beautifulsoup4 lxml requests
Run the Jupyter Notebook or Python script:

Ensure you're using an environment that supports Plotly (Jupyter Notebook or VSCode).

Recommended renderer: 'iframe' or 'notebook'

📂 File Structure
bash
Copy
Edit
├── Stock-Market-Analysis.ipynb       # Main notebook or script
├── tesla_stock_graph.html            # Optional: exported Plotly chart
├── README.md                         # This file
📸 Visuals (Optional)
Include screenshots or embedded plots from the notebook showing:

Tesla stock price over time

GameStop stock price over time

Tesla & GameStop revenue trends

✅ Learning Objectives
Understand how to work with real-world financial APIs (yfinance)

Learn how to web scrape structured financial data

Build interactive data visualizations using Plotly

Apply data cleaning techniques on time-series financial datasets

🚀 Future Improvements
Add moving averages or technical indicators

Overlay stock and revenue plots in one chart

Create a dashboard using Dash or Streamlit

Add sentiment analysis using Twitter or Reddit data

📚 References
Yahoo Finance via yfinance

Macrotrends Financial Data

Plotly Documentation
