# SmartSpam-Shield
SmartSpam Shield is a machine learning–based spam detection system that classifies SMS or email text as Spam or Ham (not spam). The project combines Natural Language Processing (NLP) techniques with multiple ML algorithms and provides a Streamlit-based front-end interface for real-time predictions.

#Features

Preprocessing pipeline with text cleaning, tokenization, stemming, stopword removal, and TF-IDF vectorization.

Implementation of multiple ML models: SVC, Logistic Regression, Random Forest, Decision Tree, KNN, and XGBoost.

Model evaluation using Accuracy, Precision, Recall, and F1-Score.

Streamlit front-end interface for real-time user interaction.

Future plan to integrate Large Language Models (LLMs) for improved adaptability to evolving spam trends.

#Methodology

Data Collection – Kaggle SMS Spam Collection Dataset.

Exploratory Data Analysis (EDA) – Understanding spam/ham distribution, keyword frequency, and message patterns.

Data Preprocessing – Lowercasing, punctuation removal, tokenization, stopword removal, stemming, TF-IDF vectorization.

Model Training – Training and testing ML models (SVC, Logistic Regression, Decision Tree, Random Forest, KNN, XGBoost).

Evaluation – Comparing models using accuracy, precision, recall, and F1-score.

Integration – Exporting the best-performing model and deploying it through Streamlit for real-time predictions.

#Installation & Usage
Prerequisites

Python 3.8+

Jupyter Notebook

PyCharm (optional, for Streamlit integration)
