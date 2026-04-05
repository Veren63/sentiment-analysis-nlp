# 🚀 Sentiment Analysis NLP

## 📌 Overview
Project ini bertujuan untuk mengklasifikasikan sentimen teks menjadi positif atau negatif menggunakan Natural Language Processing.

## 🛠️ Tech Stack
- Python
- Pandas
- Scikit-learn
- NLTK

## 🚀 Project Highlights
- Built end-to-end NLP pipeline
- Performed text preprocessing and feature engineering
- Compared multiple models (Logistic Regression vs Naive Bayes)
- Achieved ~89.5% accuracy
  
## 🧠 Model
- TF-IDF (ngram 1–2)
- Logistic Regression

## 📊 Hasil
- Accuracy: 89.54%

## ⚙️ Fitur
- Text preprocessing
- Model training
- Evaluasi
- Prediksi input manual (interactive mode)

## 💡 Insight
Eksperimen menunjukkan bahwa n-gram yang lebih besar tidak selalu meningkatkan performa.

## ▶️ Cara menjalankan
```bash
pip install -r requirements.txt
python app.py

**## 📷 Contoh Output**

Input:
"This product is amazing"

Output:
Positive 😊

Input:
"This is terrible"

Output:
Negative 😡
