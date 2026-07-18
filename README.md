# COPD Detection using Machine Learning

An AI-powered web application developed using **Machine Learning** and **Django** to predict the likelihood of **Chronic Obstructive Pulmonary Disease (COPD)** based on patient clinical parameters.

This project demonstrates an end-to-end machine learning workflow, integrating data preprocessing, model training, and a web-based prediction interface to support early disease risk assessment.

---

# 📌 Overview

Chronic Obstructive Pulmonary Disease (COPD) is a progressive respiratory condition that affects millions of people worldwide. Early prediction can help healthcare professionals identify high-risk patients and support timely medical intervention.

This project was developed as an educational healthcare AI application that combines machine learning with a Django-based web interface to generate COPD predictions from patient data.

---

# ✨ Features

- Machine Learning-based COPD prediction
- User-friendly Django web interface
- Patient demographic and clinical data processing
- Data preprocessing and feature engineering
- Model training and evaluation
- Structured project architecture
- Easy-to-extend modular design

---

# 🏗️ System Architecture

```
Patient Clinical Data
          │
          ▼
Data Preprocessing
          │
          ▼
Feature Engineering
          │
          ▼
Machine Learning Model
          │
          ▼
Prediction Engine
          │
          ▼
Django Web Application
          │
          ▼
Prediction Result
```

---

# ⚙️ Tech Stack

### Backend
- Python
- Django

### Machine Learning
- Scikit-learn
- Pandas
- NumPy

### Database
- SQLite

### Visualization
- Matplotlib

### Development
- Git
- VS Code

---

# 📂 Project Structure

```
COPD-Detection-ML
│
├── dataset/
│   ├── PQ_ProcessedData/
│   ├── PQ_RawData/
│   └── COPD_Demographic.csv
│
├── app/
│   └── GUI/
│       ├── basics/
│       ├── GUI/
│       ├── manage.py
│       └── db.sqlite3
│
├── requirements.txt
└── docs/
```

---

# 🔄 Workflow

1. Load patient clinical data
2. Preprocess and clean the dataset
3. Perform feature engineering
4. Train the machine learning model
5. Generate COPD prediction
6. Display prediction through the Django web interface

---

# 📊 Machine Learning Pipeline

- Dataset Collection
- Data Cleaning
- Feature Selection
- Model Training
- Model Evaluation
- COPD Prediction

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/shahanadh-dev/COPD-Detection-ML.git
```

Navigate to the project

```bash
cd COPD-Detection-ML/app/GUI
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the server

```bash
python manage.py runserver
```

Open

```
http://127.0.0.1:8000
```

---

# 📸 Application Preview

Included screenshots (docs/report) of:

- Home Page
- Prediction Form
- Prediction Result
- Model Output
- Data Visualization

---

# 📈 Future Improvements

- Deep Learning models
- Explainable AI (SHAP/LIME)
- REST API using FastAPI
- Docker deployment
- Cloud deployment
- Patient dashboard
- Authentication & user management

---

# ⚠️ Disclaimer

This project was developed for educational and research purposes only. It is not intended to replace professional medical diagnosis or clinical decision-making.

---

# 👨‍💻 Author

**Shahanadh Shah**

Software Engineer | AI/ML Engineer | Generative AI | Backend Developer

- LinkedIn: https://www.linkedin.com/in/shahanadh-shah
- GitHub: https://github.com/shahanadh-dev

---
