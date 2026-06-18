# # 🏠 House Price Prediction Using Machine Learning

## 📖 Overview

This project focuses on predicting house prices using Machine Learning techniques. By analyzing various property attributes such as area, number of bedrooms, bathrooms, stories, parking availability, furnishing status, and other amenities, the model estimates the market value of a house. The project demonstrates a complete data science workflow, including data preprocessing, exploratory data analysis (EDA), model building, evaluation, and visualization.

---

## 🎯 Objective

The main objective of this project is to build a regression model capable of accurately predicting house prices and identifying the factors that most strongly influence property value.

---

## 📊 Dataset Information

The dataset contains residential housing information with features such as:

* Area
* Bedrooms
* Bathrooms
* Stories
* Parking
* Main Road Access
* Guest Room
* Basement
* Air Conditioning
* Preferred Area
* Furnishing Status
* Price (Target Variable)

Dataset Source: Kaggle Housing Prices Dataset

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Loading & Exploration

* Loaded the dataset using Pandas
* Examined dataset structure and statistics
* Checked for missing values and duplicates

### 2. Data Cleaning

* Removed duplicate records
* Applied One-Hot Encoding to categorical variables
* Removed less significant features where necessary

### 3. Exploratory Data Analysis

* Visualized house price distribution
* Generated correlation heatmaps
* Analyzed relationships between features and price

### 4. Model Building

* Split data into training and testing sets (80:20)
* Trained Linear Regression model
* Trained Random Forest Regressor model

### 5. Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 📈 Visualizations Included

* House Price Distribution Histogram
* Correlation Heatmap
* Actual vs Predicted Price Scatter Plot
* Feature Importance Analysis

---

## 🔍 Key Insights

* House area is the most influential factor affecting price.
* Bathrooms, bedrooms, parking spaces, and air conditioning significantly impact property value.
* Random Forest Regressor performed better than Linear Regression.
* Properties with larger areas and modern amenities generally have higher market prices.

---

## 💡 Business Recommendation

Real estate businesses should focus on properties with larger living spaces and premium amenities, as these features contribute significantly to property valuation and buyer interest.

---

## 📂 Project Structure

HousePricePrediction_Pakshal/

├── Housing.csv

├── analysis.ipynb

├── summary.pdf

├── charts/

│   ├── price_distribution.png

│   ├── correlation_heatmap.png

│   └── actual_vs_predicted.png

└── README.md

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/HousePricePrediction.git
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Launch Jupyter Notebook

```bash
jupyter notebook
```

4. Open and run `analysis.ipynb`

---

## 👨‍💻 Author

**Pakshal**

Third Year Artificial Intelligence & Data Science Engineering

Savitribai Phule Pune University (SPPU)

---

## ⭐ Future Enhancements

* XGBoost Regression
* Hyperparameter Tuning
* Streamlit Deployment
* Interactive Dashboard
* Real-Time House Price Prediction Application
