# Diabetes-Prediction


## 📌 **Project Overview**  
This project predicts whether a person is diabetic or not using a Support Vector Machine (SVM) classifier based on health data. The dataset used is the **Diabetes.csv** file.

---

## 🚀 **Technologies Used**  
- Python  
- NumPy  
- Pandas  
- scikit-learn (SVM, StandardScaler, train_test_split)  
- Jupyter Notebook  

---

## 📂 **Dataset**  
- The dataset contains health-related information:  
  - Pregnancies  
  - Glucose  
  - Blood Pressure  
  - Skin Thickness  
  - Insulin  
  - BMI  
  - Diabetes Pedigree Function  
  - Age  
  - Outcome (Target variable)  

---

## 📊 **Project Workflow**  
1. Import libraries  
2. Load the dataset  
3. Data preprocessing  
   - Handle missing values  
   - Standardize the data  
4. Split data into training and testing sets  
5. Train the SVM classifier  
6. Evaluate model performance using accuracy score  
7. Predict outcome for new input data  

---

## 🎯 **Prediction Example**  
```python
input_data = (4,154,62,31,284,32.8,0.237,23)
```
- **Output:**  
✅ The person is diabetic OR ❌ The person is not diabetic  

