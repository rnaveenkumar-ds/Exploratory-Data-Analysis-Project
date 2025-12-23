# Exploratory Data Analysis (EDA) Project

## 📌 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a dataset to uncover patterns, trends, and insights using Python.

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📊 EDA Steps Performed
- Data cleaning and preprocessing
- Handling missing values
- Univariate analysis
- Bivariate analysis
- Data visualization
- Insights and conclusions

## 📁 Dataset
The dataset contains information related to The Titanic dataset consists of 891 passenger records with 12 features describing demographic details, travel class, family information, and ticket details. The target variable Survived indicates whether a passenger survived the disaster (0 = No, 1 = Yes). The dataset includes both numerical and categorical variables, contains some missing values (notably in Age and Cabin), and is commonly used for classification and exploratory data analysis tasks.

## 🔍 Key Insights
-Missing values found in:
-Age (177 values) → filled using mean age (≈29.7).
-Embarked (2 values) → minimal impact.
-Cabin has many missing values (only 204 present).
-No duplicate records after cleaning.
-Survival Analysis by Passenger Class
-1st class passengers show the highest survival rate.
-3rd class passengers have the lowest survival rate.
-Passenger class strongly influences survival chances.

## 🚀 Conclusion
-Survival on the Titanic was not random; it strongly depended on gender, passenger class, fare, age, and family size.
-The dataset is well-suited for machine learning classification models after preprocessing.
-Feature engineering (FamilySize, Title extraction, Cabin grouping) can further improve prediction accuracy.
