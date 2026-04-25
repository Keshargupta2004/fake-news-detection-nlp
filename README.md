# Fake News Detection using NLP (TF-IDF + Logistic Regression)

## Overview

This project focuses on detecting whether a news article is real or fake using basic NLP techniques and a machine learning model. It uses both the title and the full article text to make predictions.

---

## Problem

Fake news spreads very quickly online, and manually verifying content is not always practical. The goal here is to build a simple system that can automatically classify news as real (TRUE) or fake (FALSE).

---

## Approach

* Combined the **title and text** of each article
* Cleaned the data (lowercase, removed URLs and unwanted characters)
* Converted text into numerical features using **TF-IDF (unigrams + bigrams)**
* Trained a **Logistic Regression model**
* Used balanced class weights to handle data imbalance

---

## Model Performance

* Train-test split: 80-20
* Evaluation metric: Accuracy

**Validation Accuracy: ~99%**

---

## Files in this Repository

* `Fake_News_Detection_using_TF_IDF_and_Logistic_Regression.ipynb` → main notebook
* `no_label.csv` → final output file with predicted labels
* `README.md` → project description

---

## How to Run

1. Open the notebook in Google Colab
2. Check upload:

   * `with_label.csv`
   * `no_label.csv`
3. Run all cells
4. The model will generate predictions and update `no_label.csv`

---

## Output

The final predictions are stored in `no_label.csv`.
This file contains the original test data with an added **label column (TRUE/FALSE)**.

---

## Where this can be useful

* Filtering fake news on social media
* Supporting fact-checking tools
* Basic content moderation systems

---

## Notes

The dataset is not included here, so you’ll need to upload it before running the notebook.

---

## Final Thoughts

This project shows that even simple models like Logistic Regression, when combined with good preprocessing and TF-IDF features, can perform really well on text classification tasks.
