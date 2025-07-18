# 🩺 Diabetes Prediction Using Machine Learning

This project was completed as part of my **AI/ML Internship** at **InternPe**. The task was to develop a machine learning model that predicts whether a patient is diabetic based on health parameters using classification techniques.

---

## 📌 Task Objective

Build and evaluate a machine learning model capable of binary classification (Diabetic / Not Diabetic) based on structured medical data.

---

## 🛠️ Technologies Used

- Python 3.x  
- Jupyter Notebook  
- NumPy  
- Pandas  
- scikit-learn  
  - Support Vector Machine (SVM)  
  - Train-Test Split  
  - Standard Scaler  
  - Accuracy Score  
- Warnings (for cleaner outputs)

---

## 📁 Project Structure



diabetes-prediction/
│
├── diabetes\_prediction.ipynb     # Jupyter Notebook with the full ML pipeline
├── diabetes.csv                  # Dataset used for training/testing
├── README.md                     # Project documentation



---

## 🧬 Dataset Description

The dataset contains medical records of patients and includes features like:
- Pregnancies  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  
- Outcome (0 = Not Diabetic, 1 = Diabetic)

---

## 🔄 ML Workflow

1. **Data Loading** – Read the dataset using `pandas`
2. **Preprocessing** – Scale features using `StandardScaler`
3. **Data Splitting** – Divide into training and testing sets (80/20)
4. **Model Training** – Train an SVM classifier (`SVC(kernel='linear')`)
5. **Model Evaluation** – Measure performance using `accuracy_score`
6. **Prediction System** – Accept new input data and predict the result

---

## 📊 Results

- **Training Accuracy**: ~78%  
- **Testing Accuracy**: ~78%  
- The model generalizes well and provides consistent predictions

---

## 🔧 Future Scope

- Try other ML models: Random Forest, Logistic Regression, etc.  
- Improve accuracy via hyperparameter tuning  
- Deploy using Flask, Streamlit, or as a web API  
- Add GUI for better user experience

---

## 🎓 Internship & Task Details

- **Internship Track**: Artificial Intelligence & Machine Learning  
- **Internship Provider**: InternPe  
- **Task Name**: Task 01 – Diabetes Prediction Model  
- **Environment**: Jupyter Notebook (Local)

---

## 📬 Contact

**Difina George**  
📧 difina.georgecs@gmail.com  
📍 Kerala, India
