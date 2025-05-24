
# 🛍️ Amazon Product Reviews Sentiment Analysis

This project analyzes customer sentiment in Amazon product reviews using Natural Language Processing (NLP) techniques and Exploratory Data Analysis (EDA). The goal is to uncover insights about customer satisfaction, review patterns, and rating distributions.

## 📌 Project Overview

- **Objective:** Understand customer sentiments from Amazon reviews through sentiment labeling and text analysis.
- **Dataset:** `Reviews.csv` (Amazon product reviews dataset with text and numeric ratings)
- **Techniques Used:**
  - Data Cleaning & Preprocessing
  - Text Normalization (Tokenization, Lemmatization)
  - Sentiment Mapping (Score-based)
  - Exploratory Data Analysis (Score & Text Distributions)
  - Visualization of Review Trends

## 📂 Folder Structure

```
project/
│
├── data/
│   └── Reviews.csv
│
├── notebooks/
│   └── sentiment_analysis.ipynb
│
├── outputs/
│   └── sentiment_plots.png
│
└── README.md
```

## 🛠️ Technologies & Libraries

- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn
- NLTK (Natural Language Toolkit)

## ⚙️ Workflow Steps

1. **Data Loading**
   - Loaded `Reviews.csv` using Pandas.
   - Performed structure checks using `.head()`, `.info()`, `.shape`.

2. **Data Cleaning**
   - Removed missing values and duplicate entries.
   - Filtered out irrelevant columns.

3. **Sentiment Labeling**
   - Mapped `Score` to sentiment categories:
     - 1–2 → Negative
     - 3 → Neutral
     - 4–5 → Positive
   - Added a `Sentiment` column.

4. **Text Preprocessing**
   - Lowercasing
   - Removing punctuation and digits
   - Tokenization
   - Stopword removal (NLTK)
   - Lemmatization

5. **Exploratory Data Analysis**
   - Analyzed review lengths and score distributions.
   - Visualized sentiment distribution and review word counts.

## 📈 Key Insights

- Majority of reviews are **positive** (Score = 5).
- Most reviews are concise, under 100 words.
- Useful patterns observed between sentiment class and review length.

## 🧠 Potential Extensions

- Train a machine learning model to predict sentiment from text.
- Use TF-IDF or Word Embeddings for feature engineering.
- Build a sentiment dashboard with Streamlit or Flask.

## 📌 Contributors

- Group 3 – ADTA 5340 – University of North Texas

## 📝 License

This project is for academic and research use only.
