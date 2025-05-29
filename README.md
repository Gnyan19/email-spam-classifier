<p align="center">
  <img src="https://img.shields.io/badge/Project-Email%20Spam%20Classifier-brightgreen?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/NLP-Scikit--Learn-orange?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Language-Python-blue?style=for-the-badge&logo=python&logoColor=white" />
</p>

<h1 align="center">📧 Email Spam Classifier</h1>

<p align="center">
An AI-based text classifier using NLP & Python that distinguishes between spam and non-spam messages. Built for real-world applications like email filtering and fraud detection.
</p>

---

## 🚀 Features
- Preprocessing and vectorizing text data using `CountVectorizer`
- Binary classification using `Multinomial Naive Bayes`
- Accuracy and performance metrics
- Custom input prediction support
- Model saving using Pickle

---

## 🧠 Technologies Used
- Python
- Pandas
- Scikit-learn
- Natural Language Processing (NLP)
- CountVectorizer
- Jupyter / Google Colab

---

## 📁 Dataset
Dataset used: [UCI SMS Spam Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)

Loaded via raw URL:
```python
https://raw.githubusercontent.com/justmarkham/pycon-2016-tutorial/master/data/sms.tsv
```

---

## 🧪 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/email-spam-classifier.git
cd email-spam-classifier
```

### 2. Run in Google Colab
- Open [https://colab.research.google.com](https://colab.research.google.com)
- Upload your `.ipynb` file or paste the code.

### 3. Or run locally
```bash
pip install pandas scikit-learn matplotlib seaborn
python spam_classifier.py
```

---

## 🔮 Predict Your Own Message
```python
print(predict_spam("Congratulations! You've won a free ticket!"))
```

---

## 🧊 Model Export
- `spam_model.pkl` – Trained classifier
- `vectorizer.pkl` – Fitted CountVectorizer

Use these to deploy in web apps or Flask/Django APIs.

---

## 🧑‍💻 Author
Built by Gnyanprakhash as part of an AI/Python Internship application.

---

## 📜 License
MIT License – feel free to use or modify.
