# Spam Email Classifier

Welcome to the Spam Email Classifier project! This program utilizes machine learning algorithms to classify emails as spam or not spam. The project was developed during the Compozent internship in Machine Learning and Artificial Intelligence.

## Table of Contents

1. [Datasets Used](#datasets-used)
2. [Algorithms Used](#algorithms-used)

## Datasets Used

### 1. 2007 TREC Public Spam Corpus
   - **File Name:** email_text.csv
   - **Original Link:** [TREC 2007 Corpus](https://plg.uwaterloo.ca/~gvcormac/treccorpus07/)
   - **Preprocessed Download Link:** [Kaggle Dataset](https://www.kaggle.com/datasets/bayes2003/emails-for-spam-or-ham-classification-trec-2007)

### 2. Enron-Spam Dataset
   - **File Name:** enron_spam_data.csv
   - **Original Link:** [Enron-Spam Dataset](https://www2.aueb.gr/users/ion/data/enron-spam/)
   - **Preprocessed Download Link:** [GitHub Repository](https://github.com/MWiechmann/enron_spam_data/)

## Algorithms Used

### 1. TF-IDF Vectorizer
   - **Description:** TF-IDF (Term Frequency Inverse Document Frequency) is a widely used algorithm for transforming text into a numerical representation. It helps in fitting machine learning algorithms for prediction.
   - **Advantages:** 
     - Addresses the bias introduced by counting word frequency alone (as in CountVectorizer).
     - Assigns higher importance to unique and indicative words, making it effective for spam classification.
   - **Application:** Preferred for spam email classification due to its ability to capture the relative importance of words.

### 2. Support Vector Machine (SVM)
   - **Description:** SVM is a supervised machine learning algorithm used for both classification and regression. It excels in learning complex patterns and performs well on linear and non-linear problems.
   - **Advantages:**
     - Achieves higher classification accuracy.
     - Robust to noise and outliers in the data.
   - **Application:** Widely used in spam filtering to distinguish between legitimate emails and spam messages.

Feel free to explore the datasets and algorithms to gain insights into the development of this spam email classifier. If you have any questions or suggestions, please don't hesitate to reach out!
