# 📊 Titanic Dataset - Exploratory Data Analysis (EDA)

This project is part of the AI & ML Internship program and focuses on performing Exploratory Data Analysis (EDA) on the Titanic dataset. The goal is to gain insights about the data using descriptive statistics and various types of visualizations.

---

## 🧠 Objective

To understand the dataset through:
- Summary statistics
- Visualizations
- Correlation analysis
- Pattern and anomaly detection

---

## 📁 Dataset

- Source: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File used: `titanic.csv`

---

## 🛠 Tools Used

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- *(Optional)* Plotly for interactive visualizations

---

## ✅ Tasks Performed

### 1. Data Loading
- Loaded the dataset using `pandas`.

### 2. Descriptive Statistics
- Used `.describe()` and `.info()` to understand feature types, missing values, and data distribution.

### 3. Univariate Analysis
- Histograms for age, fare, and other numerical columns.
- Boxplots to detect outliers.

### 4. Bivariate Analysis
- Countplots and barplots for categorical vs target (`Survived`).
- Correlation matrix and heatmap.
- Pairplot to explore pairwise relationships.

### 5. Insights Gained
- Higher survival rate in females.
- Passengers from higher classes (Pclass = 1) had better survival chances.
- Fare has a right-skewed distribution with some extreme outliers.

---

## 📂 Folder Structure
- task 2.ipynb # Jupyter Notebook with EDA code
- titanic.csv # Raw dataset
- README.md # Project documentatio
