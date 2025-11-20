📘 Simple Linear Regression – CGPA to Package Prediction (Streamlit App)

This project demonstrates a Simple Linear Regression model that predicts a student’s salary package based on their CGPA, along with a Streamlit web application for real-time predictions.

📌 Overview

Feature (X): CGPA

Target (Y): Salary Package

Model: Linear Regression

App Framework: Streamlit

Model File: regression_model.joblib

Dataset Size: 200 rows, 2 columns

The workflow includes data analysis, model training, saving the model, and deploying it using Streamlit.

📂 Project Structure
Simple_Linear_Regression/
│
├── Single Linear Regression.ipynb   # Training notebook
├── app.py                           # Streamlit web app
├── regression_model.joblib          # Saved ML model
├── requirements.txt                 # Dependencies
├── .gitignore
└── README.md

📊 Dataset Example
cgpa	package
6.89	3.26
5.12	1.98
7.82	3.25
7.42	3.67
6.94	3.57

The model learns the relationship between CGPA and salary package.

🧠 Model Training Summary

Trained using sklearn LinearRegression

Evaluated using: R² Score, MAE, MSE

Saved with: joblib.dump(model, "regression_model.joblib")

🚀 How to Run the Streamlit App
1️⃣ Install requirements
pip install -r requirements.txt

2️⃣ Run the application
streamlit run app.py

3️⃣ Predict through UI

Enter CGPA

Click Predict

Get the salary package output

🛠 Tech Stack 
Python, Pandas, NumPy, Scikit-Learn, Streamlit, Joblib, Jupyter Notebook

📈 Insights

The linear model follows:

package = m * cgpa + c


As CGPA increases, predicted package also increases.

🎯 Use Cases

Placement package prediction,
Student performance analytics,
Educational ML demo,
Streamlit model deployment example.

🤝 Contributing

Contributions, issues, and suggestions are welcome.

⭐ Support

If you like this project, please give the repository a star ⭐.
