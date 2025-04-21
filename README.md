📧 Spam-Ham Message Classifier (NLP Project)
This project is a Natural Language Processing (NLP) based Spam Detection System that classifies text messages as either Spam or Ham (Not Spam) using the TF-IDF vectorizer and a Naive Bayes classifier.

🚀 Project Overview
Spam detection is a common task in email and SMS filtering. This project demonstrates a simple and effective approach to spam classification using:
1) TF-IDF (Term Frequency–Inverse Document Frequency) for feature extraction.
2) Multinomial Naive Bayes for classification.

📂 Dataset
The dataset used is the SMS Spam Collection dataset from Kaggle.
It contains 5,572 labeled SMS messages as either:
1) spam – Unwanted, commercial messages
2) ham – Legitimate, personal or useful messages

🛠️ Tech Stack
1) Python 
2) Pandas
3) NumPy
4) Scikit-learn
5) NLTK (for preprocessing)
6) Jupyter Notebook / Python script

📊 Workflow
Data Preprocessing
Lowercasing
Removing punctuation
Removing stopwords
Stemming using NLTK
Feature Extraction
Using TF-IDF Vectorizer to convert text data into numerical features.
Model Training
Multinomial Naive Bayes Classifier
Evaluation
Accuracy, Precision, Recall, F1 Score
Confusion Matrix
