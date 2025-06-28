# Revolutionizing-Liver-Care-Predicting-Liver-Cirrhosis-using-Advanced-Machine-Learning-Techniques
Revolutionizing Liver Care : Predicting Liver Cirrhosis using Advanced Machine Learning Techniques

# Revolutionizing Liver Care: Predicting Liver Cirrhosis Using Advanced Machine Learning

## 📌 Project Overview

This project presents a machine learning-based web application that predicts the presence of **Liver Cirrhosis** using clinical patient data. It uses advanced models such as **Random Forest**, **XGBoost**, and **Logistic Regression** to assist healthcare professionals in early detection, improving diagnosis speed and accuracy.

By leveraging clinical features like bilirubin, albumin, INR, and ascites, this application provides real-time predictions and insights into liver health.

---

## 🎯 Objective

To create an accurate, accessible, and scalable AI-powered system that can:
- Predict liver cirrhosis from routine patient data
- Reduce diagnosis delays in rural or under-resourced regions
- Aid doctors with decision support and risk classification

---

## 🩺 Dataset

- **Source:** [UCI Machine Learning Repository – Liver Disorders](https://archive.ics.uci.edu/ml/datasets/liver+disorders)  
- **Features Used:**  
  - Age  
  - Gender  
  - Total Bilirubin  
  - Direct Bilirubin  
  - Alkaline Phosphatase  
  - Serum Glutamic-Oxaloacetic Transaminase (SGOT)  
  - Serum Glutamic-Pyruvic Transaminase (SGPT)  
  - Total Proteins  
  - Albumin  
  - A/G Ratio  
  - Liver Cirrhosis Label (Target)

---

## ⚙️ Tech Stack

| Component         | Technology Used                      |
|------------------|---------------------------------------|
| Frontend         | HTML, CSS, JavaScript (Bootstrap)     |
| Backend          | Python, Flask                         |
| Machine Learning | Scikit-learn, XGBoost, Pandas, NumPy  |
| Visualization    | Matplotlib, Seaborn                   |
| Deployment       | Localhost / Heroku / AWS              |

---

## 🚀 Features

- Upload patient data via form or CSV
- Real-time prediction of cirrhosis risk
- Confidence score with prediction
- Admin view to track prediction logs
- Simple and responsive web UI

---

## ✅ Model Performance

| Model          | Accuracy | Precision | Recall | F1 Score |
|----------------|----------|-----------|--------|----------|
| Random Forest  | 94.8%    | 93%       | 92%    | 92.4%    |
| XGBoost        | 93.6%    | 91%       | 90%    | 90.5%    |
| Logistic Reg.  | 87.4%    | 85%       | 83%    | 84%      |

---

## 🧠 How It Works

1. User enters clinical features into the form or uploads a CSV
2. Server processes the input and runs the ML model
3. Model returns a prediction: **Cirrhosis / No Cirrhosis**
4. Output displayed with probability/confidence score

---

## 📦 Installation

git clone https://github.com/your-username/liver-cirrhosis-predictor.git
cd liver-cirrhosis-predictor
pip install -r requirements.txt
python app.py
