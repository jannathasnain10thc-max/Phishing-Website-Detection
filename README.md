# Phishing Website Detection using Random Forest

## 📌 Project Overview
This project focuses on detecting malicious and phishing websites using Machine Learning. Using feature extraction techniques on web metrics (such as SSL certificate state, URL structure, and traffic patterns), a **Random Forest Classifier** was trained to accurately classify URLs as legitimate or phishing.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Machine Learning Library:** Scikit-Learn
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab

---

## 📊 Model Performance & Results
* **Accuracy:** **~97%** overall test accuracy.
* **Precision & Recall:** Balanced precision and recall scores (~0.96 – 0.98) across both legitimate and phishing classes.

### Key Predictive Features
Based on feature importance analysis, the primary indicators for detecting phishing websites are:
1. `SSLfinal_State`: Evaluates HTTPS certificate validity and issuer authority.
2. `URL_of_Anchor`: Evaluates anchor URL tags linking outside the domain.
3. `web_traffic`: Measures domain popularity and traffic volume.

---

## 📁 Repository Structure
```text
├── phishing_detection.ipynb    # Main Google Colab Jupyter Notebook
├── random_forest_model.pkl     # Trained Random Forest model file
├── model_predictions.csv       # Test dataset predictions output
└── README.md                   # Project documentation
