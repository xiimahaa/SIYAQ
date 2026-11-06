# SIYAQ: Sentiment Analysis and Linguistic Challenge Evaluation

This project investigates sentiment classification using two different approaches:

- **TF-IDF + Logistic Regression**
- **all-MiniLM-L6-v2 Sentence Embeddings + Logistic Regression**

The models are evaluated on the overall test set and on challenging linguistic subsets, including **contrastive language** and **negation**.

---

## 📁 Repository Contents

- `SIYAQFINAL.ipynb` — Complete implementation and evaluation
- `sentiment+labelled+sentences.zip` — Dataset used in the project

---

## Models

### 1. TF-IDF + Logistic Regression

A traditional machine learning baseline using TF-IDF text features with Logistic Regression.

### 2. MiniLM + Logistic Regression

Uses pretrained **all-MiniLM-L6-v2** sentence embeddings combined with Logistic Regression.

---

## 📊 Final Results

| Model | Overall Accuracy | Overall Macro F1 |
|---|---:|---:|
| **TF-IDF + LR** | **0.8202** | **0.8202** |
| **MiniLM + LR** | **0.8674** | **0.8673** |

### 🔍 Linguistic Challenge Evaluation

| Model | Contrastive Accuracy | Contrastive Macro F1 | Negation Accuracy | Negation Macro F1 |
|---|---:|---:|---:|---:|
| **TF-IDF + LR** | 0.6111 | 0.6000 | 0.7326 | 0.6434 |
| **MiniLM + LR** | **0.7778** | **0.7662** | **0.8023** | **0.7574** |

---

## Key Findings

- **MiniLM + Logistic Regression achieved the best overall performance**, with an accuracy of **86.74%**.
- MiniLM performed better than TF-IDF on both linguistic challenge subsets.
- The **contrastive subset contains 18 verified examples**, where MiniLM achieved **77.78% accuracy** compared with **61.11%** for TF-IDF.
- The **negation subset contains 86 examples**, where MiniLM achieved **80.23% accuracy** compared with **73.26%** for TF-IDF.
- Both linguistic phenomena remain challenging for the models compared with their overall performance.

> **Note:** Only 4 verified examples contained both contrast and negation. Because this overlap subset is very small, no separate performance analysis was conducted.

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Sentence Transformers
- Hugging Face Transformers
- Logistic Regression

---

## ▶️ How to Run

1. Clone the repository.
2. Install the required Python libraries.
3. Open `SIYAQFINAL.ipynb`.
4. Run the notebook cells in order.
