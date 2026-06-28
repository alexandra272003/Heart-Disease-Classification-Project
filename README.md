````markdown
# ❤️ Heart Disease Classification using Machine Learning

A complete end-to-end Machine Learning project that predicts whether a patient is at risk of heart disease based on clinical features. This project demonstrates the complete ML workflow including data preprocessing, exploratory data analysis, feature engineering, model training, hyperparameter tuning, and performance evaluation.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help doctors make timely decisions and improve patient outcomes.

This project applies multiple Machine Learning algorithms to classify whether a patient has heart disease using medical attributes.

---

## 🚀 Features

- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- StandardScaler for Feature Scaling
- Train-Test Split
- Hyperparameter Tuning
- Cross Validation
- Multiple ML Models
- Model Evaluation
- Performance Comparison

---

## 📂 Project Structure

```
Heart-Disease-Classification/
│
├── data/
│   └── heart_disease.csv
│
├── notebook/
│   └── Heart_Disease_Classification.ipynb
│
├── images/
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---

## 📊 Dataset

The dataset contains various medical attributes collected from patients.

### Features

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Rest ECG
- Maximum Heart Rate
- Exercise Induced Angina
- Oldpeak
- ST Slope
- Number of Major Vessels
- Thalassemia

### Target

- **0 → No Heart Disease**
- **1 → Heart Disease**

---

## 🧹 Data Preprocessing

The following preprocessing techniques were applied:

- Handling Missing Values
- Encoding Categorical Variables
- Feature Scaling using StandardScaler
- Train-Test Split
- Pipeline Implementation

---

## 📈 Exploratory Data Analysis

Performed EDA using

- Distribution Plots
- Histograms
- Correlation Matrix
- Heatmaps
- Target Distribution
- Feature Relationships

---

## 🤖 Machine Learning Models

The following algorithms were trained and evaluated:

### ✅ K-Nearest Neighbors (KNN)

- Hyperparameter tuning using RandomizedSearchCV
- Distance Metrics
- Number of Neighbors Optimization

---

### ✅ Logistic Regression

- GridSearchCV
- Regularization Parameter (C)
- Liblinear Solver

---

### ✅ Random Forest Classifier

- GridSearchCV
- Number of Trees
- Maximum Depth
- Minimum Samples Split
- Minimum Samples Leaf
- Bootstrap
- Feature Selection

---

## 🔍 Hyperparameter Tuning

Hyperparameter optimization was performed using:

- GridSearchCV
- RandomizedSearchCV
- Cross Validation

---

## 📊 Model Evaluation Metrics

Models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score
- Cross Validation Accuracy

---

## 📌 Best Model Performance

| Model | Test Accuracy |
|---------|--------------|
| KNN | **80.33%** |
| Logistic Regression | **78.69%** |
| Random Forest | **83.61%** |

Random Forest achieved the best overall performance on the test dataset.

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Heart-Disease-Classification.git
```

Move into project directory

```bash
cd Heart-Disease-Classification
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

## 📚 Libraries Used

```python
numpy
pandas
matplotlib
scikit-learn
jupyter
```

---

## 📷 Workflow

```
Dataset
   ↓
Data Cleaning
   ↓
EDA
   ↓
Preprocessing
   ↓
Feature Scaling
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Hyperparameter Tuning
   ↓
Model Evaluation
   ↓
Prediction
```

---

## 🎯 Future Improvements

- XGBoost
- LightGBM
- CatBoost
- Feature Selection Techniques
- Deep Learning Models
- Model Deployment using Flask or Streamlit
- Docker Support
- CI/CD Integration

---

## 👨‍💻 Author

**Alexandra Pratap Singh**

MCA (Data Science)  
University of Allahabad

### Skills

- Python
- Machine Learning
- Data Analysis
- Scikit-learn
- Data Visualization
- Model Evaluation

---

## ⭐ If you found this project useful, consider giving it a Star on GitHub!
````
