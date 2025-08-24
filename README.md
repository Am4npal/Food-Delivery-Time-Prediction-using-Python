# 🍴 Food Delivery Time Prediction – Zomato & Swiggy  

## 📌 Overview  
This project focuses on predicting **food delivery times** for services like **Zomato and Swiggy** using Machine Learning. The goal is to provide accurate delivery estimates by analyzing past delivery data, distances, and delivery partner characteristics, ensuring transparency and better customer satisfaction.  

---

## ❗ Problem Statement  

1. Food delivery apps often struggle to provide **accurate delivery time estimates**.  
2. Customers may lose trust when delivery times are longer than shown.  
3. Delivery times depend on multiple factors such as **distance, delivery partner’s age, and ratings**.  
4. There is a need for a **data-driven, machine learning approach** to predict delivery times in real-time.  

---

## 🧰 Tech Stack & Tools  

**Languages & Frameworks:**  
- Python  

**Libraries:**  
- `pandas` – Data manipulation  
- `numpy` – Numerical computations  
- `plotly` – Interactive visualizations  
- `scikit-learn` – Preprocessing and metrics  
- `TensorFlow / Keras` – For LSTM Neural Network  

**Tools:**  
- Jupyter Notebook  
- Git & GitHub  

---

## 🔍 Project Workflow  

### 1. Distance Calculation  
- The dataset does not directly provide the distance between restaurant and customer.  
- Used the **Haversine Formula** to calculate the distance from latitude and longitude values.  

### 2. Data Exploration (EDA)  
- Explored relationships between:  
  - Distance and delivery time  
  - Delivery partner’s age and delivery time  
  - Delivery partner’s ratings and delivery time  

### 3. Feature Engineering  
- Created a new **distance feature** (restaurant → delivery location).  
- Selected most important features:  
  - Age of delivery partner  
  - Ratings of delivery partner  
  - Distance between restaurant and delivery location  

### 4. Model Building  
- Built an **LSTM Neural Network Model** to predict delivery time.  
- Trained on historical delivery data.  

### 5. Prediction  
- Given new orders, the model predicts the **expected delivery time** in real time.  

---

## 📊 Visualizations  
- 📈 Scatter Plot: Distance vs. Delivery Time  
- 📦 Box Plot: Type of vehicle vs. Delivery Time  
- 📉 Scatter Plot : Delivery Time vs. Rating   

---

## 💡 Key Insights  

- 📍 **Distance** is the most significant factor affecting delivery time.  
- 👨‍🍳 **Age & Ratings of delivery partners** also influence time efficiency.  
- 📊 Machine Learning (LSTM) can capture **non-linear dependencies** and improve prediction accuracy.  
- 🚀 Provides a foundation for **real-time delivery time predictions** in food delivery apps.  

---

## 📎 Future Scope  
- Include features like **traffic conditions, weather, and restaurant preparation time**.  
- Test additional ML models like **XGBoost, Random Forest** for comparison.  
- Deploy as an **API** for real-time prediction in apps.  

---

## 👥 Project Members  

- **AMAN PAL** – Data Cleaning, EDA, Model Training & Documentation  

---
