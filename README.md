# EDA on Used Cars Dataset 🚗

## Project Description
This project performs a comprehensive Exploratory Data Analysis (EDA) on a dataset of used cars to uncover insights about factors influencing car prices, brands, and other attributes. The goal is to clean the data, extract meaningful features, and visualize key patterns for further modeling or decision-making.

---

## Features of the Analysis
1. **Data Cleaning**:
   - Removed irrelevant columns (`S.No.`).
   - Standardized brand names.
2. **Feature Engineering**:
   - Created `Car_Age` feature from the `Year` column.
   - Extracted `Brand` and `Model` from the `Name` column.
3. **Visualization**:
   - Distribution plots for numerical features.
   - Bar plots for categorical features.
   - Heatmap for correlation analysis.
4. **Statistical Insights**:
   - Skewness of features.
   - Grouped aggregations to analyze the impact of various factors on car prices.

---

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Key Insights
- Log transformations effectively reduced skewness in `Kilometers_Driven` and `Price`.
- Brand and location significantly affect car pricing patterns.
- Older cars tend to have lower prices, with variations depending on other features.

---

## Visuals
The analysis includes:
- Histograms and boxplots for distribution analysis.
- Bar charts for categorical comparisons.
- Correlation heatmap to assess relationships between variables.

---

## How to Run
1. Clone the repository.
2. Ensure the dataset (`used_cars_data.csv`) is in the working directory.
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
