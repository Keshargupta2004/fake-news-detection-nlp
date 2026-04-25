📰 Fake News Detection using NLP (TF-IDF + Logistic Regression)
📌 Overview
This project builds a machine learning model to classify news articles as REAL or FAKE using Natural Language Processing (NLP).
It combines title + article text, processes them using TF-IDF, and applies a Logistic Regression classifier for prediction.
🚨 Problem Statement
Fake news spreads rapidly across digital platforms, making manual verification difficult and time-consuming.
The goal of this project is to automate fake news detection using machine learning techniques.
⚙️ Methodology
1. Data Preprocessing
Combined title + text fields
Converted text to lowercase
Removed URLs, punctuation, and unwanted characters
2. Feature Engineering
Used TF-IDF Vectorization
Included:
Unigrams
Bigrams
3. Model
Applied Logistic Regression
Used balanced class weights to handle class imbalance
📊 Model Performance
Metric	Score
Accuracy	100%
Precision	1.00
Recall	1.00
F1-Score	1.00
📈 ROC-AUC
AUC Score: 1.00
Indicates excellent distinction between real and fake news
📂 Project Structure
📁 Fake-News-Detection
│── 📄 Fake_News_Detection_using_TF_IDF_and_Logistic_Regression.ipynb
│── 📄 no_label.csv
│── 📄 README.md
🚀 How to Run
Open the notebook in Google Colab / Jupyter Notebook
Upload required dataset files:
with_label.csv
no_label.csv
Run all cells
Model will:
Train on labeled data
Predict labels for unlabeled data
📤 Output
Final predictions are stored in:
👉 no_label.csv
A new column is added:
label → TRUE / FALSE
💡 Applications
📰 Fake news filtering systems
🔍 Fact-checking tools
📱 Social media content moderation
🧠 NLP-based classification tasks
⚠️ Notes
Dataset is not included in the repository
Make sure to upload it before running the notebook
🧠 Key Insight
Even simple models like Logistic Regression, when combined with strong preprocessing and TF-IDF features, can achieve high performance in text classification tasks.
📌 Future Improvements
Use Deep Learning models (LSTM, BERT)
Improve generalization with larger datasets
Deploy as a web app (Streamlit)
Add real-time news verification API
🙌 Acknowledgment
This project was developed as part of learning and applying NLP + Machine Learning concepts for real-world problems.
