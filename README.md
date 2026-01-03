# Student-Performance
#  Student Performance Prediction using Machine Learning

##  Project Overview
Student Performance Prediction is a **Machine Learning project** that predicts a student’s final academic score based on factors such as attendance, study hours, internal marks, and assignment performance.

This project helps educational institutions **identify at-risk students early** and take corrective actions to improve academic outcomes.

---

##  Objectives
- Analyze factors affecting student academic performance  
- Build a supervised ML model to predict final scores  
- Compare multiple regression algorithms  
- Improve decision-making in education systems  

---

##  Problem Type
- **Supervised Learning**
- **Regression Problem**

---

## Technologies Used
- **Programming Language:** Python  
- **Libraries:**  
  - NumPy  
  - Pandas  
  - Matplotlib  
  - Scikit-learn  

---

##  Dataset Description
The dataset contains academic-related attributes of students.

### Sample Dataset Structure:
| Feature | Description |
|------|------------|
| attendance | Attendance percentage |
| study_hours | Daily study hours |
| internal_marks | Internal exam scores |
| assignments | Assignment scores |
| final_score | Final marks (Target variable) |

---

## Machine Learning Models Used
- Linear Regression  
- Random Forest Regression  

Random Forest performed better due to:
- Higher accuracy  
- Reduced overfitting  
- Ability to handle non-linear data  

---

## Project Workflow
1. Data Collection  
2. Data Preprocessing  
3. Feature Selection  
4. Train-Test Split  
5. Model Training  
6. Model Evaluation  
7. Prediction  

---

##  Evaluation Metrics
- **Mean Squared Error (MSE)**  
- **R² Score**

---

##  Results
- Random Forest Regression achieved better prediction accuracy  
- The model successfully predicts student performance based on academic data  

---

## How to Run the Project

### Step 1 Clone the repository
git clone https://github.com/your-username/student-performance-prediction.git
### Step 2:Intall required libraries
pip install numpy pandas matplotlib scikit-learn
### Step 3: Run the Python File
python student_performance_prediction.py

### Applications
Academic performance monitoring
Early identification of weak students
Educational analytics
Personalized learning support

### Limitations
Depends on data quality
Does not consider emotional or psychological factors

### Future Enhancements
Deep learning models
Flask-based web application
Real-time student monitoring
Explainable AI (SHAP) integration

