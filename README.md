# Movie_Sentimental-Analysis 📝🎥📊

In this project, I will implement several sentiment analysis models in Python using the IMDB movie review dataset. The goal is to predict whether a given review is positive or negative.

To begin, I will preprocess the data by tokenizing the text, removing stop words, converting the text to lowercase, and performing lemmatization. The dataset will then be partitioned into training and test sets with an 80-20 split, ensuring that the target variable follows the same distribution in both sets.

For lexicon-based sentiment analysis, I will utilize the VADER Sentiment Analysis tool and evaluate the model's performance using accuracy, precision, recall, and F1 score.

Next, I will train a Naive Bayes model for sentiment analysis, selecting the number of features and choosing the appropriate method (binary, count, or tf-idf) to generate feature values. I will evaluate the model's performance using various configurations, documenting and reporting their performance.

Similarly, a Support Vector Machines model will be trained for sentiment analysis, adjusting the number of features and selecting the method for generating feature values. The model's performance will be evaluated with different configurations, and the best-performing configuration will be documented.

In the deep learning phase, I will preprocess the movie reviews into sequences of equal length for training a Bidirectional LSTM model. Various configurations will be tested, such as locally trained embeddings versus pre-trained embeddings, different numbers of layers, and hidden layer sizes. The model's performance will be assessed using accuracy, precision, recall, and F1 score, and the best-performing configuration will be recorded.

In conclusion, this project explores different models for sentiment classification. Through experimentation and evaluation, we aim to identify the most effective model for predicting sentiment in movie reviews.
