# Vityarthi_Project_AI-ML
Project Title

Sentiment Analysis of Social Media Comments Using Machine Learning

1. Introduction

Sentiment Analysis is a Natural Language Processing (NLP) technique used to determine whether a piece of text expresses a Positive, Negative, or Neutral sentiment.
This project builds a Machine Learning model that analyzes social media comments (Twitter/YouTube) and predicts their sentiment automatically.

This project uses:

Text preprocessing
TF-IDF feature extraction
Naive Bayes Machine Learning algorithm
2. Objective

The objective of this project is to:

Analyze social media comments
Classify comments into Positive, Negative, and Neutral
Train a Machine Learning model for automatic sentiment prediction
3. Technologies Used
Tool	                                                          Purpose
Python	                                                      Programming
Pandas	                                                      Data handling
NLTK	                                                        Text preprocessing
Scikit-learn	                                                Machine Learning
TF-IDF	                                                      Feature extraction
Naive Bayes	                                                  Classification algorithm
4. Dataset

The dataset is stored in a CSV file with two columns:

Column	Description
comment	Social media comment
sentiment	Positive / Negative / Neutral

Example:

comment	sentiment
I love this video	Positive
This is terrible	Negative
Video is okay	Neutral

Dataset contains 500 comments
5. Project Workflow

The project follows these steps:
Data Collection
       ↓
Data Preprocessing
       ↓
Feature Extraction (TF-IDF)
       ↓
Train Machine Learning Model (Naive Bayes)
       ↓
Model Testing
       ↓
Accuracy & Classification Report
       ↓
Prediction of New Comment
6. Text Preprocessing

Text preprocessing is performed to clean the text data.

Steps:

Convert text to lowercase
Remove punctuation
Remove stopwords (is, the, a, an, etc.)
Tokenization (split words)
Stemming/Lemmatization

Example:
"This video is very helpful!!!"
→ "video helpful"
7. Feature Extraction (TF-IDF)

TF-IDF converts text into numerical form so that Machine Learning algorithms can understand it.

TF-IDF stands for:

TF = Term Frequency
IDF = Inverse Document Frequency

It gives importance to important words and reduces importance of common words.
8. Machine Learning Algorithm Used

Multinomial Naive Bayes Algorithm

Why Naive Bayes?

Works very well for text classification
Fast and efficient
Based on probability
9. Model Evaluation (Explanation of Output Report)

After training the model, we get the following evaluation metrics:

Metric	Meaning
Accuracy	Overall correct predictions
Precision	Out of predicted, how many were correct
Recall	Out of actual, how many were correctly predicted
F1-score	Balance between Precision and Recall
Support	Number of actual samples
Example Result:
Sentiment	Precision	Recall	F1-score	Support
Negative	0.89	1.00	0.94	17
Neutral	1.00	0.33	0.50	3
Positive	1.00	1.00	1.00	20

Accuracy = 0.95 (95%)

Interpretation:
The model predicts Positive and Negative sentiments very well.
The Neutral sentiment recall is low because the dataset contains fewer Neutral samples.
The model performance can be improved by increasing Neutral data.
12. Conclusion

This project successfully performs sentiment analysis using Machine Learning.
The Naive Bayes classifier achieved high accuracy in classifying comments into Positive, Negative, and Neutral categories.
The system can be improved further by using a larger dataset and advanced algorithms like SVM or Deep Learning.

13. Future Scope
Use Deep Learning (LSTM, RNN)
Real-time Twitter sentiment analysis
GUI interface
Web application deployment

Name: Piyush Kumar Dash
Course: Fundamentals in AI & ML
Project: Sentiment Analysis
