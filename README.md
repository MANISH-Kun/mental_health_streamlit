# 🧠 Mental Health Analysis & Prediction App

<p align="center">
  <img src="https://img.shields.io/badge/Streamlit-App-red?style=for-the-badge&logo=streamlit">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green?style=for-the-badge">
</p>

---

## 📌 Overview

This project is a **Machine Learning-powered web application** built using **Streamlit** that analyzes mental health data and predicts outcomes based on user inputs.

It combines **data analysis, visualization, and predictive modeling** into an interactive web interface.

---

## 🚀 Live Demo
👉 *(Add your Streamlit Cloud link here once deployed)*

---

## ✨ Features

- 📊 Interactive data visualizations  
- 🤖 Machine Learning prediction (Random Forest)  
- ⚡ Real-time user input analysis  
- 🎯 Clean and modern UI with Streamlit  
- 📁 Pre-trained model integration using `.joblib`  

---

## 🛠️ Tech Stack

| Category        | Tools Used |
|----------------|-----------|
| Language        | Python 🐍 |
| Framework       | Streamlit |
| ML Algorithm    | Random Forest |
| Libraries       | Pandas, NumPy, Scikit-learn |
| Visualization   | Matplotlib, Seaborn |

---

## 📂 Project Structure
- app.py → Main Streamlit app
- requirements.txt → Dependencies
- *.joblib → Trained ML model & features
- dataset files → CSV data

## 🧪 Using Virtual Environment (Recommended)

It is recommended to use a virtual environment to avoid dependency conflicts.

### ▶️ Steps (Windows)

```bash
# Create virtual environment
python -m venv venv

# Activate it
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py