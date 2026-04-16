
# 🌿 Plant Leaf Disease Detector

## 📌 Overview
This project is a deep learning-based web application that detects plant leaf diseases from images.  
It helps farmers and researchers identify diseases early and take preventive measures.

---

## 🚀 Features
- Upload leaf images and get instant predictions  
- Supports 38 different classes  
- Detects multiple plant diseases (Tomato, Potato, Apple, Grape, etc.)  
- Shows prediction with confidence score  
- Simple and interactive UI using Streamlit  

---

## 🧠 Model Details
- Built using Convolutional Neural Network (CNN)  
- Custom architecture with:
  - Depthwise Convolutions  
  - MaxPooling  
  - Global Average Pooling  

**Accuracy:**
- Training Accuracy: ~94%  
- Validation Accuracy: ~90%  

---

## 📂 Dataset
Dataset used for training:

👉 https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

Includes plant leaves of:
- Tomato  
- Potato  
- Apple  
- Corn  
- Grape  
- Pepper  

---

## 🛠️ Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy  
- PIL  
- Streamlit  

---

## ⚙️ How to Run

```bash
pip install -r requirements.txt
python -m streamlit run app.py
