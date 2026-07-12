# medical-insurance-data-analysis
Data Cleaning and Exploratory Data Analysis using Python, Pandas, and Scikit-learn.
#  Medical Insurance Data Cleaning & Exploratory Data Analysis

##  Project Overview

This project demonstrates a complete data cleaning and exploratory data analysis (EDA) workflow using a real-world medical insurance dataset. The primary goal is to understand the dataset, improve its quality, identify potential issues, and prepare it for future machine learning applications.

The analysis focuses on data preprocessing techniques that are commonly used before building predictive models. Throughout the project, statistical analysis and data visualization were used to gain insights into the dataset and evaluate the quality of the data.

---

##  Dataset

**Dataset:** Medical Cost Personal Dataset

The dataset contains demographic and health-related information about insurance beneficiaries, including:

* Age
* Sex
* Body Mass Index (BMI)
* Number of Children
* Smoking Status
* Region
* Individual Medical Insurance Charges

The target variable in this dataset is **charges**, which represents the medical insurance cost.

---

##  Project Objectives

* Understand the structure of the dataset.
* Explore numerical and categorical variables.
* Detect duplicate records.
* Identify and handle missing values.
* Analyze relationships between variables.
* Measure skewness and apply transformations when necessary.
* Scale numerical features.
* Detect potential outliers using statistical techniques.
* Prepare the dataset for future machine learning models.

---

##  Tools & Libraries

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Scikit-learn

---

##  Data Preprocessing Workflow

### 1. Data Loading

* Loaded the dataset into a Pandas DataFrame.
* Displayed the first rows of the dataset.
* Inspected the dataset structure.

---

### 2. Data Exploration

* Examined dataset dimensions.
* Checked column names and data types.
* Generated descriptive statistics for numerical features.
* Explored categorical variables using value counts.

---

### 3. Data Cleaning

* Checked for duplicate records.
* Removed duplicate rows when necessary.
* Investigated missing values.
* Demonstrated different approaches for handling missing data, including:

  * Dropping rows
  * Dropping columns
  * Filling missing values using the median

---

### 4. Correlation Analysis

* Selected numerical features.
* Calculated Pearson correlation coefficients.
* Identified features that have strong relationships with the target variable (**charges**).
* Visualized relationships using scatter plots.

---

### 5. Distribution Analysis

* Examined the distribution of the target variable.
* Calculated skewness.
* Applied logarithmic transformation to reduce skewness.
* Compared the data distribution before and after transformation.

---

### 6. Feature Scaling

Applied two common feature scaling techniques:

* Min-Max Scaling
* Standardization (StandardScaler)

The project also demonstrates how to standardize an individual feature.

---

### 7. Outlier Detection

Investigated outliers using multiple approaches:

* Boxplots
* Scatter plots
* Z-score analysis

Potential outliers were identified and removed where appropriate for demonstration purposes.

---

##  Key Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Missing Value Handling
* Duplicate Detection
* Correlation Analysis
* Feature Scaling
* Skewness Analysis
* Outlier Detection
* Data Preparation for Machine Learning

---

##  What I Learned

Through this project, I strengthened my understanding of the complete data preprocessing pipeline. I practiced cleaning raw data, exploring feature relationships, applying statistical techniques, scaling numerical features, and identifying outliers. These steps are essential for preparing high-quality datasets before building machine learning models.

---

##  Future Work

The cleaned dataset will be used in future projects to build and evaluate machine learning models for predicting medical insurance charges.

Potential models include:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Models

---

##  Repository Contents

* `Medical_Insurance_EDA.ipynb` — Complete notebook containing the analysis.
* `insurance.csv` — Dataset used in the project.
* `README.md` — Project documentation.

---

##  Author

**Fatma Sirag**

Artificial Intelligence Undergraduate | Former Dentist | Aspiring AI Engineer

Currently building practical projects in Data Analysis, Machine Learning, and Artificial Intelligence.
