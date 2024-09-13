# Introduction
The primary goal of this repository is to scrape news articles related to Bitcoin from trusted sources like **Binance** and **Yahoo Finance** to provide data for sentiment analysis. Analyzing the sentiment of these news articles could ''potentially'' help predict the future price movements of Bitcoin (BTC).

## Project Overview
- **Binance Scraper:** Collects news articles from Binance, a major cryptocurrency exchange known for its extensive coverage of Bitcoin and other digital assets.
- **Yahoo Finance Scraper:** Gathers relevant news from Yahoo Finance, a reputable financial news platform providing a broad range of financial and investment information.

<br>

# Getting started
To set up the project, follow these steps:

## Clone the repository
   ```bash
   git clone https://github.com/Imad-Allal/Bitcoin-News-Scraper
   cd Bitcoin-News-Scraper
   ``` 
## Installation
1. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

2. **Download and install the ChromeDriver:**

    Ensure you have ChromeDriver installed and accessible in your system PATH. The latest versions of ChromeDriver can be downloaded from [here](https://googlechromelabs.github.io/chrome-for-testing/).

## Usage
Scrapers can be found under the `notebooks` folder. For better management, we recommend using Jupyter Notebooks to run them.

<br>

# Disclaimer
While the sources used in this project are reliable, it's important to note that predicting Bitcoin's price is inherently challenging due to its volatile nature and the complex factors influencing its market. This project aims to provide short descriptions of Bitcoin news articles for sentiment analysis, sourced from two trusted platforms. However, it does not guarantee the reliability of those articles.