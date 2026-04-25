#  Fake News Detection using NLP (TF-IDF + Logistic Regression)

##  Overview
This project builds a **machine learning model** to classify news articles as **REAL or FAKE** using Natural Language Processing (NLP).

It combines **title + article text**, processes them using **TF-IDF**, and applies a **Logistic Regression classifier** for prediction.

---

## Problem Statement
Fake news spreads rapidly across digital platforms, making manual verification difficult and time-consuming.

The goal of this project is to **automate fake news detection** using machine learning techniques.

---

##  Methodology

### 1. Data Preprocessing
- Combined **title + text**
- Converted text to lowercase
- Removed URLs and unwanted characters

### 2. Feature Engineering
- Used **TF-IDF Vectorization**
- Included:
  - Unigrams
  - Bigrams

### 3. Model
- **Logistic Regression**
- Used **balanced class weights** to handle data imbalance

---

## Model Performance

| Metric     | Score |
|------------|------|
| Accuracy   | **100%** |
| Precision  | **1.00** |
| Recall     | **1.00** |
| F1-Score   | **1.00** |

###  ROC-AUC
- **AUC Score: 1.00**
- Indicates excellent ability to distinguish between fake and real news

---

##  Project Structure
Fake-News-Detection/

│── Fake_News_Detection_using_TF_IDF_and_Logistic_Regression_2-3.ipynb

│── no_label-2.csv

│── README.md


---

##  How to Run

1. Open the notebook in **Google Colab / Jupyter Notebook**
2. Upload required dataset files:
   - `with_label.csv`
   - `no_label.csv`
3. Run all cells
4. The model will train and generate predictions

---

##  Output

- Predictions are stored in:
  - `no_label.csv`
- A new column is added:
  - **label → TRUE / FALSE**

---

##  Applications

- Fake news detection systems
- Fact-checking tools
- Social media moderation
- NLP classification projects

---

##  Notes

- Dataset is **not included**
- Upload dataset before running the notebook

---

## Key Insight

Even simple models like **Logistic Regression**, when combined with **TF-IDF**, can perform extremely well for text classification tasks.

---

##  Future Improvements

- Use deep learning models (LSTM, BERT)
- Improve dataset size and diversity
- Deploy using **Streamlit**
- Add real-time prediction API

---

##  Acknowledgment

This project demonstrates the practical use of **NLP + Machine Learning** for solving real-world problems.
