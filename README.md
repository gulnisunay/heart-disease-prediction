# Heart Disease Prediction - Logistic Regression Project

This repository contains a **Machine Learning** project that applies **Logistic Regression** to predict heart disease based on patient health data.

## Project Overview
The goal of this project is to build a **classification model**, optimize it using **Grid Search**, and evaluate its performance on a test dataset. The dataset used in this project includes various health indicators, with **target (0 = No Heart Disease, 1 = Heart Disease)** as the outcome variable.

### Key Steps in the Project
1. **Setting up the workspace**  
   - Created a GitHub repository  
   - Ignored unnecessary files using `.gitignore`  
   - Managed dependencies with `environment.yml`  

2. **Data Preparation & Preprocessing**  
   - Loaded the heart disease dataset  
   - Split data into **X (features) and y (target variable)**  
   - Scaled features using `StandardScaler`  

3. **Model Selection & Optimization**  
   - Used **Logistic Regression** for classification  
   - Tuned hyperparameter **C-value** using **GridSearchCV**  

4. **Model Evaluation**  
   - Evaluated on **10% unseen test data**  
   - Performance metrics:  
     - **Accuracy**: ~85%  
     - **Confusion Matrix**  
     - **Precision-Recall Curve**  
     - **ROC Curve**  

---

## Setup & Installation
To run this project on your machine, follow these steps:

### Clone the Repository
```bash
git clone https://github.com/gulnisunay/heart-disease-prediction.git
cd heart-disease-prediction
