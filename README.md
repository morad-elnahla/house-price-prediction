# 🏠 House Price Prediction

## 🎓 Machine Learning Mini-Project

## 📌 Project Overview
This project builds a **House Price Prediction** model using **Multiple Linear Regression**.  
The notebook performs clean preprocessing, encoding, imputing, scaling, dimensionality reduction (optional), and evaluation using standard regression metrics.

The goal is to take raw housing data → preprocess it → train a clean regression pipeline → evaluate accuracy & error rates.

---

## 🧠 What We Actually Did in This Project
Based directly on the notebook steps:

### 🔍 1. Data Loading & Inspection  
- Read dataset into pandas  
- Checked missing values  
- Identified numerical vs categorical columns  

### 🧼 2. Preprocessing  
- Handled missing data using **KNNImputer** & **SimpleImputer**  
- Applied **OneHot Encoding** to categorical columns  
- Scaled numerical features using **StandardScaler**  
- Combined transformations into a **ColumnTransformer**

### 🧩 3. Pipeline Construction  
- Built a **full ML pipeline**:  
  Preprocessing → Linear Regression  
- Ensures clean reproducible training  
- Makes exporting the model easy later

### 🔻 4. Dimensionality Reduction (Optional)  
- Tried **Kernel PCA** on encoded/scaled features  
- Reduces noise & helps linear models sometimes  
- Experiment was included inside the workflow

### 🤖 5. Model Training (Main Model)  
- Trained **Linear Regression**  
- Fitted clean pipeline on processed data  
- Examined model coefficients

### 📊 6. Evaluation  
- Calculated:  
  - MAE (Mean Absolute Error)  
  - MSE (Mean Squared Error)  
  - RMSE  
  - R² Score  
- Included cross-validation to measure generalization  
- Plotted residuals + predicted vs actual

---

## 🛠 Tools & Libraries Used
- **Pandas** – Data handling  
- **NumPy** – Numerical ops  
- **Scikit-Learn** –  
  - LinearRegression  
  - Pipeline  
  - ColumnTransformer  
  - OneHotEncoder  
  - StandardScaler  
  - KNNImputer  
  - KernelPCA  
  - Metrics  
- **Matplotlib / Seaborn** – Visualization  

---

## 🚀 How to Run This Notebook

### 1️⃣ Install Requirements
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### 2️⃣ Run the Notebook
```bash
jupyter notebook house-price-prediction-lr.ipynb
```

### 3️⃣ Execute All Steps  
Run all cells → preprocessing → training → evaluation.

---

## 📁 Project Structure
```
├── house-price-prediction-lr.ipynb
├── data.csv (example dataset)
└── README.md
```

---

## 🎯 Conclusion
This project demonstrates how a **clean ML pipeline** with Linear Regression can predict house prices after proper preprocessing.  
The notebook shows:

- Solid data cleaning workflow  
- Encoding + scaling + imputation  
- End-to-end training pipeline  
- Reliable evaluation metrics  
- Optional dimensionality reduction

A perfect mini-project for regression fundamentals. 🧠📈

---

✨ **Predict Smarter. Understand Housing Markets Better.**  
