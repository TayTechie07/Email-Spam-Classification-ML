# 📧 Email Spam Classification using Machine Learning

## Project Overview
This project implements a machine learning–based email spam classifier that automatically labels messages as **Spam** or **Ham (Not Spam)**. It leverages NLP preprocessing, TF-IDF feature extraction, and supervised learning for accurate classification.

## Objectives
- Preprocess raw text data  
- Convert text into numerical features using TF-IDF  
- Train a supervised ML model  
- Classify messages as spam or non-spam  
- Evaluate model performance with standard metrics  

## Dataset
**Dataset:** SMS Spam Collection Dataset  
**Columns:**  
- `spamORham` – Label (`0 = Ham`, `1 = Spam`)  
- `Message` – Text content of the message  

## Technologies & Libraries
- Python, Pandas, NumPy  
- Scikit-learn  
- Regular Expressions (`re`)  

## Methodology

### 1. Data Preprocessing
- Converted text to lowercase  
- Removed punctuation, numbers, and extra spaces  

### 2. Feature Extraction
- Applied **TF-IDF Vectorization**  
- Removed English stopwords  

### 3. Model Training
- **Multinomial Naive Bayes**  
- Dataset split: 80% training, 20% testing  

### 4. Model Evaluation
- **Accuracy:** 0.9731  
- **Confusion Matrix:**  

## How to Run
1. Clone the repository  
2. Install dependencies: `pip install -r requirements.txt`  
3. Run the Jupyter notebook or Python script  

## Future Improvements
- Try Logistic Regression or SVM for comparison  
- Use n-grams to capture context  
- Deploy the model with Streamlit or Flask  
- Upgrade to deep learning models (LSTM / BERT)  

## Author
**Tayyba Waheed**  
Machine Learning Intern
