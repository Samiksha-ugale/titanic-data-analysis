
# Titanic Data Cleaning and Exploratory Data Analysis (EDA)

This project explores and cleans the Titanic dataset using Python libraries such as pandas, seaborn, and matplotlib. The analysis includes handling missing values, feature engineering, visualizations, and insights extraction to understand survival patterns.

## Dataset Source
- The dataset is the classic Titanic dataset available on Kaggle.

## Steps Performed

### 1. Data Loading & Inspection
- Loaded dataset using pandas
- Used `.info()`, `.describe()`, `.head()`, and `.value_counts()` to understand data structure and spot missing values

### 2. Data Cleaning
- Imputed missing Age values using median
- Imputed missing Embarked values using mode
- Dropped Cabin column due to excessive missing data
- Converted 'Sex' and 'Embarked' to numerical using Label Encoding
- Created 'FamilySize' and 'IsAlone' features

### 3. Exploratory Data Analysis (EDA)
- Histograms, boxplots, count plots, pair plots
- Heatmap of correlations
- Survival rate by Pclass, Sex, Age, and FamilySize

### 4. Statistical Check
- Calculated Variance Inflation Factor (VIF) for multicollinearity among numeric features

## Key Observations
- Females had higher survival rate
- First class passengers survived more than 2nd and 3rd
- Passengers traveling alone had lower survival rates
- Children had relatively higher survival rates

## Technologies Used
- Python
- Jupyter Notebook
- pandas, seaborn, matplotlib
- statsmodels for VIF

## Folder Structure
```
├── Titanic_Data_Cleaning.ipynb
├── Titanic_Data.CSV
├── README_Titanic_EDA.md
├── Titanic Summary of Findings.PDF
```

## Author
- Samiksha Babasaheb Ugale

