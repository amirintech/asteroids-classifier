# 🚀 Asteroids Classification using Machine Learning

This project aims to classify asteroids using a **machine learning model** based on their physical and orbital characteristics. The dataset is cleaned, preprocessed, and analyzed to extract meaningful patterns that improve classification accuracy.

## 📌 Project Overview
- **Loads and preprocesses** asteroid data, removing redundant and irrelevant features.
- Encodes categorical features like **NEO (Near-Earth Object)** and **PHA (Potentially Hazardous Asteroid)**.
- Implements **feature engineering** to refine data representation.
- Trains a **classification model** to predict asteroid types.
- Evaluates model performance using various metrics.

---

## 🛠️ Technologies Used
- **Python** (Primary language)
- **Scikit-learn** (Machine Learning models)
- **Pandas & NumPy** (Data handling)
- **Matplotlib & Seaborn** (Data visualization)
- **Jupyter Notebook** (Exploratory data analysis)

---

## 🔬 Data Preprocessing Steps
### 1️⃣ **Feature Selection**
- Removed unnecessary attributes like `id`, `name`, and redundant time representations (`epoch_mjd`, `epoch_cal`).

### 2️⃣ **Feature Cleaning**
- Eliminated missing values and irrelevant attributes.
- Unified redundant features (`per`, `per_y`) that had different scales.

### 3️⃣ **Feature Engineering**
- **Encoded** categorical variables (`neo`, `pha`, `class`) into numerical representations.
- Computed missing `neo` values using **perihelion distance (`q`)**.

### 4️⃣ **Final Dataset Preparation**
- Ensured feature consistency and normalization for model training.

---

## 🤖 Model Implementation
- Applied **Supervised Learning** techniques to classify asteroids.
- Split dataset into **training and testing** sets.
- Evaluated model performance using **accuracy, precision, recall, and F1-score**.

---

## 📊 Results & Insights
- Successfully classified asteroids based on **orbital and physical properties**.
- Encoding `neo` based on **perihelion distance (`q`)** improved classification accuracy.
- Some features were redundant and removing them enhanced model efficiency.

