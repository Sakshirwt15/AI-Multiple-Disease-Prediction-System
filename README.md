# AI Multiple Disease Prediction System 🧑‍⚕️

## Overview

The **AI Multiple Disease Prediction System** is a web application that predicts the likelihood of multiple diseases using machine learning models.
The application is built using **Python and Streamlit**, providing an interactive interface where users can input medical parameters and receive predictions instantly.

This system currently supports prediction for the following diseases:

* Diabetes
* Heart Disease
* Parkinson’s Disease
* Breast Cancer

The goal of this project is to demonstrate how **machine learning models can assist in early disease detection and healthcare decision support**.

---

## Features

* Predicts multiple diseases using trained machine learning models
* Simple and user-friendly web interface
* Fast predictions using optimized models
* Interactive dashboard built with Streamlit
* Supports multiple medical datasets

---

## Tech Stack

**Programming Language**

* Python

**Framework**

* Streamlit

**Machine Learning Libraries**

* Scikit-learn
* XGBoost

**Data Analysis & Visualization**

* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Project Structure

```
Multiple-Disease-Prediction-System
│
├── Datasets/                # Datasets used for model training
├── Models/                  # Trained ML models
├── notebooks/               # Model development and experimentation
├── streamlit_app.py         # Main Streamlit application
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
```

---

## Installation

To run this project locally:

### 1. Clone the repository

```
git clone https://github.com/sakshirwt15/AI-Multiple-Disease-Prediction-System.git
```

### 2. Navigate to the project directory

```
cd AI-Multiple-Disease-Prediction-System
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

---

## Usage

Run the Streamlit application:

```
streamlit run streamlit_app.py
```

After running the command, the application will open in your browser at:

```
http://localhost:8501
```

You can then select a disease prediction system from the sidebar and enter the required medical parameters to obtain predictions.

---

## Dataset Description

### Diabetes Prediction

* 768 patient records
* 8 medical features such as glucose level, blood pressure, BMI, and insulin levels.

### Heart Disease Prediction

* 1025 records
* 14 attributes including age, sex, chest pain type, cholesterol level, etc.

### Parkinson’s Disease Prediction

* 195 instances
* 22 biomedical voice measurements used to detect Parkinson’s disease.

### Breast Cancer Prediction

* 569 instances
* 30 numerical features derived from digitized images of breast mass.

---

## Machine Learning Models Used

Different classification models were trained and evaluated to select the best-performing models.

### Diabetes Prediction

* Support Vector Classifier
* Logistic Regression
* Random Forest

### Heart Disease Prediction

* XGBoost
* Random Forest
* Logistic Regression

### Parkinson’s Disease Prediction

* K-Nearest Neighbors
* XGBoost
* Random Forest

### Breast Cancer Prediction

* Logistic Regression
* XGBoost
* K-Nearest Neighbors

---

## Model Development Process

1. Data collection and preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature selection
4. Model training using multiple algorithms
5. Hyperparameter tuning using GridSearchCV
6. Model evaluation using accuracy and classification reports

---

## Model Performance

| Disease       | Best Accuracy |
| ------------- | ------------- |
| Diabetes      | 75%           |
| Heart Disease | 100%          |
| Parkinson’s   | 100%          |
| Breast Cancer | 97%           |

---

## Deployment

The application can be deployed using **Streamlit Cloud** or other cloud platforms.

Example deployment platform:

Streamlit Cloud

---

## Future Improvements

* Add more disease prediction models
* Improve UI/UX of the application
* Integrate real-time patient data
* Add model explainability features

---

## Author

**Sakshi Rawat**

GitHub: https://github.com/sakshirwt15
