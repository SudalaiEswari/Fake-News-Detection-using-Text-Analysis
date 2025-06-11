# 📰 Fake News Detection Using Text Analysis

This project demonstrates a machine learning-based solution for detecting **fake news** using **text analysis** and **Natural Language Processing (NLP)** techniques. It classifies news articles as either **FAKE** or **REAL** using a supervised learning model.

---

## 📌 Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [How It Works](#how-it-works)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Work](#future-work)
- [License](#license)

---

## 📖 Introduction

Fake news has become a serious problem in the digital age. With the spread of false information on social media and other platforms, it has become critical to detect and classify news content. This project uses **TF-IDF vectorization** and a **Passive Aggressive Classifier** to identify whether a given news article is real or fake based on its content.

---

## 💻 Technologies Used

- Python 3.x
- Pandas
- Scikit-learn (sklearn)
- TF-IDF Vectorizer
- PassiveAggressiveClassifier

---

## 📊 Dataset

The project uses a dataset containing news articles labeled as "FAKE" or "REAL".  
You can download a dataset from [Kaggle - Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news).

**CSV Columns Required:**
- `text` – full content of the news article
- `label` – either `FAKE` or `REAL`

---

## ⚙️ How It Works

1. Load and explore the dataset
2. Preprocess the text using **TF-IDF vectorization**
3. Train a **PassiveAggressiveClassifier**
4. Predict on test data
5. Evaluate model performance using accuracy and confusion matrix

---

## 🚀 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/fake-news-detection.git
   cd fake-news-detection
