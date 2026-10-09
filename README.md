# 🧠 Yelp Review Sentiment Analysis using NLP

## 📌 Project Overview

This project focuses on sentiment analysis of Yelp reviews using Natural Language Processing (NLP) and Machine Learning techniques.

The objective is to classify text reviews according to their sentiment and compare different approaches for text representation and classification.

## 🎯 Objectives

- Clean and preprocess textual data.
- Apply tokenization, stop-word removal, and lemmatization.
- Convert text into numerical features using Bag of Words and TF-IDF.
- Train and compare Machine Learning classification models.
- Evaluate model performance using classification metrics.
- Explore Transformer-based sentiment analysis with DistilBERT, if supported by the notebook.

## 🛠️ Technologies

- Python
- Jupyter Notebook
- Pandas and NumPy
- NLTK
- Scikit-learn
- Matplotlib and Seaborn
- Hugging Face Transformers, if used

## 🔄 Project Workflow

1. Load and explore the Yelp review dataset.
2. Clean and preprocess text.
3. Transform text into numerical representations.
4. Train classification models.
5. Evaluate and compare predictions.
6. Visualize the results.

## 🤖 Models and Techniques

The notebook explores the following approaches:

- Multinomial Naive Bayes
- Logistic Regression
- Linear Support Vector Classification (Linear SVC)
- TF-IDF and Bag of Words
- DistilBERT, if implemented in the notebook

## 📊 Evaluation

Model performance can be evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

Actual evaluation results should be added after running the notebook.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/capriiisuun/nlp-sentiment-analysis-yelp.git
cd nlp-sentiment-analysis-yelp
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
pip install pandas numpy nltk scikit-learn matplotlib seaborn jupyter
```

Install `transformers` and `torch` only if required by the DistilBERT section.

### 4. Launch the notebook

```bash
jupyter notebook sentiment_analysis_yelp.ipynb
```

## 📁 Repository Structure

```text
nlp-sentiment-analysis-yelp/
├── sentiment_analysis_yelp.ipynb
└── README.md
```

## 👩‍💻 Authors

Alaa Elkorchi and Mohamed Aymen Malek

AI & Data Science Engineering Students

GitHub: [@capriiisuun](https://github.com/capriiisuun)

---

⭐ Explore the notebook to discover the NLP workflow and model comparison.
