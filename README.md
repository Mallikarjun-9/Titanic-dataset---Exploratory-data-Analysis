# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Task Overview
This project is part of the **Data Analyst Internship - Task 5** under Elevate Labs & MSME. The objective is to extract insights using visual and statistical exploration techniques on a dataset.

## 🎯 Objective
- Perform Exploratory Data Analysis (EDA) on the Titanic dataset.
- Identify key patterns, trends, correlations, and anomalies.
- Use visual tools to enhance understanding of the data.

## 🧰 Tools & Technologies
- **Language**: Python
- **Libraries**: 
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for data visualization
  - `numpy` for numerical operations
- **Platform**: Jupyter Notebook

## 📁 Dataset
- **Source**: Titanic dataset (from Kaggle or seaborn)
- **Files Used**:
  - `train.csv` — primary dataset for EDA

## 🔍 Steps Followed

### 1. Data Loading & Setup
- Loaded the CSV file using `pandas.read_csv()`
- Displayed initial rows and checked structure using `.head()`, `.info()`, and `.describe()`

### 2. Data Cleaning
- Handled missing values and checked for data types
- Identified columns with nulls (like `Age`, `Cabin`, `Embarked`)

### 3. Univariate Analysis
- Plotted histograms for numeric columns like `Age`, `Fare`
- Checked distributions and outliers using boxplots

### 4. Bivariate & Multivariate Analysis
- Used `groupby()` to find survival rates by gender and class
- Created `pairplot`, `heatmap`, `scatterplot`, and `barplots`

### 5. Observations
- Females had significantly higher survival rates
- Passengers in 1st class were more likely to survive
- Younger passengers had slightly better chances
- Strong negative correlation between `Pclass` and `Fare`

### 6. Summary of Findings
- Provided bullet-point insights at the end of the notebook
- Noted anomalies and patterns for further modeling or reporting

## 📄 Deliverables
- ✔️ `Titanic_EDA.ipynb`: Jupyter Notebook with code and visuals
- ✔️ `Titanic_EDA_Report.pdf`: PDF summary of findings and interpretations

## 🧠 Outcome
- Developed skills in identifying patterns, trends, and anomalies in data
- Gained hands-on experience in visual and statistical EDA using Python

---

## 🙌 Acknowledgements
- Titanic dataset sourced from [Kaggle](https://www.kaggle.com/c/titanic) / Seaborn
