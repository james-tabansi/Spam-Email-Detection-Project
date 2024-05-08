# Spam-Email-Detection-Project

## **Problem Statement:**
The prevalence of spam emails poses a significant challenge for individuals and organizations, leading to a cluttered inbox, potential security threats, and loss of productivity. To address this issue, our study aims to develop a robust spam email classifier capable of distinguishing between legitimate (ham) and spam emails effectively.

## **Objective:**
The objective of this study is to develop a spam email classifier by comparing the performances of various machine learning and deep learning models. Specifically, we consider models such as decision trees, gradient boosting, recurrent neural networks (RNNs), long short-term memory (LSTM) networks, BERT, and FLAN-T5. We evaluated the performance of these models using metrics such as recall and F1 scores to assess their effectiveness in classifying emails as spam or ham.

## **Methodology:**
Our study employs a systematic approach to spam mail classification, encompassing several key modules within the workflow. The architecture of our methodology consists of the following components:

1. **Data Collection:**
   Obtained a dataset of emails, comprising both spam and ham examples from Kaggle platform, to train and evaluate the classification models.

2. **Text Preprocessing:**
   Preprocessing the email text data to remove noise, such as HTML tags, punctuation marks, and stop words, and converting the text into a standardized format suitable for analysis.

3. **Data Exploration:**
   Exploring the characteristics of the email dataset, including the distribution of spam and ham emails, identifying key features, and gaining insights into the underlying patterns.

4. **Word Vectorization:**
   Transforming the preprocessed text data into numerical vectors using techniques such as Bag-of-Words (BoW), TF-IDF (Term Frequency-Inverse Document Frequency), or word embeddings to represent the semantic meaning of the text.

5. **Model Building and Evaluation:**
   Building and training the classification models using the vectorized text data. We experiment with various machine learning and deep learning models, including decision trees, gradient boosting, RNNs, LSTM, BERT, and FLAN-T5. The performance of each model is evaluated using metrics such as recall and F1 scores to determine its effectiveness in accurately classifying emails as spam or ham.

Each module in our methodology plays a crucial role in the overall classification process, contributing to the effectiveness and accuracy of the final spam email classifier. By systematically evaluating the performance of different models, our study aims to provide insights into the most effective approaches for combating spam emails and enhancing email security.
