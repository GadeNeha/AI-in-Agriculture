# 🌾 AI in Agriculture

An end-to-end Artificial Intelligence based system designed to assist farmers and agricultural stakeholders with **crop recommendation**, **fertilizer suggestion**, and **plant disease detection** using Machine Learning and Deep Learning techniques.

This project integrates trained ML/DL models with a **Flask-based web application** to provide an easy-to-use interface for real-world agricultural decision support.

---

## 📌 Project Overview

Agriculture faces challenges such as improper crop selection, incorrect fertilizer usage, and late detection of plant diseases.  
This project aims to solve these problems by providing:

- ✅ Crop recommendation based on soil and environmental parameters  
- ✅ Fertilizer suggestion using nutrient values (N, P, K)  
- ✅ Plant disease detection from leaf images using deep learning  

---

## 🧠 Modules Implemented

### 1️⃣ Crop Recommendation System
- Inputs: Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, Rainfall
- Algorithms used:
  - Decision Tree
  - Random Forest
  - Naive Bayes
  - XGBoost
- Output: Most suitable crop for given conditions

---

### 2️⃣ Fertilizer Suggestion System
- Inputs: Crop name and soil nutrient values (N, P, K)
- Logic:
  - Compares required vs available nutrients
- Output:
  - Recommended fertilizer and corrective suggestion

---

### 3️⃣ Plant Disease Detection System
- Input: Leaf image uploaded by the user
- Model:
  - Deep Learning (CNN-based, PyTorch)
- Dataset:
  - PlantVillage Dataset
- Output:
  - Disease name and related information

---

## 🖥️ Web Application

The project includes a **Flask web interface** that allows users to interact with all modules easily.

### Key Features:
- User-friendly UI
- Separate pages for each module
- Image upload for disease detection
- Dynamic result display

---

