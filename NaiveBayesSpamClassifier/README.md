# 📧 Naive Bayes Spam Classifier

A machine learning project to classify emails as **Spam** or **Ham** using a custom implementation of the **Naive Bayes algorithm** in Python.  
This project demonstrates text preprocessing, vocabulary building, probability estimation, and classification without relying on external ML libraries.

---

## 📌 Project Overview
- **Goal:** Detect spam emails using probabilistic text classification.
- **Dataset:** [Spam/Ham Dataset](https://raw.githubusercontent.com/saivivekreddydevaram/ML-PROJECTS/refs/heads/main/NaiveBayesSpamClassifier/spam_ham_dataset.csv)
- **Approach:** 
  1. Text preprocessing with regex.
  2. Vocabulary creation from training data.
  3. Word frequency counting for spam vs ham.
  4. Probability estimation using Laplace smoothing.
  5. Classification based on log likelihood scores.

---

## 🛠️ Tech Stack
- **Python** (NumPy, Pandas, Matplotlib, re)
- **Custom Naive Bayes Implementation** (no scikit-learn used)
- **Dataset Handling:** Pandas
- **Visualization:** Matplotlib (optional)

---

## ⚙️ Workflow
1. **Data Loading:** Import dataset using Pandas.
2. **Preprocessing:**  
   - Lowercasing  
   - Removing digits, punctuation, and special characters (`\n`, `\r`, `\\`)  
   - Tokenization  
3. **Vocabulary Building:** Create a dictionary of unique words.  
4. **Training:** Count word frequencies for spam and ham, compute conditional probabilities.  
5. **Prediction:** Calculate log likelihood scores for test emails.  
6. **Evaluation:** Compare predictions with ground truth, compute accuracy.

---

## 📊 Results
- **Accuracy Achieved:** `98.16%`  
- **Evaluation Metric:** Accuracy (with potential extension to Precision, Recall, F1-score).

---

