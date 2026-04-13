# Twitter Sentiment Analysis

## Overview

A machine learning project that classifies tweets into **Positive, Negative, Neutral, and Irrelevant** using NLP techniques.

---

##  Approach

* Text preprocessing (cleaning, stopwords removal, lemmatization)
* TF-IDF vectorization (unigrams + bigrams)
* Logistic Regression (multinomial)
* Hyperparameter tuning with GridSearchCV

---

## Results

* Accuracy: **0.83**
* F1 Score: **0.83**
* ROC-AUC: **0.95**

---

## Key Highlights

* Removed **13,814 duplicate tweets** to improve performance
* TF-IDF with bigrams improved classification accuracy
* Built an end-to-end pipeline (preprocessing → training → prediction)

---

##  Files

```
Twitter-Sentiment-Analysis/
│── Twitter_Sentiment_Analysis.ipynb
│── README.md
│── requirements.txt
```

---

## Usage

Run the notebook and use:

```python
predict_sentiment("I love this movie")
```

---

## Future Work

* Try deep learning models (LSTM, BERT)
* Build a web app (Streamlit)
