# 🧠 Quora Duplicate Question Detection using BoW & Random Forest

This project identifies whether a pair of questions from the Quora Question Pairs dataset are duplicates. It uses classic NLP techniques, specifically **Bag of Words (BoW)** for text representation and a **Random Forest Classifier** for prediction.

---

## 📂 Dataset

- **Source**: [Quora Question Pairs Dataset on Kaggle](https://www.kaggle.com/competitions/quora-question-pairs/data)
- **Columns**:
  - `id`: Unique ID for the question pair
  - `qid1`, `qid2`: Unique IDs for each question
  - `question1`, `question2`: Actual questions
  - `is_duplicate`: Label (1 = duplicate, 0 = not duplicate)

---

## 🏗️ Project Structure

```bash
quora-duplicate-detection/
├── data/
│   └── train.csv                  # Quora training dataset
│
├── notebooks/
│   └── duplicate_que_identify_project.ipynb         # Main Jupyter Notebook
│
├── models/
│   └── dup_que_iden_model.pkl    # Saved Random Forest model
│
└── README.md                      # This file


```
## ✅ Key Features

- Trained on **250,000+** diverse question samples
- Achieves **~80% accuracy** on evaluation datasets
- Supports preprocessing, training and evaluation
