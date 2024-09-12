Project Goal: Predicting whether an article is fake or real news using vectorized text data

During this notebook I will construct a new TensorFlow dataset with cleaned (removed stopwords, etc) and vectorized text data from a sample of online articles. Next, I build neural network models that classify whether an article is fake or real news, with one model takig in just the article title, one taking in just the text, and one taking in both using a functional API. After tuning parameters and evaluating training data, I will compare the model performance to determine which data (text, title, or both) is optimal for detecting fake news. Finally, the accuracy will be tested on new unseen data to validate model reliability. 

Conclusions: The text and title model performed extremely well at around 98% training and testing accuracy, leading to the conclusion that having the combined text and title of an article results in the highest detection accuracy of fake news. 


_Completed as a part of UCLA 2024 Python with Applications Course_
