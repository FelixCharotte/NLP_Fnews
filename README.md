# Sentiment Analysis-Based Financial News NLP Project 📰📈

## Project Overview
This project focuses on **sentiment analysis of financial news** to predict investment decisions in the stock and cryptocurrency markets. By combining financial news sentiment with Bitcoin price trends, this project assesses potential market movements using cutting-edge NLP techniques and financial data.

---

## Key Features

### 1. Data Acquisition  
- **Financial News**: Scraped financial news using Hugging Face tools.  
- **Bitcoin Prices**: Retrieved historical price data using the Binance API.  

### 2. Data Preparation  
- Cleaned and reformatted financial news and Bitcoin price data.  
- Categorized price movements into four segments based on quartiles:  
  - **Extreme Bearish**  
  - **Bearish**  
  - **Bullish**  
  - **Extreme Bullish**  

### 3. Model Fine-Tuning  
- Leveraged **LLaMA 3** for fine-tuning on the curated dataset to analyze sentiment and its relationship with price movements.

### 4. Performance Backtesting  
- Validated the fine-tuned model using real market performance data from the Binance API to ensure accuracy and robustness.

---

## How It Works
1. **Sentiment Analysis**:  
   Extracts sentiment from financial news headlines and articles.  
2. **Categorical Price Movements**:  
   Maps sentiment scores to quartiles to predict price movements:
   - Extreme Bearish, Bearish, Bullish, and Extreme Bullish.  
3. **Model Training and Inference**:  
   Trains the fine-tuned LLaMA 3 model on the prepared dataset and uses it for inference on market trends.  

---

## Tools and Libraries
- **Data Scraping**: Hugging Face Transformers, BeautifulSoup  
- **Data Integration**: Pandas, NumPy  
- **Model Training**: PyTorch, LLaMA 3  
- **Data API**: Binance API  
