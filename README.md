# Fundamentals-of-AI-and-ML-Evaluated-Course-Project
#  Smart Study Difficulty Predictor (AI Project)

##  Overview

The **Smart Study Difficulty Predictor** is a machine learning-based project that helps students identify whether a subject or study condition will be **Easy, Medium, or Hard** based on their study habits and past performance.

This project applies concepts from **Artificial Intelligence and Machine Learning** to solve a real-world student problem.

---

##  Problem Statement

Students often struggle to identify which subjects or topics require more focus. This leads to inefficient study planning and poor academic performance.

---

##  Solution

This project uses a **Machine Learning model (Logistic Regression)** to:

* Analyze student data
* Predict difficulty level
* Provide basic study recommendations

---

##  Technologies Used

* Python
* Pandas
* Scikit-learn
* Pickle

---

##  Dataset

The dataset includes the following features:

* `hours_studied`
* `attendance`
* `previous_score`
* `sleep_hours`

Target:

* `difficulty` (Easy / Medium / Hard)

---

##  Machine Learning Model

* Algorithm: Logistic Regression
* Type: Supervised Learning (Classification)
* Data Preprocessing: StandardScaler (Feature Scaling)

---

##  Project Structure

```
Smart-Study-Predictor/
│── student_data.csv
│── train_model.py
│── predict.py
│── model.pkl
│── scaler.pkl
│── README.md
```

---

##  How to Run the Project

### 1. Install Dependencies

```
pip install pandas scikit-learn
```

### 2. Train the Model

```
python train_model.py
```

### 3. Run Prediction

```
python predict.py
```

---

##  Sample Output

```
Enter study hours: 4
Enter attendance: 75
Enter previous score: 60
Enter sleep hours: 6

Predicted Difficulty: Medium
```

---

##  Limitations

* The dataset is small and manually created
* Predictions may be inaccurate for values outside training data range
* Model can be improved with larger datasets

---

##  Future Improvements

* Add a web interface using Streamlit
* Use larger real-world datasets
* Implement advanced models (Random Forest, Neural Networks)
* Add personalized study plans

---

##  Course Relevance

This project aligns with the course **Fundamentals of AI and ML (CSA2001)**:

* Supervised Learning
* Classification Algorithms
* Data Preprocessing
* Real-world ML application

---

##  Author

Divyansh Verma

---

##  Conclusion

This project demonstrates how machine learning can be applied to solve real-life problems in education, helping students make better study decisions.
