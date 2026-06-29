# House Price Prediction - Data Preprocessing

This project is part of the **DigiSkills Artificial Intelligence (AIP-301)** assignment. It demonstrates the basic steps of data preprocessing using Python and Pandas to prepare a house price dataset for machine learning.

---

## 📌 Project Objectives

The following tasks were completed:

### 1. Dataset Loading
- Loaded the HousePricePrediction dataset using Pandas.
- Displayed the first 10 rows of the dataset.

### 2. Data Exploration
- Displayed the dataset shape.
- Checked the data types of all columns.
- Generated summary statistics for numerical features.

### 3. Data Cleaning
- Identified missing values.
- Filled missing numerical values using the median.
- Filled missing categorical values using the mode.
- Checked and removed duplicate records.

### 4. Feature Selection
- Identified relevant features for house price prediction.
- Removed the unnecessary `Id` column because it is only an identifier and does not contribute to prediction.

### 5. Data Preprocessing
- Converted categorical variables into numerical form using One-Hot Encoding (`pd.get_dummies()`).
- Prepared the dataset for machine learning.
- Displayed a preview of the preprocessed dataset.

---

## 🛠 Technologies Used

- Python 3
- Pandas
- NumPy
- Jupyter Notebook / Google Colab

---

## 📂 Dataset

**Dataset:** `HousePricePrediction.csv`

The dataset contains information about different houses, including:
- MSSubClass
- MSZoning
- LotArea
- LotConfig
- BldgType
- OverallCond
- YearBuilt
- YearRemodAdd
- Exterior1st
- BsmtFinSF2
- TotalBsmtSF
- SalePrice

---

## 📊 Data Preprocessing Steps

1. Load the dataset.
2. Explore the dataset.
3. Handle missing values.
4. Remove duplicate records.
5. Remove unnecessary features (`Id`).
6. Encode categorical variables.
7. Prepare the dataset for machine learning.

---


