# 🎓 Student Performance Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting **student academic performance** based on key factors such as **study hours** and **attendance rate**.  
A **supervised machine learning model (Linear Regression)** is trained on a large dataset to estimate final examination marks.

The goal of this project is to demonstrate practical implementation of **data preprocessing, model training, evaluation, and prediction** using Python.

---

## 🧠 Problem Statement
Student performance is influenced by multiple academic factors.  
Predicting marks in advance can help educators and institutions identify students who may need additional academic support.

---

## 🛠️ Technologies Used
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Scikit-learn  
- **Machine Learning Algorithm:** Linear Regression  
- **Platform:** Google Colab  

---

## 📂 Dataset Description
The dataset contains over **90,000 student records** with the following features:

| Column Name | Description |
|------------|-------------|
| Study_Hours | Average number of hours studied per day |
| Attendance_Rate | Attendance percentage of the student |
| HSSC_II_Marks | Final examination marks (Target Variable) |

---

## ⚙️ Methodology
1. Loaded and explored the dataset
2. Selected relevant features and target variable
3. Handled missing values
4. Split the dataset into training and testing sets
5. Trained a Linear Regression model
6. Evaluated the model using performance metrics
7. Visualized actual vs predicted results
8. Predicted marks for new student data

---

## 📊 Model Evaluation Metrics
The model performance is evaluated using:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

---

## 📈 Results
The Linear Regression model demonstrates a strong relationship between:
- Study Hours  
- Attendance Rate  
and student marks.

The visualization of actual vs predicted marks shows that the model performs effectively on large-scale data.

---

## 🔮 Sample Prediction
Example input:
- Study Hours: `5`
- Attendance Rate: `85%`

Output:
- Predicted Final Marks (HSSC II): *Model Generated*

---

## 🚀 How to Run the Project
1. Open **Google Colab**
2. Upload the dataset `student_performance_dataset_90k.csv`
3. Copy the Python code into a Colab notebook
4. Run all cells to train and test the model

---

## 📌 Future Enhancements
- Add more academic and demographic features
- Apply advanced regression models
- Build a web-based interface using Flask
- Perform feature scaling and hyperparameter tuning

---

## 👤 Author
**Golla Mohan Datta**  
- 📧 Email: gollamohan970@gmail.com  
- 🔗 LinkedIn: https://www.linkedin.com/in/mohan-datta-golla-198203368/

---

## ⭐ Conclusion
This project highlights the practical application of **machine learning in education analytics**, showcasing how data-driven approaches can help predict student outcomes and support academic decision-making.
