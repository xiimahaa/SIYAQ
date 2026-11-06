# SIYAQ: Sentiment Analysis and Primary Challenge Investigation

This project investigates sentiment classification using two different approaches:

- **TF-IDF + Logistic Regression**
- **all-MiniLM-L6-v2 Sentence Embeddings + Logistic Regression**

The project also analyzes challenging linguistic patterns, including **negation** and **contrastive language**.

---

## 📊 Results

| Model / Evaluation | Accuracy | Macro F1 |
|---|---:|---:|
| TF-IDF + Logistic Regression | *Add your final result* | *Add your final result* |
| MiniLM + Logistic Regression | **89.71%** | **89.69%** |

### Contrastive Language Analysis

The MiniLM model was further evaluated on manually verified contrastive sentences:

- **Overall Test Accuracy:** 89.71%
- **Contrastive Subset Accuracy:** 76.92%
- **Contrastive Examples:** 39
- **Correct Predictions:** 30
- **Incorrect Predictions:** 9

The results show that contrastive language is more challenging for the model than general sentiment classification.

---

## 🔍 Project Analysis

The project investigates:

- Overall sentiment classification performance
- Negation as a linguistic challenge
- Contrastive language patterns such as **but**, **however**, and **although**
- Comparison between the two modeling approaches

---

## 🛠️ Technologies

- Python
- Scikit-learn
- Sentence Transformers
- all-MiniLM-L6-v2
- Pandas
- NumPy

---

## 📁 Files

- `SIYAQFINAL.ipynb` — Complete implementation and evaluation
- `sentiment+labelled+sentences.zip` — Dataset used in the project
