# 🎬 Movie Genre Classification

This project uses Natural Language Processing (NLP) and Machine Learning to classify movie genres based on their textual descriptions. The workflow includes data cleaning, feature extraction, model training, and evaluation.

---

## 📁 Dataset

The dataset contains movie plot summaries along with their associated genres. Each movie may belong to multiple genres (multi-label classification).

---

## 📌 Features

- Text preprocessing (lemmatization, stopwords removal)
- Data visualization (WordClouds)
- TF-IDF feature extraction
- Multi-label classification with One-vs-Rest strategy
- Evaluation with precision, recall, and F1-score

---

## 🧪 Machine Learning Models Used

- **XGBoost**
- **Multinomial Naive Bayes**
- **Logistic Regression**

---

## 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

1. Install the required dependencies:

```bash
pip install -r requirements.txt
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook CREDIT CARD FRAUD DETECTION.ipynb
```
3. Execute each cell step-by-step to perform preprocessing, training, and evaluation.


## 📦 Requirements

All dependencies are listed in the `requirements.txt` file. Key libraries include:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`
- `nltk`
- `wordcloud`
- `textblob`

📊 Sample Output

## ✅ Accuracy and Classification Report

Each model is evaluated using the following metrics:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**

### 📌 Example – Logistic Regression:

```bash
Precision: 0.82
Recall: 0.79
F1-score: 0.80
Accuracy: 0.81
```

## 📁 Project Structure

```bash
📂 Movie Genre Classification
.
├── Movie Genre Classification.ipynb
├── requirements.txt
└── README.md

```
