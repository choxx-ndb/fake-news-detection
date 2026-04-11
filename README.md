# Fake News Detection Project

The goal of this project is to classify news articles as **REAL** or **FAKE** using text data and machine learning techniques.

This project follows a complete workflow from data preparation to model training and explainability.

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
5. Perform exploratory data analysis (EDA)
6. Convert text into numerical features using TF-IDF
7. Train a Logistic Regression model
8. Evaluate the model
9. Interpret predictions using LIME and SHAP

---

## 🧠 Explainability

To better understand how the model makes predictions, I added an explainability notebook.

In `04_explainability.ipynb`, I use:
- **LIME** to explain individual predictions
- **SHAP** to analyze word-level feature contributions

This helps make the fake news detection model more interpretable instead of treating it like a black box.

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- LIME
- SHAP

---

## 🗂️ Project Structure

```bash
fake-news-detection/
│
├── data/
│   └── (not included in repo)
│
├── notebooks/
│   ├── 01_data_preparation.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_model.ipynb
│   └── 04_explainability.ipynb
│
├── README.md
└── requirements.txt
