<div align="center">

# 💬 SentiScope AI
### 🚀 Intelligent Sentiment Analysis Platform

<p align="center">
AI-powered sentiment analysis system that understands emotions from text using Machine Learning and Natural Language Processing (NLP).
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-Backend-000000?style=for-the-badge&logo=flask)
![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react)
![Vite](https://img.shields.io/badge/Vite-Frontend-646CFF?style=for-the-badge&logo=vite)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikitlearn)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

<p align="center">

⭐ Machine Learning • NLP • Interactive Dashboard • Modern UI ⭐

</p>

---

</div>

# 📖 Overview

**SentiScope AI** is a modern Machine Learning based Sentiment Analysis platform capable of detecting emotions from any text input.

The application processes text through an NLP pipeline, transforms it using TF-IDF vectorization, and predicts whether the sentiment is:

- 😊 Positive
- 😐 Neutral
- 😔 Negative

The project combines **Machine Learning**, **Natural Language Processing**, and a **beautiful React dashboard** to provide both accurate predictions and meaningful visual analytics.

---

# ✨ Features

## 🤖 AI & Machine Learning

- Text Sentiment Prediction
- Positive / Negative / Neutral Detection
- Confidence Score
- Probability Distribution
- TF-IDF Feature Extraction
- Multiple ML Models
- Automatic Best Model Selection
- Model Accuracy Comparison

---

## 🧠 NLP Pipeline

- Lowercase Conversion
- Tokenization
- Stopword Removal
- Lemmatization
- URL Removal
- Emoji Removal
- HTML Cleaning
- Number Removal
- Punctuation Removal

---

## 📊 Analytics Dashboard

- Total Predictions
- Positive Count
- Negative Count
- Neutral Count
- Average Confidence
- Prediction Timeline
- Pie Chart
- Line Chart
- Bar Graph
- History Table

---

## 🌐 Web Application

- Responsive Design
- Glassmorphism UI
- Dark Mode
- Light Mode
- Beautiful Animations
- Mobile Friendly
- Smooth Page Transitions
- Loading Animations
- Skeleton Loader
- Toast Notifications

---

## 📁 History Management

- Save Predictions
- Delete Prediction
- Search History
- Filter History
- Export CSV
- Export PDF

---

## 🔒 Security

- Input Validation
- Secure API
- Error Handling
- Sanitized User Input
- REST Architecture

---

# 🏗️ Project Architecture

```
                    User
                      │
                      ▼
             React Frontend
                      │
          REST API (Axios)
                      │
                      ▼
               Flask Backend
                      │
        Text Preprocessing (NLP)
                      │
                      ▼
            TF-IDF Vectorizer
                      │
                      ▼
        Trained Machine Learning Model
                      │
                      ▼
           Prediction & Confidence
                      │
                      ▼
            SQLite / MongoDB
```

---

# ⚙️ Tech Stack

## Frontend

- React
- Vite
- Tailwind CSS
- Framer Motion
- Axios
- React Router
- Chart.js
- Lucide Icons

---

## Backend

- Python
- Flask
- REST API
- Flask CORS

---

## Machine Learning

- Scikit-Learn
- Pandas
- NumPy
- NLTK
- TextBlob
- Joblib
- TF-IDF Vectorizer

---

## Models

- Logistic Regression
- Naive Bayes
- Linear SVM

---

## Database

- SQLite

or

- MongoDB

---

# 📂 Folder Structure

```
SentiScope-AI/

│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── dataset/
│   ├── model/
│   ├── api/
│   ├── utils/
│   ├── app.py
│   ├── requirements.txt
│   └── database.db
│
├── trained_model.pkl
├── vectorizer.pkl
├── README.md
└── LICENSE
```

---

# 📈 Machine Learning Workflow

```
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Text Preprocessing
    │
    ▼
Tokenization
    │
    ▼
Stopword Removal
    │
    ▼
Lemmatization
    │
    ▼
TF-IDF Vectorization
    │
    ▼
Model Training
    │
    ▼
Evaluation
    │
    ▼
Save Model
    │
    ▼
Prediction API
```

---

# 🌐 REST API

## Predict Sentiment

```
POST /predict
```

Example

```json
{
"text":"I love this project!"
}
```

Response

```json
{
"sentiment":"Positive",
"confidence":98.64
}
```

---

## History

```
GET /history
```

---

## Statistics

```
GET /statistics
```

---

## Delete History

```
DELETE /history
```

---

# 📊 Dashboard Includes

✅ Total Predictions

✅ Positive %

✅ Negative %

✅ Neutral %

✅ Accuracy

✅ Prediction Timeline

✅ Confidence Distribution

✅ Recent Activity

---

# 🎯 Future Improvements

- Deep Learning Model
- BERT Integration
- RoBERTa Model
- Multilingual Analysis
- Voice Sentiment Analysis
- Speech Emotion Recognition
- Image Caption Sentiment
- Live Twitter Analysis
- WhatsApp Chat Analyzer
- Telegram Integration
- Cloud Deployment

---

# 📸 Screenshots

```
📷 Home Page

(Add Screenshot)

```

---

```
📷 Prediction Page

(Add Screenshot)

```

---

```
📷 Analytics Dashboard

(Add Screenshot)

```

---

```
📷 History

(Add Screenshot)

```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/SentiScope-AI.git
```

---

## Backend

```bash
cd backend

pip install -r requirements.txt

python app.py
```

---

## Frontend

```bash
cd frontend

npm install

npm run dev
```

---

# 🎓 Educational Purpose

This project demonstrates practical implementation of

- Machine Learning
- Natural Language Processing
- Flask REST APIs
- React Development
- Dashboard Design
- Data Visualization
- Model Deployment

making it ideal for:

- Final Year Project
- College Demonstration
- Portfolio
- Resume
- Hackathons

---

# 👨‍💻 Developed By

**Satyajit Pratihar**

> *"Transforming human emotions into meaningful insights through Artificial Intelligence."*

---

<div align="center">

### ⭐ If you like this project, consider giving it a Star ⭐

Made with ❤️ using Machine Learning, NLP, React & Flask

</div>
