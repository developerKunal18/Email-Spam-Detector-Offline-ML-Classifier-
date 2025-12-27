# 🕵️‍♂️ Email Spam Detector —

## 💡 Overview
The **Email Spam Detector** is an offline Python application that uses **Machine Learning** to classify messages as **Spam** or **Ham (Not Spam)**.

It works by training a text classification model using **TF-IDF vectorization** and a **Naive Bayes classifier**, similar to how real-world email spam filters operate.

---

## 🚀 Features

### 📩 Spam Detection
- Classifies messages as:
  - **SPAM 🚨**
  - **HAM ✅**

### 🧠 Machine Learning Model
- Uses **Naive Bayes** for text classification
- Converts text into numerical features using **TF-IDF**

### 📊 Confidence Score
- Displays how confident the model is about its prediction

### 💾 Model Persistence
- Saves the trained model to disk (`spam_model.pkl`)
- Reuses the model for future predictions

### 🌐 Fully Offline
- No APIs
- No internet
- No cloud services

---

## 🧠 Concepts & Technologies Used
- Python
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Naive Bayes Classifier
- Pickle model storage
- Text classification
- Cybersecurity & spam filtering logic

---

## 📦 Installation

### Install dependency:
```bash
pip install scikit-learn
