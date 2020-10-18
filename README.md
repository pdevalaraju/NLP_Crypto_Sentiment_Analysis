# Crypto Currencies Sentiment Analysis

![Stock Sentiment](Resources/sentimental.jpeg)

## Background

There's been a lot of hype in the news lately about cryptocurrency, so we will analyse the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

In crypto_sentiment.ipynb Notebook, we will apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. We will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

The following tasks are incorporated in the notebook:

1. [Sentiment Analysis](#Sentiment-Analysis)
2. [Natural Language Processing](#Natural-Language-Processing)
3. [Named Entity Recognition](#Named-Entity-Recognition)

---

### Sentiment Analysis

We will use the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin and answer the following questions:

> Which coin had the highest mean positive score?
>
> Which coin had the highest negative score?
>
> Which coin had the highest positive score?

### Natural Language Processing

In this section, We will tokenize the news text for each coin using NLTK and Python to tokenize the text for each coin. We cleanse the data and 
before creating ngrams and word frequency for each coin

Finally, We generate word clouds for each coin to summarize the news for each coin.

![btc_word_cloud.png](Resources/btc_word_cloud.png)

![eth_word_cloud.png](Resources/eth_word_cloud.png)

### Named Entity Recognition

In this section, We will build a named entity recognition model for both coins and visualize the tags using SpaCy.

![btc_ner.png](Resources/btc_ner.png)

![eth_ner.png](Resources/eth_ner.png)

---
