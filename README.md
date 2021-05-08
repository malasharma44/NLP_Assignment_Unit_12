# NLP_Assignment_Unit_12 by Mala Sharma

# Unit 12—Tales from the Crypto: NLP analysis, Bitcoin and Ethereum

## Background

For this assignment I have used natural language processing to analyze sentiment in news articles featuring Bitcoin and Ethereum. Using fundamental NLP techniques I have looked at other factors involved with the coin prices such as the words and phrases used frequently, as well as the names of the entities mentioned in the articles.

1. [Sentiment Analysis](#1---Sentiment-Analysis)
2. [Natural Language Processing](#2---Natural-Language-Processing)
3. [Named Entity Recognition](#3---Named-Entity-Recognition)

---

## Files

[Starter Notebook](Starter_Code/crypto_sentiment.ipynb)

----

### 1 - Sentiment Analysis

I utilized the [newsapi](https://newsapi.org/) in order to access news articles for Bitcoin & Ethereum. I have created a DataFrame of sentiment scores for both Ethereum and Bitcoin.

> Q. Which coin had the highest mean positive score?
> A. Bitcoin had the marginally higher mean positive score.

> Q. Which coin had the highest negative score?
> A. Bitcoin and Ethereum had very similiar negative mean scores, however Ethereum had a slightly higher negative max score.
> 
> Q. Which coin had the highest positive score?
> A. Ethereum had the higher positive max score.
> 
> Q. Which coin had the highest compound score?
> A. Bitcoin had the higher compound mean score, but Ethereum had the higher compound max score.

---

### 2 - Natural Language Processing

NLTK & Python were used to tokenize text, find n-gram counts, and create word clouds for both coins. 

#### Tokenize

For tokenization, the process has been to:

1. Lowercase each word.
2. Remove punctuation.
3. Remove stop words.

#### N-grams

I analyzed the ngrams & word frequency for both Ethereum & Bitcoin.
The process involved the following:

1. Use NLTK to produce the ngrams for N = 2.
2. List the top 10 words for each coin.

#### Word Clouds

For visual representation of the findings, I generated word clouds for both coins to summarize the news accordingly.

---

### 3 - Named Entity Recognition

I created a named entity recognition model for both coins using SpaCy.

---

## Resources

[Vader Sentiment Analysis](http://www.nltk.org/howto/sentiment.html)
