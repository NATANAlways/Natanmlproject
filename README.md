## END to END Machine Learning Project


# 🎯 Student Performance Prediction – End-to-End ML Project

This project aims to build an end-to-end machine learning pipeline that predicts student performance based on various academic and personal attributes. It follows a complete MLOps-ready structure with proper data ingestion, transformation, model training, evaluation, and deployment components.

---

## 📌 Problem Statement

Predict students' exam scores based on features such as parental education level, test preparation course, and other socio-economic attributes. This is a regression task.

---

## 🧰 Tech Stack

- Python
- Scikit-learn
- Pandas, NumPy
- Jupyter Notebook
- Pickle (for model saving)
- Custom logging, exception handling
- Modular pipeline (`src/` directory)
- Git for version control

```

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
  - KNN Regressor
  - Decision Tree, Random Forest
  - SVR (Support Vector Regression)
  - AdaBoost Regressor
  - XGBoost Regressor
  - CatBoost Regressor

- **Best Model**:
  - Linear Regression

- **Evaluation Metrics**:
  - R² Score
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)


## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Natanmlproject.git
   cd Natanmlproject










