
# 📖 Comparative Study of Organic and Synthetic Data for Text Summarization

## 📑 Project Overview
This project performs a comparative analysis of text summarization using **organic** (human-written) and **synthetically generated** text data. A **T5 Transformer model** is used for abstractive summarization, and performance is evaluated using **ROUGE metrics**. The goal is to observe how summarization quality varies between organic and synthetic data sources.

## 🛠️ Technologies & Libraries
- **Python 3.x**
- **Jupyter Notebook**
- **Hugging Face Transformers**
- **PyTorch**
- **ROUGE Score**
- **Pandas**

## 📂 Project Structure
```
text_summarization_study/
│
├── data/
│   ├── organic_data.csv
│   └── synthetic_data.csv
│
├── summarizer.ipynb
│
├── requirements.txt
│
└── README.md
```

## 📊 Datasets
- `organic_data.csv`: Contains original, human-written text samples.
- `synthetic_data.csv`: Contains AI-generated or paraphrased text samples simulating synthetic data.

## 📌 Features
- Load organic and synthetic datasets.
- Summarize each text sample using **T5-small Transformer**.
- Evaluate summarization quality with **ROUGE-1**, **ROUGE-2**, and **ROUGE-L** scores.
- Compare summarization performance across organic and synthetic data.

## ▶️ How to Run
1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook summarizer.ipynb
   ```

3. **View summarization results and ROUGE evaluations in the notebook outputs.**

## 📈 Outcome
This study helps assess the effectiveness of summarization models on varied data types and provides insight into how model performance differs when summarizing organically written versus synthetically generated content.

## 📜 License
Free for academic and research use.
