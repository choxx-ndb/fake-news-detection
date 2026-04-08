# Fake News Detection Project

The goal of this project is to classify news articles as **REAL** or **FAKE** using text data and machine learning techniques.

---

## 📌 Dataset

The dataset consists of two files:
- `True.csv` → real news articles
- `Fake.csv` → fake news articles

---

## 🔄 Workflow

1. Load and explore the datasets
2. Add labels (REAL / FAKE)
3. Merge the datasets into one
4. Clean and preprocess the text
5. Convert text into numerical features using TF-IDF
6. Train a Logistic Regression model
7. Evaluate the model

---

## 🛠️ Tools Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---
## 🗂️ Project Structure

fake-news-detection/
│
├── data/
│   ├── True.csv
│   └── Fake.csv
│
├── notebooks/
│   ├── 01_data_preparation.ipynb
│   ├── 02_eda.ipynb
│   └── 03_model.ipynb
│
├── README.md
└── requirements.txt

## 🚀 Next Steps

- Try other models (Naive Bayes, Random Forest)
- Improve preprocessing
- Try embeddings (advanced NLP)

---
