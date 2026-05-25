# 🩺 Diabetes Prediction Using Support Vector Machine (SVM)

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-blue?style=for-the-badge&logo=numpy)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)

---

# 📌 Project Overview

This project predicts whether a patient is **Diabetic** or **Non-Diabetic** using a **Support Vector Machine (SVM)** Machine Learning model.

The model is trained using the **PIMA Indians Diabetes Dataset** and includes:

✅ Data Preprocessing  
✅ Feature Scaling  
✅ Model Training  
✅ Accuracy Evaluation  
✅ Real-Time Prediction  

---

# 🧠 Machine Learning Workflow

```text
Dataset
   ↓
Data Preprocessing
   ↓
Feature Scaling (StandardScaler)
   ↓
Train-Test Split
   ↓
SVM Model Training
   ↓
Model Evaluation
   ↓
Prediction System
```

---

# 📂 Dataset Features

| Feature | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Glucose concentration |
| BloodPressure | Blood pressure value |
| SkinThickness | Skin fold thickness |
| Insulin | Insulin level |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes hereditary score |
| Age | Age of patient |
| Outcome | 0 = Non-Diabetic, 1 = Diabetic |

---

# ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| 🐍 Python | Programming Language |
| 📊 Pandas | Data Analysis |
| 🔢 NumPy | Numerical Operations |
| 🤖 Scikit-learn | Machine Learning |
| 📈 Matplotlib | Visualization |
| 📓 Jupyter Notebook / Colab | Development Environment |

---

# 🚀 Model Used

## 🔹 Support Vector Machine (SVM)

SVM is a supervised machine learning algorithm used for classification tasks.

In this project:

✔ Linear Kernel is used  
✔ StandardScaler is applied  
✔ Model predicts diabetes status accurately  

---

# 📊 Feature Scaling

This project uses:

## ✅ StandardScaler

Formula:

```math
z = \frac{x - \mu}{\sigma}
```

Where:

- \(x\) = original value
- \(\mu\) = mean
- \(\sigma\) = standard deviation

---

# 🧪 Training the Model

```python
model = svm.SVC(kernel='linear')

model.fit(X_train, y_train)
```

---

# 📈 Accuracy Evaluation

```python
training_data_accuracy = accuracy_score(X_train_prediction, y_train)

testing_data_accuracy = accuracy_score(X_test_prediction, y_test)
```

---

# 🔮 Prediction System

```python
prediction = model.predict(std_data)

if prediction[0] == 0:
    print("Patient is Non Diabetic")
else:
    print("Patient is Diabetic")
```

---

# 📸 Sample Output

```text
[1]

Patient is Diabetic
```

---

# 🎯 Project Highlights

✨ End-to-End ML Project  
✨ Real-world Healthcare Dataset  
✨ Data Preprocessing  
✨ Feature Scaling  
✨ SVM Classification  
✨ Prediction System  
✨ Beginner Friendly  

---

# 📁 Project Structure

```text
📦 Diabetes-Prediction-Using-SVM
 ┣ 📜 diabetes.csv
 ┣ 📜 diabetes_prediction.ipynb
 ┣ 📜 README.md
 ┣ 📜 requirements.txt
 ┗ 📜 Diabetes_Prediction_Report.pdf
```

---

# 📌 Future Improvements

🚀 Deploy using Streamlit  
🚀 Add Web Interface  
🚀 Improve Accuracy  
🚀 Try Different ML Models  
🚀 Hyperparameter Tuning  

---


# ⭐ If you like this project

Give this repository a ⭐ on GitHub!

---

# 📜 License

This project is open-source and available under the MIT License.
