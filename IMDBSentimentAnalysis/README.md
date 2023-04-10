## Overview:

This project focuses on classifying movie reviews as positive or negative based on their content. The primary goal is to develop a machine learning model that accurately identifies the sentiment of a given movie review. The project employs Python programming language and various popular libraries to preprocess the data, train the model, and evaluate its performance.

## Dependencies:

* Python 3.7+
* Pandas
* Numpy
* Scikit-learn
* TensorFlow
* Keras
* Requests

To install the required libraries, run the following command:

$ pip install pandas numpy scikit-learn tensorflow keras requests

## Dataset:

The dataset used in this project is the "IMDB Dataset of 50K Movie Reviews", which consists of 50,000 movie reviews labeled as positive or negative. The dataset can be downloaded directly using the provided URL:

* IMDB Movie Reviews Dataset: https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz

In this script, the download_and_extract_data() function downloads and extracts the IMDB movie reviews dataset using the provided URL. The read_imdb_data() function reads the data and creates a pandas DataFrame. The main() function preprocesses the data using the TfidfVectorizer, splits it into training and testing sets, trains a LinearSVC classifier, and evaluates its performance using classification report and accuracy score.