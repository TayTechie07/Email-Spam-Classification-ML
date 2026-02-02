# 📧 Email Spam Classification using Machine Learning

## 📌 Project Overview

This project focuses on building a **machine learning–based email spam classification system** that automatically identifies whether a given message is **Spam** or **Not Spam **. The model is trained on labeled text data and uses standard Natural Language Processing (NLP) techniques to preprocess text, extract features, and perform classification.

The project is designed as an **internship-level applied machine learning task**, emphasizing clarity, correctness, and real-world relevance.

---

## 🎯 Objectives

* Preprocess raw email/message text data
* Convert text into numerical features using TF-IDF
* Train a supervised machine learning model
* Classify messages as spam or non-spam
* Evaluate model performance using standard metrics

---

## 📂 Dataset

**Dataset Used:** SMS Spam Collection Dataset

**Columns:**

* `spamORham` – Label indicating spam or ham
* `Message` – Text content of the message

**Label Encoding:**

* `0` → Ham (Not Spam)
* `1` → Spam

The dataset contains real-world SMS/email-style messages commonly used for spam detection experiments.

---

## 🛠️ Technologies & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Regular Expressions (re)

---

## 🧠 Methodology

### 1️⃣ Data Preprocessing

* Converted text to lowercase
* Removed punctuation, numbers, and extra spaces
* Cleaned raw text for effective feature extraction

### 2️⃣ Feature Extraction

* Applied **TF-IDF Vectorization** to transform text data into numerical form
* Removed English stopwords
* Limited features to the most informative terms

### 3️⃣ Model Training

* Used **Multinomial Naive Bayes**, a model well-suited for text classification tasks
* Split dataset into training (80%) and testing (20%) sets

### 4️⃣ Model Evaluation

The model was evaluated using:

* Accuracy
* Confusion Matrix

These metrics ensure reliable spam detection while minimizing false positives.

---

## 📊 Results

The trained model achieved strong performance in distinguishing spam messages from legitimate ones, demonstrating high precision and recall suitable for real-world spam filtering applications.

---

## 📁 Project Structure

```
email-spam-classification/
│
├── spam.csv
├── spam_classification.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository
2. Install required dependencies
3. Run the Jupyter notebook or Python script

---

## 📝 Key Learnings

* Practical application of NLP preprocessing techniques
* Importance of feature extraction in text-based ML tasks
* Model evaluation using classification metrics
* End-to-end implementation of a supervised ML project

---

## 🚀 Future Improvements

* Try Logistic Regression or SVM for comparison
* Use n-grams for better context capture
* Deploy the model using Streamlit or Flask
* Upgrade to deep learning models (LSTM / BERT)

---

## 👤 Author

**Tayyba Waheed**
Machine Learning Intern

---

## 📌 Note

This project was developed as part of a **Machine Learning Internship Task** and demonstrates foundational skills in NLP and supervised learning.
