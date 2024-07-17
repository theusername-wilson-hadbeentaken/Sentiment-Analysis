# Natural Language Processing - Sentiment Analysis on Multilingual Online Shopping Comments

## Description
This project performs sentiment analysis on multilingual online shopping comments using various natural language processing (NLP) techniques. 
The goal is to classify comments into different sentiment categories such as positive, negative, and neutral.

## Installation
To run this project, you need to install the required dependencies by referencing requirement.txt

# Table of Contents
1. Techniques and Methodology
2. Dataset
3. Results
4. Contributing
5. License

##1.Techniques and Methodology
In this project, several NLP techniques are used to preprocess and analyze the comments. These include:

Text Preprocessing: Tokenization, stopword removal, lemmatization, and normalization.
Vectorization: TF-IDF Vectorizer to convert text data into numerical format.
Machine Learning Models: Various classifiers such as Multinomial Naive Bayes, Support Vector Machine (SVM), Logistic Regression, and Random Forest are used to predict the sentiment.
Deep Learning: A Sequential model with Embedding and LSTM layers is used for sentiment analysis.

Each technique is chosen for its ability to handle specific aspects of text data. For instance, TF-IDF Vectorizer helps in weighting the importance of words, while LSTM is effective in capturing sequential dependencies in text.


##2.Dataset
The example dataset is included in the data directory. Make sure to place any necessary datasets there before running the notebook. The dataset contains comments in multiple languages along with their sentiment labels.
The dataset in this project contains comments for shoe online shop with Bilingual language (Malay and English)

##3.Results
The project evaluates the performance of different models using accuracy and other relevant metrics. The results show the effectiveness of each model in predicting sentiments.

##4.Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request. We welcome improvements and fixes.

##5.License
This project is licensed under the MIT License - see the LICENSE file for details.