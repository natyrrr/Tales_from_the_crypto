 # Tales From The Crypto...


![Alt Text](https://media.giphy.com/media/1DQWAuidHJH8Y/giphy.gif)



## Background
There's been a lot of hype in the news lately about cryptocurrency, so I want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.
I will apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. I will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

## Resources

1. *Vader Sentiment Analysis*
2. *Python*
3. *NLK library*
4. *NER*
5. *SpaCY library*
6. *News API Client*
7. *Pandas*

### Complete the following tasks:

Sentiment Analysis
Natural Language Processing
Named Entity Recognition


## Procedure

## Sentiment Analysis:

I will be using the newsapi to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.
I will use descriptive statistics to answer the following questions:

Which coin had the highest mean positive score?
Which coin had the highest negative score?
Which coin had the highest positive score?


## Natural Language Processing:

In this section, I will use NLTK and Python to tokenize the text for each coin. 

1. I will look at the ngrams and word frequency for each coin.
2. Use NLTK to produce the ngrams for N = 2.
3. List the top 10 words for each coin.
4. Generate word clouds for each coin to summarize the news for each coin.

### Findings

Q: Which coin had the highest mean positive score?

### A: Bitcoin had the highest mean positive score with .068.

Q: Which coin had the highest compound score?

### A: Bitcoin also had the highest compound score with a max of 92%.

Q. Which coin had the highest positive score?

### A: Bitcoin had the highest positive score with .267.

## Bitcoin Sentiment Score

![Alt Text](https://github.com/natyrrr/Tales_from_the_crypto/blob/master/Screen%20Shot%202020-09-17%20at%2011.59.52%20AM.png)

## Ethereum Sentiment Score
![Alt Text](https://github.com/natyrrr/Tales_from_the_crypto/blob/master/Screen%20Shot%202020-09-17%20at%2012.00.02%20PM.png)
