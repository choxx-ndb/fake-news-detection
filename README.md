# Fake News Detection Project

The goal of this project is to classify news articles as **REAL** or **FAKE** using text data and machine learning techniques.

---

## 📂 Dataset

The dataset is not included in this repository due to size limitations.

You can download it from Kaggle:
- Fake and Real News Dataset

After downloading, place the files inside the `data/` folder:
- True.csv
- Fake.csv

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
│ └── (not included in repo)
│
├── notebooks/
│ ├── 01_data_preparation.ipynb
│ ├── 02_eda.ipynb
│ └── 03_model.ipynb
│
├── README.md
└── requirements.txt

## 🚀 Next Steps

- Try other models (Naive Bayes, Random Forest)
- Improve preprocessing
- Try embeddings (advanced NLP)

---
