# Fake News Detection using Machine Learning Techniques
# Overview
This project implements a machine learning framework for detecting fake news, leveraging text preprocessing, feature extraction, and various classification algorithms. The goal is to differentiate real news from fake news articles using a labeled dataset and machine learning models, providing an automated, scalable solution for combating misinformation.

# Introduction
The proliferation of fake news poses risks to public trust and safety. Manual fact-checking methods are not sufficient due to the volume of misinformation. This project explores machine learning techniques to identify fake news based on patterns in the language and structure of articles. The models used include Logistic Regression, Naive Bayes, Support Vector Machine, Random Forest, Gradient Boosting, and others, evaluated on accuracy, precision, recall, and F1-score.

# Objectives
Develop a machine learning framework for fake news detection.
Compare different machine learning algorithms to identify the most effective model.
Analyze and optimize models based on key performance metrics for practical deployment.
Dataset
The dataset includes pre-labeled articles categorized as "True" or "Fake." Sources include trusted news agencies for real news and identified fake news sources. Data preprocessing steps, such as text cleaning, tokenization, and vectorization, transform the raw text data for analysis.

# Methodology
The workflow includes:

Data Preprocessing: Cleaning, tokenizing, stopword removal, lemmatization, and TF-IDF vectorization.
Feature Extraction: Using TF-IDF and exploring alternative vectorizations like Count Vectorization and embeddings.
Model Selection: Training and evaluating models including:
Logistic Regression
Naive Bayes
Support Vector Machine
Random Forest
Gradient Boosting
Model Evaluation: Using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.


Results
The Gradient Boosting model achieved the best performance, with an accuracy of 92% and an F1-score of 91%, outperforming other models in identifying fake news. The detailed results are presented in the report for comparison among models.

# Conclusion and Future Work
This project demonstrates the potential of machine learning in automated fake news detection, with Gradient Boosting proving to be effective. Future work may include deep learning approaches and integrating social media metrics to enhance accuracy and adaptability.

# References
Key references include works on fake news detection techniques, TF-IDF vectorization, machine learning models, and ensemble methods. Full references are available in the project report.
