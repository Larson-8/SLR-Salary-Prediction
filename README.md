# 💰 Salary Prediction Using Simple Linear Regression

## 📌 Project Overview

This project is a Machine Learning web application that predicts an employee's salary based on their years of experience using **Simple Linear Regression (SLR)**. The model is trained using historical salary data and deployed through a user-friendly web interface built with Flask.

The application allows users to enter their years of experience and instantly receive a predicted salary.

---

## 📖 Problem Statement

Salary estimation is an important task for organizations and job seekers. This project aims to automate salary prediction by identifying the relationship between:

* **Independent Variable (X):** Years of Experience
* **Dependent Variable (Y):** Salary

A Simple Linear Regression model is trained to learn this relationship and generate salary predictions for new inputs.

---

## 🎯 Objectives

* Understand the implementation of Simple Linear Regression.
* Train a Machine Learning model using Scikit-Learn.
* Save and load trained models using Pickle.
* Build a web application using Flask.
* Deploy the application on Render.
* Showcase an end-to-end Machine Learning project.

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Machine Learning

* Scikit-Learn
* NumPy
* Pandas

### Backend

* Flask

### Frontend

* HTML
* CSS

### Deployment

* Gunicorn
* Render

### Version Control

* Git
* GitHub

---

## 📂 Project Structure

```text
Salary-Prediction/
│
├── app.py
├── requirements.txt
├── Procfile
├── SLR_model.pkl
│
├── templates/
│   └── index.html
│
└── README.md
```

---

## 📊 Machine Learning Workflow

### Step 1: Data Collection

A salary dataset containing:

* Years of Experience
* Salary

was collected for training the model.

---

### Step 2: Data Preprocessing

The dataset was cleaned and prepared using Pandas and NumPy.

Tasks performed:

* Data inspection
* Feature selection
* Data transformation

---

### Step 3: Model Training

The project uses **Simple Linear Regression**.

Linear Regression Formula:

[
y = mx + c
]

Where:

* y = Predicted Salary
* x = Years of Experience
* m = Slope
* c = Intercept

The model learns the relationship between experience and salary from historical data.

---

### Step 4: Model Saving

After training, the model is saved as:

```python
SLR_model.pkl
```

using Python's Pickle library.

This prevents retraining the model every time the application starts.

---

### Step 5: Model Deployment

The trained model is integrated with Flask and deployed on Render.

Workflow:

```text
User Input
     ↓
Flask Application
     ↓
Loaded SLR Model
     ↓
Salary Prediction
     ↓
Display Result
```

---

## ⚙️ Application Workflow

### Home Page

The user enters:

```text
Years of Experience
```

Example:

```text
5
```

### Prediction

The value is sent to Flask through an HTML form.

The Machine Learning model predicts the salary.

### Result

The predicted salary is displayed on the webpage.

Example:

```text
Predicted Salary = ₹75,000
```

---


## 🔧 Installation Guide

### Clone Repository

```bash
git clone https://github.com/your-username/salary-prediction.git
```

### Navigate to Project Directory

```bash
cd salary-prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

### Open Browser

```text
http://127.0.0.1:5000/
```

---

## 🌐 Deployment on Render

### Build Command

```bash
pip install -r requirements.txt
```

### Start Command

```bash
gunicorn app:app
```

### Procfile

```text
web: gunicorn app:app
```

---

## 📈 Future Enhancements

* Multiple Linear Regression
* Advanced UI Design
* Input Validation
* Salary Range Prediction
* Interactive Data Visualizations
* Docker Deployment
* Cloud Database Integration
* User Authentication

---

## 🎓 Learning Outcomes

Through this project, I learned:

* Machine Learning fundamentals
* Simple Linear Regression
* Model Serialization using Pickle
* Flask Web Development
* HTML/CSS Integration
* GitHub Version Control
* Cloud Deployment using Render

---

## 🤝 Contribution

Contributions, suggestions, and improvements are welcome.

Feel free to fork this repository and submit pull requests.

---

## 📧 Contact

**Manoj Kumar**

GitHub: https://github.com/Larson-8

LinkedIn: https://www.linkedin.com/in/manoj-kumar-balisetty-53794b256/

Email: manojkumarbalisetty@gmail.com

---

## ⭐ If you found this project useful, please give it a star on GitHub!
