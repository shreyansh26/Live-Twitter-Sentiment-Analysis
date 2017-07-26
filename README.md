Live Twitter Sentiment Analysis
===============================

I created a module called **sentiment_mod** using NLTK. The classifier used for sentiment analysis is a custom classifier based on voting involving various algorithms including - 

* Original Naive Bayes Classifier of NLTK
* Multinomial Naive Bayes
* Stochastic Gradient Descent (SGD)
* Bernoulli Naive Bayes

The module can do sentiment analysis on any piece of text and describe it as positive(pos) or negative(neg).

The file **live_twitter_sentiment.py** is used to do twitter analysis on live twitter feed on ay topic.  
The file **graphing_live_twitter.py** plots a live graph of the sentiment value of tweets.

The pickle files can also be made by running the **sentiment_module_1.py**.
