Project Goal: Predicting whether an article is fake or real news using vectorized text data

During this notebook I will construct a new TensorFlow dataset with cleaned (removed stopwords, etc) and vectorized text data from a sample of online articles. Next, I build neural network models that classify whether an article is fake or real news, with one model takig in just the article title, one taking in just the text, and one taking in both using a functional API. After tuning parameters, and evaluating training data plots I will compare the model performance to determine which data (text, title, or both) is optimal for detecting fake news.

_Completed as a part of UCLA 2024 Python with Applications Course_
