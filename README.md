# Sentiment Analysis of Various Countries' Tweets for the US Presidential Elections 2020

This purpose of this project is to scrape tweets from Twitter using SNScrape, index the tweet corpus using Solr, classify the tweets using Bi-directional Encoder Representations from Transformers (BERT), and present classified tweets from each country for viewing in a web-based search engine. T

## Quickstart

1. To start solr:

```bash
    cd solr
    ./bin/solr start
```

2. To start the flask app:

```bash
    cd app
    pip install -r requirements.txt
    python app.py
```
