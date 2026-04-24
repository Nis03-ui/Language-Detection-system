# 🌍 Language Detection using Machine Learning

A machine learning project that detects the language of a given text using **TF-IDF vectorization** and classification model Random Forest 
---

## 🚀 Project Overview

This project classifies text into multiple languages such as:

* 🇬🇧 English
* 🇫🇷 French
* 🟤 Darija

It uses classical NLP techniques and achieves high accuracy (~96–99%).

---

## 🧠 Tech Stack

* Python 🐍
* Scikit-learn
* Pandas & NumPy
* TF-IDF Vectorization
* Machine Learning Models:

  * Random Forest
 
---

## 📊 Model Performance

* Accuracy: ~96–99%
* Cross-validation score: ~96%
* Evaluation metrics:

  * Precision
  * Recall
  * F1-score
  * Confusion Matrix

---

## 🔄 Workflow

1. Data Collection
2. Text Cleaning (lowercase, remove URLs, punctuation, etc.)
3. Feature Extraction using TF-IDF
4. Model Training
5. Evaluation
6. Prediction on new text

---

## 🧹 Text Preprocessing

* Lowercasing
* Removing URLs
* Removing punctuation & numbers
* Removing stopwords
* Lemmatization (spaCy)

---

## 🧪 How to Run

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 2. Train the model

```bash
python train.py
```

---

### 3. Predict on new text

```python
from model import predict_language

print(predict_language("Bonjour comment ça va"))
```

---

## 📌 Example Prediction

```text
Input: "I love machine learning"
Output: English
```

```text
Input: "Je suis très heureux"
Output: French
```

---

## 📈 Confusion Matrix (Sample)

```
[[841   8  18]
 [  2 833   5]
 [  0   6 918]]
```

---

## 📦 Project Structure

```
language-detection/
│── data/
│── model/
│── notebooks/
│── train.py
│── predict.py
│── preprocessing.py
│── requirements.txt
│── README.md
```

---

## ⚡ Future Improvements

* Use character n-grams for better accuracy
* Try deep learning (LSTM / BERT)
* Deploy using FastAPI or Flask
* Create web UI for live prediction

---

## 👨‍💻 Author

Built by Nishan Bhandari
Passionate about Machine Learning & NLP 🚀

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and contribute!
