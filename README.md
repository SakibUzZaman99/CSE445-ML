# Los Angeles City Data Analysis: Employee Payroll and Crime Statistics

## Overview

This project explores two significant public datasets from the City of Los Angeles: **Employee Payroll** and **Crime Data** from 2020 to the present. It applies various analytical approaches, including regression analysis for payroll data, and classification and unsupervised learning for crime data. The goal is to identify meaningful patterns and insights that can aid in city resource allocation, policy development, and public safety strategies.

## Table of Contents

- [Introduction](#introduction)
- [Methodology](#methodology)
- [Data Preprocessing](#data-preprocessing)
- [Regression Analysis](#regression-analysis)
- [Classification Analysis](#classification-analysis)
- [Unsupervised Analysis](#unsupervised-analysis)
- [Conclusion](#conclusion)
- [Installation](#installation)
- [Usage](#usage)
- [References](#references)
- [Acknowledgements](#acknowledgements)

## Introduction

The project analyzes two crucial datasets:
1. **City Employee Payroll**: Contains details about job titles, departments, pay scales, and benefits of Los Angeles city employees.
2. **Crime Data**: Provides information on crime incidents across Los Angeles from 2020 to the present, including crime types, locations, and dates.

The analysis focuses on:
- Predicting employee total pay based on job-related factors.
- Categorizing crimes based on available features.
- Discovering hidden crime patterns through unsupervised learning.

## Methodology

### Data Sources
1. **City Employee Payroll (Current)** - Available from the Los Angeles Controller’s Office.
2. **Crime Data from 2020 to Present** - Available from the Los Angeles Open Data Portal.

### Techniques Used
- Regression analysis on payroll data.
- Classification analysis on crime data.
- Unsupervised learning (clustering and dimensionality reduction) on crime data.

## Data Preprocessing

- **Handling Missing Values**: Removal of incomplete records and columns with substantial null values.
- **Feature Selection**: Dropped redundant or irrelevant variables to improve model performance.
- **Categorical Encoding**: Encoded non-numerical features to enable numerical analysis.
- **Outlier Detection**: Used correlation analysis and heatmaps to identify outliers.

## Regression Analysis

### Models Used:
- Linear Regression
- Random Forest
- XGBoost
- KNN
- Neural Network

**Key Results:**
- XGBoost Regression provided the best performance with an R-squared value of 0.9975 and low error metrics.

## Classification Analysis

### Models Used:
- Logistic Regression
- Random Forest
- XGBoost
- KNN

**Key Findings:**
- The XGBoost classifier achieved 98% accuracy, with strong precision and recall values.
- Key predictors for crime included location, time of day, and weapon type.

## Unsupervised Analysis

- **PCA**: Reduced the feature space to 2D, capturing 85% of the variance in the data.
- **Clustering Techniques**: K-means, Hierarchical Clustering, DBSCAN were applied to identify crime patterns.

## Conclusion

This analysis provides valuable insights into employee compensation and crime dynamics in Los Angeles. The regression models for payroll data identified job type and department as key determinants. The classification and unsupervised models for crime data revealed significant patterns in crime 
