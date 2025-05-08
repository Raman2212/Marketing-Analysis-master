# Marketing Data Analysis

This repository contains an in-depth analysis of marketing data. The goal of this project is to clean, explore, and derive insights from the dataset to better understand customer purchasing behaviors.

## Table of Contents

- [Goals](#goals)
- [Data](#data)
  - [Loading the Data](#loading-the-data)
  - [Data Information](#data-information)
- [Data Cleaning](#data-cleaning)
  - [Adding an Age Column](#adding-an-age-column)
  - [Checking the Education Variable](#checking-the-education-variable)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
  - [Big Picture](#big-picture)
  - [Purchasing Behavior by Income](#purchasing-behavior-by-income)
  - [Purchasing Behavior by Education and Income](#purchasing-behavior-by-education-and-income)
  - [Purchasing Behavior by Age](#purchasing-behavior-by-age)
  - [Purchasing Behavior by Marital Status](#purchasing-behavior-by-marital-status)
  - [Purchasing Behavior by Country](#purchasing-behavior-by-country)
  - [Purchasing Behavior by Kids at Home](#purchasing-behavior-by-kids-at-home)
  - [Purchasing Behavior by Teens at Home](#purchasing-behavior-by-teens-at-home)
  - [Purchasing Behavior by Website Visits](#purchasing-behavior-by-website-visits)
- [Conclusion](#conclusion)

## Goals

The primary objectives of this project are:
- Understanding the dataset and cleaning it for analysis.
- Developing questions for analysis.
- Exploring variables to identify patterns and insights.

## Data

### Loading the Data
The dataset is loaded and processed using Python libraries such as:
- `pandas` for data manipulation
- `seaborn` and `matplotlib` for data visualization
- `numpy` for numerical operations

### Data Information
- **Rows and Columns**: 2240 rows × 28 columns.
- **Column Types**: Includes integers, categorical variables, and monetary values.
- **Missing Values**: The `income` column contains 24 missing entries.
- **Cleaning Steps**:
  - Renamed columns to snake_case for consistency.
  - Converted `income` from string to a numerical format.
  - Removed outliers and replaced missing values with the mean.

## Data Cleaning

### Adding an Age Column
- An `age` column is calculated using the year of birth.
- Outliers (age > 100) are removed.

### Checking the Education Variable
- Explored relationships between education levels, income, and purchasing behaviors.

## Exploratory Data Analysis

### Big Picture
- Histograms and correlation heatmaps provide an overview of the dataset.
- Income shows the strongest associations with purchasing behaviors.

### Purchasing Behavior by Income
- Positive linear relationships with catalog, store, and web purchases.
- Weak negative relationship with deal purchases.

### Purchasing Behavior by Education and Income
- Higher education levels exhibit stronger purchasing power, especially for wines.

### Purchasing Behavior by Age
- Customers aged 36–70 dominate purchases.
- Age group analysis revealed no significant differences in product preferences.

### Purchasing Behavior by Marital Status
- Divorced and widowed customers buy more wine.
- Singles prefer web purchases over store visits.

### Purchasing Behavior by Country
- ME (Middle East) customers dominate wine sales despite fewer total purchases.
- Web and catalog purchases are preferred in ME.

### Purchasing Behavior by Kids at Home
- Families with more kids at home make fewer store and catalog purchases.

### Purchasing Behavior by Teens at Home
- Families with teens buy fewer meat products but more gold products.

### Purchasing Behavior by Website Visits
- Active website users (9–10 visits/month) are more likely to make purchases.
- Deal seekers visit the site more than 17 times per month.

## Conclusion

### Insights
- **Income**: Strongest determinant of purchasing behavior.
- **Education**: Higher education correlates with higher spending.
- **Age Groups**: Customers aged 36-70 are the most active shoppers.
- **Product Preferences**: Wine is the most popular product across all demographics.
- **Geographic Trends**: ME customers excel in wine purchases and prefer online shopping.
- **Family Dynamics**: Families with teens are good targets for gold products, while families with kids respond well to deal-based marketing.

### Recommendations
- Target high-income and educated customers for premium products like wine.
- Develop marketing strategies for underrepresented age groups (18–35 and 71+).
- Focus on deal-based advertising for families with kids.
- Optimize website content for highly active users.

---

Feel free to explore the provided code and visualize the insights using the included Jupyter Notebook.
