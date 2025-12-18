# Task 5 – Exploratory Data Analysis (EDA) on Titanic Dataset

## 📌 Objective
The objective of this task is to perform **Exploratory Data Analysis (EDA)** to extract meaningful insights using **statistical methods and visualizations**. The analysis focuses on identifying patterns, trends, relationships, and anomalies in the dataset.

---

## 📊 Dataset
- **Dataset Used:** Titanic Dataset  
- **Source:** Kaggle Titanic Competition - https://www.kaggle.com/competitions/titanic/data?select=train.csv
- The dataset contains passenger information such as age, gender, passenger class, fare, and survival status.

---

## 🛠 Tools & Libraries
- Python  
- Pandas  
- Matplotlib  
- Seaborn  

---

## 🔍 Steps Performed

### 1. Data Understanding
- Loaded the dataset and inspected its structure using:
  - `df.info()`
  - `df.describe()`
  - `value_counts()` for categorical variables

### 2. Missing Value Analysis
- Identified missing values in Age, Cabin, and Embarked columns.
- Documented missing value handling strategy.

### 3. Data Cleaning
- Created a cleaned copy of the dataset (`df_clean`) to preserve raw data.
- Filled missing Age values using **median**.
- Filled missing Embarked values using **mode**.
- Dropped Cabin column due to excessive missing values.

### 4. Univariate Analysis
- Survival count distribution
- Gender distribution
- Age distribution (histogram)
- Fare distribution (histogram)

### 5. Bivariate Analysis
- Survival vs Gender
- Survival vs Passenger Class
- Survival vs Fare (boxplot)

### 6. Multivariate Analysis
- Correlation heatmap
- Pairplot for numerical features
- Explicit scatterplot (Age vs Fare)

### 7. Observations & Insights
- Observations were written for **each visualization**.
- A final summary of findings was provided.

---

## 📈 Key Insights
- Survival rate on the Titanic was low.
- Female passengers had significantly higher survival rates.
- First-class passengers were more likely to survive.
- Higher fares were associated with higher survival probability.
- Socio-economic factors played a stronger role than age alone.

---

## 📌 Conclusion
This EDA demonstrates how visual and statistical exploration can reveal important patterns in real-world data. The analysis highlights the role of gender and socio-economic status in survival outcomes on the Titanic.

---
## 🧑‍💻 Author - MOHAMMAD SHARJEEL YAZDANI

This project was completed as part of a Data Analyst Internship assignment.

