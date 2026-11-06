# SIYAQ: Sentiment Analysis 📝

## 📌 Overview

This project implements and compares two approaches for **binary sentiment classification** of text reviews:

- **TF-IDF + Logistic Regression**
- **all-MiniLM-L6-v2 Sentence Embeddings + Logistic Regression**

The goal is to classify reviews as **Positive** or **Negative** and compare the performance of both approaches.

---

## 🔍 Primary Challenge: Contrastive Language

The main analysis focuses on reviews containing contrastive expressions such as:

- but
- however
- although
- though
- yet

These expressions can be challenging because the sentiment may change within the same sentence.

The project also includes **negation analysis** and an analysis of **misclassified examples**.

---

## 📊 Evaluation

Both models are evaluated using:

- **Accuracy**
- **Macro F1 Score**

The analysis includes:

- Overall model performance
- Contrastive language subset analysis
- Negation analysis
- Model comparison
- Error analysis

---

## 📂 Dataset

The project uses the **Sentiment Labelled Sentences** dataset.

Labels:

- `0` → Negative
- `1` → Positive

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Sentence Transformers
- Logistic Regression
- all-MiniLM-L6-v2

---

## 🚀 How to Run

1. Download or clone this repository.
2. Open `SIYAQFINAL.ipynb`.
3. Run the notebook cells in order.

---

## 📁 Project Structure

```text
SIYAQ/
├── SIYAQFINAL.ipynb
├── sentiment+labelled+sentences.zip
└── README.md
```

---

## 👥 Team Project

This project was developed as part of an **NLP course project** focused on sentiment analysis and challenging linguistic patterns.
