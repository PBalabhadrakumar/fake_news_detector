# 📰 Fake News Detector

An AI-powered fake news detection system built using Python, Flask (backend), and machine learning. It classifies news articles or headlines as **Real** or **Fake** using NLP and a trained model on labeled datasets.

---

## 📌 Overview

The rise of misinformation demands smart solutions. This project uses **Natural Language Processing (NLP)** and **machine learning** to detect fake news based on textual data. It provides a backend-powered web interface for users to input news and receive predictions instantly.

---

## 🎯 Key Features

- ✅ Detects if a news article or headline is real or fake
- ⚙️ Powered by a trained ML model using labeled news datasets
- 🔗 Backend built with Python and Flask
- 📊 Preprocessing includes stopword removal, TF-IDF vectorization
- 🧠 Trained on real-world data from Kaggle

---

## 🧠 Technologies Used

- **Language:** Python
- **Backend:** Flask
- **Libraries:** scikit-learn, pandas, NumPy, NLTK
- **Model:** Logistic Regression / Naive Bayes
- **Dataset:** [Kaggle - Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

---

## 📂 Project Structure
📁 fake-news-detector/
│
├── app.py # Flask backend logic
├── templates/
│ └── index.html # Frontend page
├── static/
│ └── style.css # Styling (if used)
├── model/
│ └── model.pkl # Trained ML model
├── data/
│ └── news.csv # Dataset used for training
├── training/
│ └── train_model.py # Script to train and save model
├── requirements.txt # Required Python packages
└── README.md


---

## 🚀 How to Run Locally

1. **Clone this repository:**
   ```bash
   git clone https://github.com/your-username/fake-news-detector.git
   cd fake-news-detector



