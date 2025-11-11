# ❤️ Heart Disease Detection using Machine Learning  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<YOUR-USERNAME>/<YOUR-REPO>/blob/main/heart_disease_detection.ipynb)

---

## 🧠 Project Overview  

Heart disease is one of the leading causes of death worldwide.  
This project uses **supervised machine learning** to predict whether a person has heart disease based on medical attributes such as age, cholesterol level, resting blood pressure, and more.  

The model was trained and evaluated using **Python, Pandas, Scikit-learn, and Seaborn**, achieving high accuracy within a short development cycle — perfect for rapid prototyping and healthcare analytics.

---

## 🩺 Key Features  

✅ Clean data preprocessing pipeline (scaling, splitting, encoding)  
✅ Exploratory Data Analysis (EDA) with visual insights  
✅ Multiple classification algorithms (Logistic Regression & Random Forest)  
✅ Model evaluation with ROC, AUC, and confusion matrix  
✅ Save and reuse model with `pickle`  
✅ Optional extension into Streamlit web app  

---

## 📊 Dataset Information  

- **Source:** UCI Heart Disease Dataset (Cleveland Database)  
- **Rows:** 303  
- **Columns:** 14  
- **Target Variable:** `target` → `1` (Heart Disease) / `0` (No Heart Disease)  
- **Attributes:**  
  `age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal`

---

## ⚙️ Tech Stack  

| Category | Tools / Libraries |
|-----------|------------------|
| Language | Python 3.x |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Plotly |
| Machine Learning | Scikit-learn |
| Model Storage | Pickle |
| Environment | Google Colab / Jupyter Notebook |

---

## 🚀 How to Run the Project (Colab Friendly)  

### **Step 1:** Open the notebook  
Click this badge 👇  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<YOUR-USERNAME>/<YOUR-REPO>/blob/main/heart_disease_detection.ipynb)

---

### **Step 2:** Upload the dataset  
Upload the `heart.csv` file from your local system when prompted:  
```python
from google.colab import files
uploaded = files.upload()
