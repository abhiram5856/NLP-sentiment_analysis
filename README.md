# 📚 Kindle Review Sentiment Analysis

A Natural Language Processing (NLP) project that analyzes Kindle book reviews and classifies them as **positive or negative sentiment** using machine learning techniques.

---

## 🚀 Project Overview

This project focuses on extracting insights from textual data by building a sentiment classification model. It includes:

* Text preprocessing
* Feature extraction (BoW & TF-IDF)
* Model training
* Performance evaluation

---

## 📂 Dataset Information

The dataset contains **12,000 Kindle reviews**  with:

* Review Text
* Rating (1 to 5 stars)

### 🎯 Target Transformation:

* Ratings < 3 → Negative (0)
* Ratings ≥ 3 → Positive (1)

---

## 🛠️ Tech Stack

* **Language:** Python 🐍
* **Libraries:**

  * Pandas
  * NumPy
  * NLTK
  * Scikit-learn
  * BeautifulSoup
  * Regex (re)

---

## ⚙️ Workflow

### 1. Data Preprocessing

* Converted text to lowercase
* Removed:

  * Special characters
  * Stopwords
  * URLs
  * HTML tags
* Cleaned extra spaces

---

### 2. Text Processing

* Applied:

  * Bag of Words (BoW)
  * TF-IDF Vectorization

---

### 3. Model Training

* Used **Naive Bayes Classifier (GaussianNB)**

---

### 4. Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## 📊 Results

| Method       | Accuracy |
| ------------ | -------- |
| Bag of Words | ~29%     |
| TF-IDF       | ~28.5%   |

⚠️ Accuracy is low due to:

* Use of simple model (GaussianNB)
* No advanced NLP techniques

---

## 📌 Key Insights

* Text preprocessing significantly impacts performance
* TF-IDF did not outperform BoW significantly
* Naive Bayes is fast but not optimal for complex NLP tasks

---

## ▶️ How to Run

1. Clone the repository:

```bash id="h2p9kx"
git clone https://github.com/your-username/kindle-sentiment-analysis.git
cd kindle-sentiment-analysis
```

2. Install dependencies:

```bash id="ok0p8g"
pip install -r requirements.txt
```

3. Run the notebook:

```bash id="2df9zv"
jupyter notebook
```

---

## 📈 Future Improvements

* Use advanced models:

  * Logistic Regression
  * SVM
  * LSTM / Transformers 🤖

* Apply:

  * Lemmatization properly
  * Hyperparameter tuning
  * Better feature engineering

---

## 💡 Use Cases

* Product Review Analysis
* Customer Feedback Systems
* E-commerce Sentiment Tracking
* Recommendation Systems

---

## 👨‍💻 Author

**Abhiram Modukuru**

* AIML Student | ML Enthusiast | Future Builder 🚀

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!

---
