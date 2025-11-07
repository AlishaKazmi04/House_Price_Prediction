#  Indian House Price Prediction using Machine Learning

This project predicts house prices in India using a real-world dataset. It demonstrates a complete machine learning pipeline including data cleaning, encoding, scaling, model training, evaluation, and saving the best model for future predictions — all implemented in a Google Colab notebook.

---

##  Dataset Description

- **Source:** [Kaggle – Housing Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
- **Format:** CSV
- **Size:** ~12,000 rows and 13 columns
- **Target Variable:** `price` (house price in INR)

### 🔍 Feature Summary:
- `area`: Total area of the house (numeric)
- `bedrooms`, `bathrooms`, `stories`: Structural features (numeric)
- `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `parking`, `prefarea`: Binary categorical features (`yes`/`no`)
- `furnishingstatus`: Multi-class categorical feature (`furnished`, `semi-furnished`, `unfurnished`)

###  Challenges:
- Missing values in both numerical and categorical columns
- Mixed data types requiring encoding
- Skewed price distribution and presence of outliers

---

##  Workflow Overview
- Data Cleaning & Imputation
- Encoding Categorical Features
- Feature Scaling
- Model Training (Linear Regression, Random Forest)
- Evaluation (RMSE, MAE, R²)
- Saving Best Model
- Demo Prediction

---

##  Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

---

##  Authors
**Alisha Kazmi**  
**Aman Sharma**

Prefinal-year B.Tech students specializing in Data Science and Artificial Intelligence, passionate about applying ML to real-world problems.


