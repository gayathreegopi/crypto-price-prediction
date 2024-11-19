# Project Title: Crypto Price Prediction Using Sentiment and Financial Data

## Project Overview
This project involves developing a predictive model for cryptocurrency prices, specifically focusing on Bitcoin. The crypto market is known for its high volatility, influenced by a wide range of factors, from macroeconomic events to investor sentiment. By leveraging both traditional financial metrics and real-time sentiment analysis from social media platforms like Reddit, this project aims to offer a comprehensive approach to forecasting price movements. We built models using time series data and integrated community-driven insights to capture both market trends and the social dynamics that impact cryptocurrency prices.

## Contributions
- Created a recurrent neural network (RNN) model using **LSTM** to handle time series data from yfinance and sentiment metrics from Reddit, enriching predictions with social sentiment analysis.
- Developed both regression and classification models to predict Bitcoin price trends, optimizing model performance with techniques such as hyperparameter tuning.

## Important Findings
1. **Impact of Community Sentiment**: Integrating Reddit data provided valuable insights into market sentiment, which often drives short-term price fluctuations in the crypto market.
2. **Model Performance**: The LSTM model, tuned over several hyperparameters (e.g., learning rate, epochs, dropout rate), outperformed baseline models, demonstrating the importance of capturing both time-based and sentiment features.
3. **Hyperparameter Optimization**: Adjusting parameters like the number of hidden layers and batch size significantly improved the model's robustness and accuracy.
4. **Use of Multiple Datasets**: Comparing models trained on different datasets (Bitcoin-only, multi-crypto, and ETFs) revealed how various financial contexts impact predictive performance.
5. **Market Insights**: This dual-input approach provided a nuanced understanding of how investor sentiment correlates with actual price movements, offering potential value for trading and investment strategies.

## Technologies Used
- **Programming Languages**: Python
- **Libraries and Tools**: yfinance, spaCy, scikit-learn, LSTM from Keras, Reddit API
- **Data Sources**: yfinance for historical Bitcoin prices and Reddit for community sentiment analysis

## How to Run the Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/crypto-price-prediction
  ```
2. **Install Dependencies**:
  ```bash
  pip install -r requirements.txt
  ```
3. **Data Collection**:
Use yfinance to pull historical Bitcoin data and Reddit API to scrape relevant posts from subreddits like r/Bitcoin and r/CryptoCurrency.
4. **Train the Models**:
Run the provided Python scripts to train the LSTM model and test regression and classification models.
6. **Analyze Results**:
Review model performance metrics and visualizations to understand how financial metrics and sentiment influence price predictions.
7. **Future Applications**:
* Real-Time Market Monitoring: Implement a real-time monitoring system to adjust trading strategies based on evolving sentiment and market conditions.
* Expanded Sentiment Analysis: Incorporate sentiment from other social media platforms, such as Twitter, for a broader view of market sentiment.
* Algorithmic Trading: Develop an algorithmic trading bot that leverages these models to make automated investment decisions in real time.

## Contact
For questions or further information, please contact:
* Email: gayathreegopi@utexas.edu
* LinkedIn: linkedin.com/in/gayathreegopi
