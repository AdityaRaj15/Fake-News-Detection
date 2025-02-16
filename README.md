# Fake News Detection 🔍📰

A **Machine Learning project** to detect **fake news** using **Natural Language Processing (NLP)** techniques and **Logistic Regression**.

## 📌 Features
- Preprocessing text data using **stopword removal** and **stemming**.
- Converting textual data to numerical data using **TF-IDF Vectorization**.
- Building a **Logistic Regression** model for classification.
- Training and testing on a **dataset of news articles**.

## 🛠️ Technologies Used
- **Python**
- **NumPy**, **Pandas**
- **NLTK** (Natural Language Toolkit)
- **Scikit-learn** (for machine learning algorithms)
- **Regular Expressions** (for text preprocessing)

## 📂 Dataset
The dataset used for training and testing is `train.csv`, which consists of:
- `id` → Unique identifier for each news article.
- `title` → Title of the news article.
- `author` → Author of the article.
- `text` → Full text of the article.
- `label` → **1** (Fake) or **0** (Real).

