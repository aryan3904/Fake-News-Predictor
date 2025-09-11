\# 📰 Fake News Predictor  



A simple machine learning project built with \*\*Python\*\* that classifies news articles as \*\*Real\*\* or \*\*Fake\*\*.  

This project demonstrates text preprocessing, feature extraction, and classification using standard ML techniques.  



---



\## 📌 Features  

\- Preprocesses text data (removes stopwords, punctuation, etc.)  

\- Converts text into numerical features using TF-IDF / CountVectorizer  

\- Trains a classification model (e.g., Logistic Regression / Naive Bayes)  

\- Predicts whether a given news article is \*\*Fake\*\* or \*\*Real\*\*  

\- Evaluation metrics: Accuracy, Confusion Matrix, Classification Report  



---



\## 🛠️ Tech Stack  

\- \*\*Python\*\*  

\- \*\*Pandas / NumPy\*\* (data processing)  

\- \*\*Scikit-learn\*\* (ML models \& evaluation)  

\- \*\*Matplotlib / Seaborn\*\* (visualization)  



---



\## 📂 Dataset  

\- Dataset used: \[Fake News Dataset on Kaggle](https://www.kaggle.com/datasets/yashvardhanthakker/fake-or-real-news-dataset)  



Example usage in code:  

```python

import pandas as pd

df = pd.read\_csv("train.csv")



