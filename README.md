# Bangalore House Price Analysis
This repository contains my analysis of the Bangalore house price dataset (`house_price.csv`), focusing on statistical measures ,outlier detection and visualizations.

## Project Overview
The goal of this project is to examine the 'price per sqft' variable in the Bangalore house price dataset and perform the following tasks:

1.  **Exploratory Data Analysis (EDA):** Understand the basic characteristics of the data.

2.  **Outlier Detection and Removal:** Identify and handle outliers using various statistical methods.

3.  **Box Plot Analysis:** Determine the most effective outlier removal method.

4.  **Normality Check and Transformation:** Assess and improve the normality of the 'price per sqft' column.

5.  **Correlation Analysis:** Explore the relationships between numerical variables.

6.  **Scatter Plot Visualization:** Visualize correlations through scatter plots.

## Dataset

* `house_price.csv`: Contains property prices in Bangalore.

## Methodology

### 1. Exploratory Data Analysis (EDA)

* Loaded the dataset using pandas.

* Calculated the 'price per sqft' variable.

* Performed basic statistical analysis using `describe()` , `info()` and `head()`.

### 2. Outlier Detection and Removal

* Implemented the following outlier detection methods and remove:
    
    * Mean and Standard Deviation
    
    * Percentile Method
    
    * Interquartile Range (IQR) Method
    
    * Z-Score Method
 
### 3. Box Plot Analysis

* Created box plots to visualize the distribution of 'price per sqft' after applying each outlier removal method.

* Determined the most effective method based on the box plot results.

### 4. Normality Check and Transformation

* Generated histograms to check the normality of the 'price per sqft' column.

* Calculated skewness and kurtosis before and after applying a log transformation.

* Applied a log transformation to improve normality.

### 5. Correlation Analysis

* Calculated the correlation matrix for all numerical columns.

* Created a heatmap to visualize the correlation matrix.

### 6. Scatter Plot Visualization

* Generated scatter plots to visualize the relationships between pairs of variables.

* Used pairplots to give a general view of the correlation.


## Skills Demonstrated

* Data manipulation using pandas.

* Statistical analysis with numpy and scipy.

* Data visualization with matplotlib and seaborn.

* Outlier detection and removal.

* Correlation analysis.


## Files

* `house_price.csv`: The dataset.

* `Assignment-1-statistical_measures.ipynb`: Jupyter Notebook containing the code.




