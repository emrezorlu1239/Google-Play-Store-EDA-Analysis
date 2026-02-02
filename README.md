# Google Play Store Data Analysis & Preprocessing

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458)
![Status](https://img.shields.io/badge/Status-Completed-success)

This project focuses on **Data Cleaning**, **Feature Engineering**, and **Exploratory Data Analysis (EDA)** of the Google Play Store dataset. The primary goal is to transform raw, unstructured data into a clean numerical format suitable for Machine Learning models.

## Project Overview

- **Dataset:** Google Play Store Apps (10,000+ records) & User Reviews.
- **Objective:** Analyze key factors influencing App Ratings and prepare the dataset for predictive modeling.
- **Key Techniques:** Data Cleaning, Sentiment Analysis, One-Hot Encoding, Statistical Visualization.

## Key Steps Performed

### 1. Data Cleaning
- **Missing Values:** Handled null values through statistical imputation.
- **Duplicates:** Removed duplicate entries to ensure data integrity.
- **Formatting:** Cleaned non-numeric characters from columns like `Price`, `Installs`, and `Size` (e.g., removing '$', '+', 'M', 'k').

### 2. Feature Engineering
- **Date Handling:** Converted `Last Updated` to datetime objects for temporal analysis.
- **Sentiment Analysis:** Merged user reviews to calculate `Sentiment_Polarity` and `Subjectivity`.
- **Encoding:** Applied One-Hot Encoding to categorical variables (Category, Type, Content Rating).

### 3. Exploratory Data Analysis (EDA)
- Visualized the distribution of app ratings across different categories.
- Analyzed correlations between Reviews, Size, Price, and Ratings.
- **Key Finding:** Identified a strong positive correlation between User Sentiment Polarity and App Ratings.

## Visualizations

The analysis includes a dashboard containing:
* Rating Distribution Histograms
* Sentiment vs. Rating Regression Plots
* Market Share Analysis (Free vs. Paid)
* Category Performance Boxplots

## Technologies & Libraries

* **Pandas:** Data manipulation and cleaning.
* **NumPy:** Numerical computations.
* **Matplotlib & Seaborn:** Data visualization.
* **Scikit-learn:** Data preprocessing.

---
*This project demonstrates end-to-end data preprocessing and analytical skills.*
