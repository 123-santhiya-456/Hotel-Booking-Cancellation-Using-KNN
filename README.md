# 🏨 Hotel Booking Cancellation Prediction using KNN

## 📌 Project Overview
This project focuses on predicting whether a hotel booking will be **cancelled or not** using the **K-Nearest Neighbors (KNN)** machine learning algorithm.  
The goal is to help hotels understand booking patterns and reduce revenue loss due to cancellations.

---

## 🎯 Objective
- Analyze hotel booking data
- Perform Exploratory Data Analysis (EDA)
- Preprocess and clean the dataset
- Build a KNN classification model
- Evaluate model performance using standard metrics

---

## 📂 Dataset
- **Dataset Name:** Hotel Booking Demand
- **Source:** Kaggle
- **Description:**  
  The dataset contains booking information for a city hotel and a resort hotel, including:
  - Booking dates
  - Length of stay
  - Number of guests
  - Meal type
  - Market segment
  - Booking cancellation status

**Target Variable:**  
- `is_canceled`  
  - `1` → Booking Cancelled  
  - `0` → Booking Not Cancelled  

---

## 🛠️ Technologies Used
- **Programming Language:** Python  
- **Libraries:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

---

## 🔍 Project Workflow
1. Data Loading
2. Data Understanding
3. Exploratory Data Analysis (EDA)
4. Data Cleaning
5. Encoding Categorical Features
6. Feature Scaling
7. Train-Test Split
8. KNN Model Training
9. Model Evaluation
10. Conclusion

---

## ⚙️ Model Used
### K-Nearest Neighbors (KNN)
- A distance-based supervised learning algorithm
- Requires feature scaling for better performance
- Classifies a data point based on majority vote of nearest neighbors

---

## 📊 Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-score

---

## 📈 Results
The KNN model achieved satisfactory accuracy in predicting booking cancellations.  
Proper preprocessing and feature scaling significantly improved model performance.

---

## ✅ Conclusion
This project demonstrates how machine learning can be applied to real-world hospitality data to predict booking cancellations.  
The KNN algorithm performed well after normalization, proving the importance of preprocessing for distance-based models.

---

## 🚀 Future Improvements
- Hyperparameter tuning for optimal `K` value
- Comparison with other algorithms (Logistic Regression, Naive Bayes)
- Feature selection techniques
- Deployment using Streamlit

---

## 📌 Author
**Daisy**  
B.Tech – Artificial Intelligence & Data Science  

---

## 📜 License
This project is for educational purposes.
