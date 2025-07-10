# 🕵️‍♀️ Fake Job Posting Detection

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to detect fraudulent job postings from a dataset of real and fake job advertisements.

---

## 📌 Project Objective

The goal is to:
- Clean and preprocess job posting text data.
- Apply NLP techniques for feature extraction.
- Build and evaluate machine learning models to classify fake vs real job postings.

---

## 🧠 Technologies & Skills Used

- **Python**
- **Pandas, NumPy** – Data Handling
- **NLTK** – Text Preprocessing
- **Scikit-learn** – Machine Learning
- **Bag of Words (BoW)** – Feature Extraction
- **Logistic Regression & Decision Tree** – Classification Models

---

## 📁 Dataset Overview

The dataset contains information such as:
- Job Title, Location, Company Profile, Description, Requirements, etc.
- The target column `fraudulent` is binary (0 = Real, 1 = Fake).

> 📂 Dataset file used: `fake_job_postings.csv`

---

## 🧼 Preprocessing Steps

- Merged columns like company profile, description, and requirements.
- Lowercased all text and removed punctuation.
- Removed stopwords using **NLTK**.
- Converted cleaned text to a Bag of Words vector.

---

## 🤖 Model Building

Two models were trained and evaluated:
1. **Logistic Regression**
2. **Decision Tree Classifier**

Metrics Used:
- Confusion Matrix
- Precision, Recall, F1-Score

---

## 🧪 Results

| Model               | Accuracy | Fake Class Recall | Fake Class F1-score |
|--------------------|----------|-------------------|----------------------|
| Logistic Regression| ~97-99%  | ~70-80%           | ~0.80                |
| Decision Tree      | ~96-98%  | ~40-70%           | ~0.59–0.80           |

> Logistic Regression generally performed better in terms of identifying fraudulent postings.

---

## ✅ Conclusion

- Text classification using basic NLP and ML can effectively detect fake job posts.
- Logistic Regression was more reliable in identifying fake listings.
- Bag of Words is simple yet effective for this use case.

---

## 🚀 Future Work

- Try **TF-IDF** or **Word Embeddings** for richer feature representation.
- Use advanced models like **Random Forest**, **XGBoost**, or **BERT**.
- Build a simple web UI to detect fraud from user input job ads.

---

## 👤 Author

**Tina Lokhande**  
Aspiring Data Analyst | Python & Power BI Enthusiast

---

## 📌 Repository Structure

```bash
.
├── Fake_Job_Posting_Detection_Portfolio_Notebook.ipynb
├── fake_job_postings.csv
└── README.md
```

---

⭐ If you found this useful, feel free to star this repo and connect with me on [LinkedIn](https://www.linkedin.com/)!
