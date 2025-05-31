# 📰 Fake News Detection Using Logistic Regression

## 🔍 Overview
This project aims to classify news articles as **real** or **fake** using **logistic regression**. It uses natural language processing (NLP) techniques such as text cleaning, TF-IDF vectorization, and binary classification to detect misinformation.

---

## 📁 Dataset
- **Source**: [Kaggle Fake News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)
- The dataset contains real and fake news articles collected from reliable and unreliable sources.

---

## 🧠 Techniques Used
- **Text Preprocessing**:
  - Lowercasing
  - Removing punctuation, numbers, special characters, and HTML
  - Removing stopwords and noise
- **Feature Extraction**:
  - TF-IDF (Term Frequency–Inverse Document Frequency)
- **Model**:
  - Logistic Regression (for binary classification)

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- Numpy
- Scikit-learn
- NLTK or SpaCy (optional for text preprocessing)
- Matplotlib / Seaborn (for visualization)

---

## 🧪 How It Works
1. Load and inspect the dataset
2. Clean and preprocess the text data
3. Vectorize the cleaned text using TF-IDF
4. Train a logistic regression model
5. Evaluate performance using accuracy, confusion matrix, precision, recall, and F1 score

---

## 📊 Results
- Accuracy: ~90% (depends on data split and preprocessing quality)
- Precision and recall show effective binary classification performance

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Divyanshyadavofficial/ApplicationsOfHandsOnMl.git
   cd ApplicationsOfHandsOnMl
   pip install -r requirements.txt


