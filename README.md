# Stock Trade Forecaster

TradeForecaster is a Python-based project for forecasting stock prices and analyzing financial news sentiment to assist in making informed trading decisions.

it makes use of a custom coded Recurrent Neural Network (RNN) trained on 5 years worth of data. This allows it to predict long terms and short term trends. On top of that, to handle extremely sudden changes, we added sentiment analysis from live news articles. The combination of these 2 things, allows it to hit over 90% accuracy in the trend of the stock 

## Features

- **Stock Data Fetching:** Retrieve historical and real-time stock data.
- **News Aggregation:** Fetch and process financial news articles.
- **Sentiment Analysis:** Analyze news sentiment to gauge market mood.
- **Stock Prediction Model:** Predict future stock prices using machine learning.
- **Top Performer Identification:** Identify top-performing stocks based on data and sentiment.


## Dependencies

- Python 3.12+
- pandas
- numpy
- scikit-learn
- requests
- beautifulsoup4
- nltk
- (Other dependencies as required by your code)

