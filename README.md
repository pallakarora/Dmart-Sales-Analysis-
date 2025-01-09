# Dmart Sales Analysis Project

This project aims to build a predictive model for estimating sales of various products across different D-Mart outlets. Using historical sales data, the project explores patterns, treats missing data, and applies preprocessing and feature engineering techniques to enhance the dataset for predictive analysis.

## Project Overview

The dataset consists of sales data from 2013 for 1559 products across 10 stores in various cities. Along with sales figures, the dataset includes attributes of the products and the stores. The objective is to identify key properties of products and outlets that drive sales, thereby aiding BigMart in optimizing its operations.

### Key Features of the Dataset:
- **Product Details:** Includes attributes such as item identifier, weight, visibility, and type.
- **Store Details:** Outlet size, type, location, and establishment year.
- **Sales Figures:** The target variable `Item_Outlet_Sales`.

## Steps in the Analysis

1. **Exploratory Data Analysis (EDA):**
   - Examined distribution of numerical and categorical variables.
   - Visualized sales trends across different outlet types and product categories.
   - Addressed missing values in columns like `Item_Weight` and `Outlet_Size`.

2. **Data Preprocessing:**
   - Filled missing values using mean and mode as appropriate.
   - Removed outliers based on interquartile range (IQR).
   - Standardized categorical variables such as `Item_Fat_Content` and `Outlet_Location_Type`.
   - Created new features such as `Outlet_Age` for enhanced predictive power.

3. **Feature Engineering:**
   - Mapped categories like `Outlet_Size` to numeric values.
   - One-hot encoded variables such as `Item_Type` and `Item_Identifier_Categories`.
   - Dropped irrelevant columns, e.g., `Item_Identifier`.

4. **Model Development:**
   - Prepared features (`X`) and target (`y`) datasets.
   - Models trained to predict `Item_Outlet_Sales`.

## Technologies Used

- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Tools:** Jupyter Notebook

## Visualizations

The project incorporates the following visualization techniques:
- Histograms and KDE plots for feature distribution.
- Count plots for categorical data.
- Correlation heatmaps to identify relationships between variables.
- Box plots and scatter plots to analyze outliers and feature-target relationships.


## Results and Insights

- Identified significant predictors of sales such as `Item_MRP`, `Outlet_Size`, and `Item_Type`.
- Outlier detection and removal improved the model's performance.
- Encoding categorical features enhanced model interpretability and efficiency.

## Future Scope

- Implement advanced machine learning algorithms for better predictive accuracy.
- Explore additional features and external datasets for comprehensive analysis.
- Develop a dashboard for real-time sales prediction and visualization.

