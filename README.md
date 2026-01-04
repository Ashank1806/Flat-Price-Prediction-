# 🏢 Flat Price Prediction

## 📌 Project Overview
**Flat Price Prediction** is an end-to-end Machine Learning project that predicts property prices in **Gurgaon city** using real estate data collected from the **99acres website**.  
This project covers the complete ML pipeline—from **web scraping and data preprocessing** to **model training and deployment** using **Streamlit**.

---

## 📊 Data Collection
- Data collected through **web scraping** from the 99acres website
- Two datasets:
  - **Flats dataset**
  - **Houses dataset**
- Location: **Gurgaon, India**

## 🧹 Data Cleaning
Each dataset was cleaned separately using the following steps:

- Handled missing values
- Converted data types
- Removed duplicate records
- Corrected spelling mistakes
- Removed irrelevant columns
- Renamed columns for clarity
- Converted text features into numerical values

After cleaning, both datasets were merged and further refined.

---

## ⚙️ Feature Engineering
The following techniques were applied:

- Feature scaling
- Creation of new features
- One-Hot Encoding
- Target Encoding

---

## 📈 Exploratory Data Analysis (EDA)
EDA was performed to understand the data distribution and relationships:

- Univariate analysis
- Multivariate analysis
- Visual insights using plots and charts

---

## 🚫 Outlier Handling & Missing Value Imputation
- Identified and removed outliers
- Missing values handled using:
  - Mean
  - Median

---

## 🤖 Model Building
- Applied multiple feature extraction techniques
- Trained several Machine Learning models
- Used **cross-validation** for model evaluation
- Performed **hyperparameter tuning** for optimization

### 🏆 Best Performing Model
- **Random Forest Regressor**
- Achieved high prediction accuracy 90.05% with 45L MSE
- Selected as the final model


---

## 🌐 Model Deployment
- Built an end-to-end **Machine Learning web application**
- Used **Streamlit** for real-time price prediction

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- BeautifulSoup / Requests
- Streamlit
- Jupyter Notebook
