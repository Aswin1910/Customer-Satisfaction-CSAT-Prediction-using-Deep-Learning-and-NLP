# Customer-Satisfaction-CSAT-Prediction-using-Deep-Learning-and-NLP
Customer Satisfaction (CSAT) Prediction using Deep Learning and NLP
Project Overview

This project focuses on predicting Customer Satisfaction (CSAT) scores for an e-commerce customer support system using Deep Learning and Natural Language Processing (NLP) techniques. The model analyzes customer interaction data, service response time, and customer remarks to estimate the satisfaction score provided by customers.

Customer satisfaction is an important metric for evaluating the quality of customer support services. By predicting CSAT scores, businesses can identify service issues, improve support quality, and enhance customer experience.

Dataset Features

The dataset includes information related to customer support interactions such as:

Channel Name

Issue Category

Sub-category

Customer Remarks (text feedback)

Customer City

Product Category

Item Price

Connected Handling Time

Agent Shift

Tenure Bucket

Issue Reported Time

Issue Responded Time

CSAT Score (Target Variable)

Project Workflow

The project follows a complete Machine Learning and Deep Learning pipeline:

1. Data Understanding

Dataset exploration

Feature analysis

Identifying missing values

2. Data Wrangling

Handling missing values

Outlier detection and removal

Data cleaning

3. Feature Engineering

Response time calculation

Date-time feature extraction

Categorical encoding

4. Text Processing (NLP)

Customer remarks are processed using:

Text cleaning

Tokenization

Lemmatization

Stopword removal

TF-IDF Vectorization

5. Exploratory Data Analysis

Various visualizations were created to understand relationships between features and CSAT scores.

Examples include:

CSAT distribution

Channel vs CSAT

Category vs CSAT

Response time vs CSAT

Correlation heatmap

Pair plots

6. Hypothesis Testing

Statistical tests were conducted to validate relationships between variables such as:

Channel type and CSAT score

Agent shift and CSAT score

Response time and customer satisfaction

7. Model Implementation

Deep Learning (Artificial Neural Network)

The Deep Learning model was trained using both structured features and text features extracted from customer remarks.

8. Model Deployment

The trained model was deployed using Streamlit, allowing users to input service details and receive real-time CSAT predictions.

Technologies Used

Python

Pandas

NumPy

Scikit-learn

TensorFlow / Keras

NLTK

TF-IDF Vectorizer

Matplotlib & Seaborn

Streamlit

Project Outcome

The system successfully predicts CSAT scores ranging from 0 to 5 based on customer service interaction data. This solution can help businesses:

Identify factors affecting customer satisfaction

Improve response efficiency

Enhance customer service quality

Support data-driven decision making

Future Improvements

Use advanced NLP models such as BERT

Implement real-time support analytics dashboards

Deploy the system on cloud platforms
