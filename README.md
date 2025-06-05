# 📊 Marketing Data Visualization Dashboard

## Key Insights
- **Income** is the most predictive factor for total purchases.
- **Wine** is the top selling product—especially to widows/divorced and in "ME" country.
- Older and middle-aged shoppers (36–70) are most active.
- Website visits correlate with deal-seeking; families with teens are gold product buyers.

## Chart Types Used
- **Scatterplots & Regression Lines:** Income vs. Purchases, colored by Education/Country
- **Boxplots:** Distribution of Purchases by Age Group, Marital Status
- **Bar Charts:** Purchases by Categorical Variables (Age, Country, Marital Status, Website Visits)
- **Heatmap:** Correlation Matrix of Numeric Variables
- **FacetGrid:** Small multiples for Education/Income breakdowns

## Features
- **Interactive Dashboard:** Filter by age, education, country, marital status.
- **Download filtered data** for further analysis.
- **Responsive visualizations**—hover for details.
- **Summary statistics** for selected groups.

## How to Run
```sh
pip install pandas numpy matplotlib seaborn plotly streamlit scikit-learn
streamlit run app.py
```
Place `marketing_data.csv` in the same folder.

## Data
- Source: `marketing_data.csv`
- Cleaned to snake_case, outliers removed, missing values imputed.


