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

### 🗂️ Project Structure

```
Natanmlproject-main/
│
├── artifacts/                   # Contains saved model, preprocessor, and train/test split data
│   ├── model.pkl
│   ├── preprocessor.pkl
│   ├── train.csv
│   └── test.csv
│
├── notebook/                    # Jupyter notebook for model development and experimentation
│   └── Untitled74.ipynb
│
├── src/                         # Source code: utils, logging, exception handling
│   ├── __init__.py
│   ├── logger.py
│   ├── exception.py
│   └── utils.py
│
├── templates/                   # HTML templates for Flask frontend
│   └── index.html
│
├── app.py                       # Flask application for web-based predictions
├── setup.py                     # Setup script to make the project pip-installable
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation
```

## 📌 Sample

When you run:

```bash
python app.py
type url: http://127.0.0.1:5000/


<img width="1919" height="617" alt="image" src="https://github.com/user-attachments/assets/ca1312aa-2dcc-4ba0-9130-ed8d573f634c" />


Click the Predict button to go to: http://127.0.0.1:5000/predictdata?


<img width="770" height="843" alt="image" src="https://github.com/user-attachments/assets/168748aa-ba45-4df8-8586-7b624b3359ad" />

Input the data and click the Predict button:



<img width="1584" height="950" alt="image" src="https://github.com/user-attachments/assets/3120dd2e-5f61-48a3-8b26-cd443408fbb6" />

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










