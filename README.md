
```markdown
# 📩 SMS Spam Detection 🚀

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![ML](https://img.shields.io/badge/Machine%20Learning-Naive%20Bayes-orange)
![NLP](https://img.shields.io/badge/NLP-TFIDF-green)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Accuracy](https://img.shields.io/badge/Accuracy-98.76%25-brightgreen)

---

## 🧠 Overview
This project is a **Machine Learning-based SMS Spam Classifier** that detects whether a message is **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques.

It uses **TF-IDF Vectorization** and a **Multinomial Naive Bayes model** to achieve high performance.

> 🎯 **Model Accuracy: 98.76%**

---

## 🎬 Demo

![Demo](https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif)

**Example Predictions:**
- 📩 *"Congratulations! You've won a free prize"* → 🚨 **Spam**
- 📩 *"Hey, are we still meeting today?"* → ✅ **Ham**

---

## ✨ Features
- 🔍 Text preprocessing using NLP techniques  
- 📊 TF-IDF feature extraction  
- ⚡ Fast and efficient Naive Bayes model  
- 🎯 High accuracy classification  
- 🧪 Easy to extend and deploy  

---


---

## ⚙️ Tech Stack
- Python 🐍  
- NumPy  
- Pandas  
- NLTK  
- Scikit-learn  

---

## 🔍 Data Preprocessing Pipeline

The dataset is cleaned and processed using the following steps:

1. Convert text to lowercase  
2. Remove punctuation  
3. Remove digits  
4. Tokenization  
5. Stopword removal  
6. Lemmatization  
7. Rejoin tokens into cleaned text  

---

## 🧠 Model Details

| Component        | Technique                  |
|-----------------|--------------------------|
| Feature Engine  | TF-IDF Vectorizer        |
| Model           | Multinomial Naive Bayes  |
| Train/Test Split| 80 / 20                  |
| Accuracy        | **98.76%**               |

---

## ▶️ Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/sms-spam-detection.git
cd sms-spam-detection
````

---

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 3️⃣ Run Training

```bash
python src/train.py
```

---

### 4️⃣ Predict Custom Message

```bash
python src/predict.py
```

---

## 📊 Example Usage

```python
message = "Congratulations! You've won a free ticket"
prediction = model.predict([message])

if prediction[0] == 1:
    print("Spam 🚨")
else:
    print("Ham ✅")
```

---

## 📌 Future Improvements

* 🤖 Deep Learning models (LSTM / Transformers)
* 🌐 Deploy as API (Flask / FastAPI)
* 📱 Real-time SMS filtering system
* 📊 Improve feature engineering

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👤 Author

**Adarsh**
🚀 Building AI systems to solve real-world problems

