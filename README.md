# 🧠 Stroke Prediction Using Machine Learning

Brain stroke is one of the leading causes of death and long-term disability globally, with approximately 13.7 million new cases and 5.5 million deaths each year. Early detection is essential for improving patient outcomes, yet traditional diagnostic methods are often time-consuming, expensive, and require expert medical input.

This project aims to develop an efficient and accessible stroke prediction system using machine learning techniques. It leverages comprehensive patient health data and applies multiple classification algorithms, including:

- Logistic Regression  
- Decision Tree  
- Support Vector Machine (SVM)  
- **Random Forest** ✅ (Best performance)

The **Random Forest model**, enhanced using **SMOTE** (Synthetic Minority Over-sampling Technique) to handle class imbalance, achieved a **92% accuracy** in predicting stroke risk. SMOTE was critical in improving the model’s sensitivity by generating synthetic stroke cases, ensuring balanced predictions.

To bring the model into real-world use, a **Flask-based web application** was developed. This app allows users—both healthcare professionals and the general public—to enter health parameters such as:

- Age  
- Gender  
- Hypertension  
- Heart disease  
- Glucose level  
- BMI  
- Smoking status  
- Work type  
- Marital status  

Upon submission, the app instantly returns whether the user is **“Likely”** or **“Not Likely”** to have a stroke, offering a fast, cost-effective early warning tool.

## 🚀 Features
- Machine Learning model trained on real healthcare data
- SMOTE applied to improve stroke case prediction
- Web interface using Flask for real-time risk assessment
- User-friendly and accessible without medical expertise

## ✅ Goals
- Enable early stroke risk prediction
- Encourage preventive medical action
- Demonstrate the role of AI in accessible healthcare

---

Feel free to fork, contribute, or use this project as a starting point for your own ML healthcare applications!
