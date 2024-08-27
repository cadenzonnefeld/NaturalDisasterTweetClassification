The goal of this project was to use natural language processing (NLP) techniques to understand the sentiment of tweets and determine if they are indicative of a natural disaster.

The approach I took began with a traditional NLP approach using TF-IDF Vectorizer and then iterated with Recursive Neural Networks (RNNs) that used both Gated Rectified Unit (GRU) layers and Long Short Term Memory (LSTM) layers to evaluate the data. The result was an RNN classifier that determined whether or not tweets were indicative of a natural disaster that earned an F1-Score of 80% on the test dataset.
