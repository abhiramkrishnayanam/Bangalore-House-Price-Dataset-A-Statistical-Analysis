# Bangalore-House-Price-Dataset-A-Statistical-Analysis

This repository documents the analysis of the **Bangalore House Price Dataset** with a focus on data cleaning, exploratory analysis, and outlier handling using statistical techniques.  

---

## Table of Contents  
1. [Introduction](#introduction)  
2. [Dataset Overview](#dataset-overview)  
3. [Objectives](#objectives)  
4. [Key Tasks](#key-tasks)  
5. [Outlier Detection Methods](#outlier-detection-methods)  
6. [Tools Used](#tools-used)  
7. [Conclusion](#conclusion)  

---

## Introduction  

This project analyzes Bangalore's real estate data, emphasizing price-per-square-foot statistics, outlier detection, and data cleaning.  

---

## Dataset Overview  

- **Entries**: 13,200 (reduced to 12,151 after cleaning)  
- **Columns**:  
  - location  
  - size  
  - total_sqft  
  - bath  
  - price  
  - bhk  
  - price_per_sqft  

---

## Objectives  

1. Perform data cleaning and exploratory data analysis (EDA).  
2. Identify and handle outliers in `price_per_sqft`.  
3. Prepare the dataset for accurate analysis or modeling.  

---

## Key Tasks  

- Removed 1,049 duplicate rows.  
- Identified and handled outliers using multiple statistical techniques.  
- Verified dataset integrity after cleaning.  
- Histograms and Box plot were plotted to find oultliers.
- Heatmap and Scatter Plot were plotted to check the correlation between numerical columns.

---

## Outlier Detection Methods  

1. **Mean and Standard Deviation**: Trimmed extreme deviations from the mean.  
2. **Percentile Method**: Capped data within the 5th and 95th percentiles.  
3. **Interquartile Range (IQR)**: Addressed outliers using upper and lower bounds.  
4. **Z-Score Method**: Validated with no further outliers detected.  

---

## Tools Used  

- **Python Libraries**:  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  

---

## Conclusion  

The dataset is now free of duplicates and outliers, making it suitable for further analysis or machine learning applications.  

---
