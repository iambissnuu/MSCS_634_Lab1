# MSCS 634 – Lab 1: Data Visualization, Preprocessing, and Statistical Analysis

## Student Information

Name: Bishnu Sharma
Course: MSCS 634 – Data Mining
Lab Assignment: Lab 1 – Data Visualization, Preprocessing, and Statistical Analysis

---

## Overview

The purpose of this lab is to explore the fundamental processes involved in data analysis and data preprocessing using Python and Jupyter Notebook. The lab focuses on loading a dataset, visualizing relationships between variables, preparing data for analysis, and performing statistical analysis to understand the dataset’s characteristics.

Python libraries such as **Pandas**, **Matplotlib**, **Seaborn**, and **Scikit-learn** were used to perform data manipulation, visualization, and preprocessing tasks.

---

## Dataset

A sample sales dataset was used containing the following attributes:

* Date
* Product
* Region
* Sales
* Profit

The dataset represents sales transactions for different products across multiple regions.

---

## Data Visualization

Two visualization techniques were used to explore the dataset:

### Scatter Plot

A scatter plot was created to analyze the relationship between **Sales** and **Profit**.

**Insight:**
The scatter plot indicates a positive relationship between sales and profit. As sales increase, profit also tends to increase.

### Bar Chart

A bar chart was generated to compare **total sales by product category**.

**Insight:**
The chart shows that **laptops generate the highest total sales**, followed by phones and tablets, suggesting laptops have the strongest demand in the dataset.

---

## Data Preprocessing

Several preprocessing techniques were applied to prepare the dataset for analysis.

### Handling Missing Values

Missing values were checked using `df.isnull().sum()`. No missing values were detected in the dataset, but the mean replacement technique was demonstrated as a preprocessing method.

### Outlier Detection

The **Interquartile Range (IQR)** method was used to identify potential outliers in the Sales column. The analysis indicated that no outliers were present.

### Data Reduction

Data reduction techniques were applied by:

* Sampling a subset of the dataset
* Removing less relevant columns such as the Date attribute

### Data Scaling

Min-Max scaling was applied to normalize the Sales values, transforming them into a range between 0 and 1.

---

## Statistical Analysis

Several statistical techniques were applied to understand the dataset.

### Dataset Overview

The dataset structure and summary statistics were explored using:

* `df.info()`
* `df.describe()`

### Central Tendency Measures

The following measures were calculated:

* Minimum
* Maximum
* Mean
* Median
* Mode

### Dispersion Measures

The following dispersion statistics were calculated:

* Range
* Quartiles
* Interquartile Range (IQR)
* Variance
* Standard Deviation

### Correlation Analysis

A correlation matrix was generated to analyze relationships between numerical variables. The analysis showed a strong positive correlation between **Sales** and **Profit**.

---

## Challenges

One challenge during this lab was ensuring that preprocessing techniques such as outlier detection and scaling were implemented correctly even when the dataset contained no missing values or outliers. Additionally, organizing screenshots and maintaining a clear notebook structure required careful attention.

---

## Conclusion

This lab demonstrated the importance of data visualization, preprocessing, and statistical analysis in understanding datasets. Through the use of Python tools, it was possible to uncover relationships between variables, prepare data for modeling, and summarize key statistical characteristics of the dataset.
