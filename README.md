# Deep Learning based Sentiment Analysis
Sentiment analysis is contextual mining of text which identifies and extracts subjective information in source material, and helps a business to understand the social sentiment of their brand, product or service while monitoring online conversations. In this assignment, you are to implement a sequence-based text classification model to predict the number of positive and negative reviews based on sentiments.

## Dataset
The dataset used here is from https://ai.stanford.edu/~amaas/data/sentiment/

## Below are some techniques covered and demonstrated in the Jupyter Notebook
* Data preprocessing - using nltk and regex patterns
* CBOW Word2Vec modelling
* Character based Word2Vec modelling
* Bi-LSTM based sequence model
* PyTorch
* Visualisation using matplotlib
* Hyperparameter Optimization

## Objective
The main goal was to try and demonstrate NLP, deep learning methods via PyTorch and hence less focus was given to attain more accuracy.

## Improvements to be added
I believe the below improvements might improve the model.
* Check if readily available genism Word2Vec embeddings (https://radimrehurek.com/gensim/downloader.html) are giving better results
* Use pre-trained BERT to get contextual embedding of the sentences
* Extract characted based Word2Vec by concatenating the values from hidden states of the LSTM network
