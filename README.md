# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand patterns, trends, and relationships between features before building any machine learning model.

The objective is to analyze survival patterns based on different factors such as gender, passenger class, age, and fare.

---

## 📊 Dataset Information
- Dataset: Titanic Dataset
- Total Rows: 891
- Total Columns: 12
- Source: Kaggle Titanic Dataset

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔎 Steps Performed

### 1️⃣ Data Loading
- Imported dataset using pandas.
- Displayed first few rows for overview.

### 2️⃣ Data Understanding
- Checked dataset shape.
- Used `.info()` to inspect data types.
- Used `.describe()` for summary statistics.

### 3️⃣ Missing Values Analysis
- Age → 177 missing values
- Cabin → 687 missing values
- Embarked → 2 missing values

### 4️⃣ Data Visualization
- Survival distribution
- Gender vs Survival
- Passenger Class vs Survival
- Age distribution (Histogram)
- Fare distribution (Boxplot)
- Correlation heatmap

---

## 📈 Key Insights

- Females had significantly higher survival rate than males.
- 1st class passengers had better survival chances.
- Fare shows strong outliers.
- Age distribution is slightly right-skewed.
- Missing values present in Age and Cabin columns.

---

## 🧠 What I Learned

- Importance of EDA before model building.
- How to detect missing values and outliers.
- How visualization helps understand feature relationships.
- How correlation helps identify important features.

---

## 📌 Conclusion

EDA helped in understanding the dataset and identifying:
- Missing values
- Important survival factors
- Feature relationships

This analysis prepares the dataset for further preprocessing and machine learning modeling.

---

## 📁 Repository Structure
