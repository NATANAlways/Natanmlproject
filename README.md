# 🎯 Student Performance Prediction – End-to-End ML Project

This project builds a complete machine learning pipeline that predicts students' math scores based on various academic and socio-economic features. It includes data preprocessing, model training, evaluation, and a web-based Flask frontend for user interaction.

---

## 📌 Problem Statement

Predict a student's **math exam score** based on inputs such as gender, parental education, test preparation course, lunch type, and reading/writing scores.

This is a **regression task**.

---

## 🧰 Tech Stack

- Python
- Scikit-learn
- Pandas, NumPy
- Jupyter Notebook
- Pickle (for saving model & preprocessor)
- Custom Logging and Exception Handling
- Modular pipeline (inside `src/`)
- Flask (for web deployment)
- Git & GitHub (for version control)

---

## 📁 Project Structure

```
Natanmlproject-main/
│
├── artifacts/                         # Stores model artifacts
│   ├── model.pkl                      # Trained ML model
│   ├── preprocessor.pkl               # Preprocessing pipeline
│   ├── train.csv                      # Training dataset
│   └── test.csv                       # Testing dataset
│
├── notebook/                          # Jupyter notebooks for experimentation
│   └── Untitled74.ipynb
│
├── src/                               # Core source code
│   ├── __init__.py
│   ├── logger.py                      # Custom logger
│   ├── exception.py                   # Exception handling
│   └── utils.py                       # Utility functions
│
├── templates/                         # HTML templates for Flask frontend
│   └── index.html
│
├── app.py                             # Flask web app for predictions
├── setup.py                           # Setup script for pip installation
├── requirements.txt                   # Python dependencies
└── README.md                          # Project documentation
```

---

## 🧪 Model & Results

- **Models Evaluated**:
  - Linear Regression, Ridge, Lasso
  - K-Nearest Neighbors Regressor
  - Decision Tree, Random Forest
  - SVR (Support Vector Regression)
  - AdaBoost Regressor
  - XGBoost, CatBoost Regressors

- **Best Model**:  
  ✅ `Linear Regression` gave the best performance on test data.

- **Evaluation Metrics**:
  - R² Score
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)

---

## ⚙️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Natanmlproject.git
cd Natanmlproject
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Flask App

```bash
python app.py
```

Open your browser and go to:  
👉 [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

---

## 📌 Sample

### ▶️ Home Page

```bash
python app.py
```

Go to: [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

<img src="https://github.com/user-attachments/assets/ca1312aa-2dcc-4ba0-9130-ed8d573f634c" width="100%" />

---

### ▶️ Prediction Form

Click the **Predict** button.  
This redirects to: [http://127.0.0.1:5000/predictdata](http://127.0.0.1:5000/predictdata)

<img src="https://github.com/user-attachments/assets/168748aa-ba45-4df8-8586-7b624b3359ad" width="60%" />

---

### ▶️ Prediction Result

After filling the form and clicking "Predict", the output is displayed:

<img src="https://github.com/user-attachments/assets/3120dd2e-5f61-48a3-8b26-cd443408fbb6" width="100%" />

---


