# 🚗 Car Price Prediction - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a car dataset to understand the key features that affect a vehicle's price. The goal is to uncover patterns and relationships in the data that can later support the development of a car price prediction model.

---

## 📊 Dataset Information

The dataset includes detailed information about cars, including:

- **Categorical Features**: `Brand`, `Fuel Type`, `Transmission`, `Owner Type`, `Location`
- **Numerical Features**: `Year`, `Kilometers Driven`, `Mileage`, `Engine`, `Power`, `Seats`, `Price`

> 📁 The dataset is assumed to be sourced from platforms like CarDekho or Kaggle, containing pre-owned car listings.

---

## 🧰 Tools & Libraries Used

- **Python**
- **Pandas** – for data manipulation
- **NumPy** – for numerical operations
- **Matplotlib** & **Seaborn** – for data visualization
- **Jupyter Notebook** – for interactive analysis

---

## 🔍 EDA Workflow

### 1. 🧹 Data Cleaning
- Identified and handled missing values
- Converted string-based numerical features (e.g., `Mileage`, `Power`, `Engine`) to proper numeric formats
- Removed or flagged invalid entries (e.g., zero engine power or missing mileage)

### 2. 📈 Univariate Analysis
- Explored distributions of individual features such as `Year`, `Price`, and `Kilometers Driven`
- Noted trends such as more listings for newer cars and a right-skewed distribution of car prices

### 3. 📊 Bivariate & Multivariate Analysis
- Investigated relationships between `Price` and other features like `Year`, `Mileage`, `Power`, and `Kilometers Driven`
- Created scatter plots, box plots, and bar charts to visualize dependencies
- Explored how `Fuel Type`, `Transmission`, and `Owner Type` impact pricing

### 4. 🧠 Correlation Analysis
- Created a heatmap to show correlation between numeric features
- Found positive correlation between `Power`, `Engine`, and `Price`
- Observed that `Kilometers Driven` had a weak negative impact on price

### 5. ⚠️ Outlier Detection
- Used boxplots and scatter plots to detect price outliers and anomalies in features like `Engine` and `Power`
- Flagged extreme values which could skew future model training

---

## 💡 Key Insights

- Newer cars with higher engine power tend to be priced higher
- Manual cars are more frequent, but automatic ones often have higher price tags
- Diesel and petrol are the most common fuel types, but fuel type does impact pricing
- Owner type plays a significant role — first-owner cars have a higher market value

---

## 📌 What I Learned

- Practical experience in handling real-world, messy datasets
- Importance of data cleaning and preprocessing
- How visualizations can drive insight and support data-driven decisions
- Foundations for building predictive models using cleaned and analyzed data

---

## 🔮 Future Scope

- 💻 Build a **regression model** to predict car prices
- 📊 Create an **interactive dashboard** using Streamlit or Power BI
- 📦 Deploy the model as a web app using Flask or Django

---

## 📁 Project Structure

