## Overview:

This project focuses on classifying Twitter messages as positive, negative, or neutral based on their content. The primary goal is to develop a machine learning model that accurately identifies the sentiment of a given tweet. The project employs Python programming language and various popular libraries to preprocess the data, train the model, and evaluate its performance.

## Dependencies:

* Python 3.7+
* Pandas
* Numpy
* Scikit-learn
* TextBlob
* Requests

To install the required libraries, run the following command:

$ pip install pandas numpy scikit-learn textblob requests

## Dataset:

The dataset used in this project is the "Sentiment140" dataset, which consists of 1.6 million tweets labeled as positive, negative, or neutral. The dataset can be downloaded directly using the provided URL:

* Sentiment140 Dataset: http://cs.stanford.edu/people/alecmgo/trainingandtestdata.zip

In this script, the download_and_extract_data() function downloads and extracts the Sentiment140 dataset using the provided URL. The load_data() function reads the data and creates a pandas DataFrame. The preprocess_tweet() function applies basic preprocessing using TextBlob. The main() function preprocesses the data using the TfidfVectorizer, splits it into training and testing sets, trains a LogisticRegression classifier, and evaluates its performance using classification report and accuracy score.