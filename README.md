### Stock price prediction using headline sentiment analysis

Attempt to identify a relationship between news headline sentiment and stock price movement. To then be able to predict stock price movement based on previous period’s sentiment scoring!

News headlines data available on: https://www.kaggle.com/datasets/miguelaenlle/massive-stock-news-analysis-db-for-nlpbacktests?select=analyst_ratings_processed.csv

Stock price data gathered from yFinance package.

Analysis on the following stocks:
- FB
- AAPL
- GOOGL
- TSLA
- NFLX
- MSFT

vaderSentiment and Hugging Face used for sentiment analysis.

Using the sentiments scores built Neural Network and XGBoost models. Also compared the models.
