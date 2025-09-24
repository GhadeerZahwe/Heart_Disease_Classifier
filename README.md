# Heart Disease Classification

A machine learning project that predicts the presence of heart disease using patient health data.  
This repository demonstrates a full ML workflow — from data preprocessing to model evaluation and saving.

---

## Project Overview

The goal is to build a **binary classifier** that predicts whether a patient has heart disease.  

### Key Steps:
- Data loading & preprocessing  
- Exploratory Data Analysis (EDA) with Matplotlib & Seaborn  
- Train/Test Split for unbiased evaluation  
- Model Training: Random Forest & Logistic Regression  
- Hyperparameter Tuning with RandomizedSearchCV  
- Performance Evaluation: precision, recall, F1-score, confusion matrix, classification report  
- Model Saving using Joblib  

This project is designed to be beginner-friendly for anyone learning supervised ML in Python.

---

## Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/heart-disease-classifier.git
cd heart-disease-classifier
```
### 2. Create & activate a virtual environment
```bash
python -m venv heart
# On Linux/Mac
source heart/bin/activate
# On Windows (PowerShell)
.\heart\Scripts\activate
```
### 3. Install dependencies
```bash
pip install -r requirements.txt
```

