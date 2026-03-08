# 📧 Spam Detection using Naive Bayes (Probability-Based Machine Learning)

A machine learning project that detects **spam vs ham messages** using **Probability Theory and Naive Bayes classification**.
This project demonstrates how **Bayes Theorem and Conditional Probability** from statistics can be applied to solve a real-world problem used by companies like **Google, Microsoft, and Yahoo** in spam filtering systems.

---

## 🚀 Project Overview

Spam messages are a major challenge in communication platforms.
This project builds a **probabilistic machine learning model** that learns patterns from labeled text messages and predicts whether a new message is **Spam or Not Spam**.

The model uses:

* **Probability Theory**
* **Bayes Theorem**
* **Conditional Probability**
* **Naive Bayes Classifier**
* **Natural Language Processing (NLP)**

---

## 🧠 Mathematical Foundation

This project is based on **Bayes Theorem**:

P(Spam | Message) = (P(Message | Spam) × P(Spam)) / P(Message)

The Naive Bayes model assumes **independence of words**, allowing efficient computation of probabilities.

Concepts used:

* Probability
* Conditional Probability
* Bayes Theorem
* Independence assumption
* Likelihood estimation

These concepts come from **Probability and Distribution Models**.

---


## 📊 Dataset

The dataset contains **1000 labeled SMS messages**.

Columns:

| Column  | Description |
| ------- | ----------- |
| label   | spam or ham |
| message | SMS text    |

Example:

| label | message                                |
| ----- | -------------------------------------- |
| spam  | Congratulations! You won a FREE iPhone |
| ham   | Let's meet tomorrow for lunch          |

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* Scikit-learn
* Natural Language Processing
* Count Vectorizer

---

## 🔬 Machine Learning Pipeline

1️⃣ Data Loading
2️⃣ Text Preprocessing
3️⃣ Feature Extraction (Bag of Words)
4️⃣ Train/Test Split
5️⃣ Naive Bayes Training
6️⃣ Model Evaluation

Pipeline:

```
Email/Text
   ↓
Text Cleaning
   ↓
Feature Extraction
   ↓
Naive Bayes Model
   ↓
Spam / Not Spam
```

---

## 🧪 Model Training

The model is trained using **Multinomial Naive Bayes**.

```
from sklearn.naive_bayes import MultinomialNB
model = MultinomialNB()
model.fit(X_train, y_train)
```

---

## 📈 Model Performance

Evaluation metrics used:

* Accuracy
* Confusion Matrix
* Precision
* Recall

Typical accuracy:

**95% – 98%**

---

## 🧩 Example Prediction

Input message:

```
Congratulations! You won a FREE gift card
```

Prediction:

```
Spam
```

---

## 🏢 Real-World Applications

This project demonstrates techniques used in:

* Gmail Spam Filter
* Outlook Spam Detection
* Fraud Detection Systems
* Email Security Systems
* Message Moderation Systems

---

## 💡 Skills Demonstrated

* Probability and Statistics
* Machine Learning Classification
* Natural Language Processing
* Data Preprocessing
* Model Evaluation
* Real-world ML pipeline

---


## 🔮 Future Improvements

* TF-IDF vectorization
* Logistic Regression classifier
* Deep Learning models
* Real-time spam detection API
* Web application deployment

---

## 👨‍💻 Author

**Balaji Anwane**

M.Sc Data Science Student
Interested in Machine Learning, AI, and Data Analytics.

---

## ⭐ If you like this project

Give it a **star on GitHub ⭐** to support the project.
