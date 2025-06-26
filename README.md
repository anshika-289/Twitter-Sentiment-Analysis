
# Twitter Sentiment Analysis 💬

This project performs sentiment analysis on tweets using machine learning techniques. It classifies the sentiments expressed in tweets into categories such as **Positive**, **Negative**, **Neutral**, and **Irrelevent**.

## 📚 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Notebook Highlights](#notebook-highlights)
- [Installation & Usage](#installation--usage)
- [Results](#results)

---

## 📌 Overview

Twitter Sentiment Analysis is a natural language processing task aimed at determining the emotional tone behind social media texts. In this notebook, we:
- Load and clean tweet data.
- Visualize tweet sentiments using word clouds and graphs.
- Train ML models to classify tweets into sentiment categories.
- Evaluate and interpret model performance.

---

## 📂 Dataset

The dataset used consists of pre-labeled tweets with sentiment annotations. It typically includes:

- **Text**: The tweet content.
- **Sentiment**: Label (Positive / Negative / Neutral).
- **Entity**

---

## 🛠 Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**, **WordCloud**
- **NLTK**, **re** (for preprocessing)
- **Scikit-learn** (TF-IDF Vectorizer, ML models)

---

## 📓 Notebook Highlights

- **Data Preprocessing**: Cleans special characters, stopwords, URLs, and user mentions.
- **Visualization**: Word clouds and sentiment distributions.
- **Modeling**:
  - TF-IDF Vectorization
  - Logistic Regression and Random Forest
- **Evaluation**: Confusion matrix, accuracy, precision, recall, and F1-score.

---

## 🚀 Installation & Usage

To run the notebook:

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook Twitter_Sentiment_Analysis.ipynb
```

Alternatively, open directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/your-repo-name/blob/main/Twitter_Sentiment_Analysis.ipynb)

---

## 📊 Results

- Achieved high accuracy on test data using logistic regression - 88%.
- Achieved high accuracy on test data using random forest - 89%.
- Successfully classified tweets with reasonable precision and recall.

---
