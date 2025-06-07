---

# 🎯 CodeTech Internship – Task 2

## 📝 Sentiment Analysis on IMDB Movie Reviews

This project is part of the **Machine Learning Internship at CodeTech IT Solutions**. The goal is to build a logistic regression model that can predict the **sentiment** (positive/negative) of movie reviews using **Natural Language Processing (NLP)** techniques.

---

## 📁 Dataset

* **Name:** IMDB Dataset of 50K Movie Reviews
* **Source:** [Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
* **Fields:**

  * `review` — The full text of the movie review
  * `sentiment` — Sentiment label (`positive` or `negative`)

Note: The dataset is not included in the repository due to GitHub's file size restrictions. Please download it manually from the link above if needed for local execution.
---

## 🛠️ Tech Stack

* Python
* Jupyter Notebook
* scikit-learn (Logistic Regression, TF-IDF)
* pandas, numpy
* matplotlib, seaborn
* pickle

---

## 🚀 Workflow

1. Load and inspect the dataset
2. Preprocess reviews (clean text, remove noise)
3. Convert sentiment to binary labels
4. Split into train/test sets
5. Apply TF-IDF vectorization
6. Train a Logistic Regression model
7. Evaluate using accuracy, confusion matrix, classification report
8. Save the model and vectorizer for deployment

---

## 📂 Folder Structure

sentiment-analysis-task2/
│
├── IMDB Dataset.csv # Source dataset
├── Sentiment\_Analysis.ipynb # Full notebook with code and visualizations
├── model/
│ ├── sentiment\_model.pkl # Trained Logistic Regression model
│ └── tfidf\_vectorizer.pkl # Saved TF-IDF vectorizer
└── README.md # This file

---

## 📌 Result

* ✅ Achieved \~88% accuracy on test data
* ✅ Clean and reusable codebase for sentiment classification
* ✅ Ready for API deployment in future phases
* ✅ Evaluated model performance using ROC curve and AUC score to measure the classifier’s ability to distinguish between positive and negative reviews effectively.

> Prepared as **Task 2 Submission** for CodeTech IT Internship

---
