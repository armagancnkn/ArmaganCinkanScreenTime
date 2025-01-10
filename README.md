
# Project ReadMe

## Overview
This repository contains data files and a Jupyter notebook for analyzing shopping behavior and screen time usage. The main objective is to extract insights from the provided datasets and document the steps undertaken in the analysis process.

## Files in the Repository
1. **shopping.csv**: Contains data related to shopping behavior, such as customer purchases, item categories, and transaction details.
2. **screen_time.csv**: Provides data on screen time usage, including app categories, usage duration, and timestamps.
3. **analyze.ipynb**: Jupyter notebook containing the data analysis, preprocessing steps, and visualizations.

## Steps Undertaken

### 1. Data Exploration
- Loaded the datasets using pandas.
- Inspected the structure of the datasets using functions like `.head()`, `.info()`, and `.describe()`.

### 2. Data Preprocessing
- Identified and handled missing or inconsistent data.
- Performed data cleaning, including renaming columns for clarity and converting data types.
- Standardized time formats in the screen time dataset.

### 3. Data Analysis
#### Shopping Data
- Analyzed customer purchasing patterns and top-selling categories.
- Visualized trends using bar charts and histograms.

#### Screen Time Data
- Examined daily and weekly usage patterns.
- Grouped data by app categories to understand the most used categories.
- Created time-series plots for visualizing usage over time.

### 4. Insights and Findings
- Summarized key findings from both datasets.
- Highlighted correlations between shopping habits and screen time behavior.

### 5. Visualizations
- Included charts and graphs for a better understanding of the trends.
- Used libraries like Matplotlib and Seaborn for plotting.

## How to Run the Notebook
1. Clone the repository.
2. Ensure you have Python and Jupyter Notebook installed.
3. Install necessary libraries using:
   ```bash
   pip install pandas matplotlib seaborn
   ```
4. Open `analyze.ipynb` in Jupyter Notebook and run the cells sequentially.

## Future Work
- Incorporate machine learning models to predict customer behavior based on screen time patterns.
- Perform sentiment analysis on customer reviews if available.

## Author
This project was developed to analyze datasets and derive actionable insights. For any queries, feel free to contact the author.
