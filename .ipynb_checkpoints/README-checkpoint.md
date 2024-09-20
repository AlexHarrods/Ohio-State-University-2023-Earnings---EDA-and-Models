# Ohio State University 2023 Earnings - EDA and Models

## Overview

This project provides an exploratory data analysis (EDA) of **The Ohio State University 2023 Combined Earnings** dataset. It explores the structure of the data, investigates object and numerical variables, and delves into gender pay gap analysis through various visualizations and statistical techniques. This repository includes not only the EDA but also model implementations to identify outliers and patterns in the earnings data.

# Table of Contents

1. [Import Necessary Libraries](#1-import-necessary-libraries)
2. [About the Dataset](#2-about-the-dataset)
3. [Load the Dataset](#3-load-the-dataset)
4. [Overview of the Dataset](#4-overview-of-the-dataset)
5. [Presence of negative values](#5-presence-of-negative-values)
   - 5.1 Possible explanations
   - 5.2 Compare to data from other university
6. [Analyze Object Data](#6-analyze-object-data)
    - 6.1 Analyze frequencies/percentages of some data
        - 6.1.1 Gender
        - 6.1.2 Position Groups
    - 6.2 Gender and Position Groups
7. [Analyze Numerical Data](#7-analyze-numerical-data)
    - 7.1 Overview
        - 7.1.1 Visualizations of Distributions
        - 7.1.2 Observations
    - 7.2 Highest Paying Jobs
    - 7.3 Gross Pay Categories Distribution
    - 7.4 Gross Pay by Position Group
        - 7.4.1 Mean and Median Gross Pay by Position Group
        - 7.4.2 Mean and Median Gross Pay by Gender and Position Group
    - 7.5 Gross Pay and Gender
        - 7.5.1 Mean Gross Pay by Gender
        - 7.5.2 Gross Pay Categories by Gender
8. [Outliers](#8-outliers)
    - 8.1 Boxplot visualization
        - 8.1.1 Boxplots by Position Group
        - 8.1.2 Boxplots by Position Group and Gender
    - 8.2 Skewness and Kurtosis
    - 8.3 Correlation
    - 8.4 Bivariate Outliers: Gross Pay and Regular Pay
        - 8.4.1 Observations
    - 8.5 Using Isolation Forest to Find Outliers
    - 8.6 Conclusion on Outliers
9. [Models](#9-models)
10. [Final Analysis](#10-final-analysis)

## 1. Import Necessary Libraries

The project starts by importing the necessary libraries to handle data manipulation, visualization, and modeling.

## 2. About the Dataset

The **Ohio State University 2023 Combined Earnings** dataset provides salary and position information for faculty and staff. The data has fields such as gender, position group, gross pay, and more. The analysis focuses on identifying patterns, such as gender pay disparities and position-related pay trends.

## 3. Load the Dataset

We load the dataset using `pandas`, and conduct initial checks to understand the size, structure, and quality of the data.

## 4. Overview of the Dataset

A summary of the dataset is provided here, including the number of entries, key columns, and data types. 

## 5. Analyze Object Data

We start by analyzing the categorical variables, focusing on the distribution of **gender** and **position groups**. The goal is to understand how evenly these variables are represented in the dataset. Then we explore how gender distribution varies across different position groups. We generate visualizations to uncover any observable trends or imbalances.

## 6. Analyze Numerical Data

We provide a detailed summary of the numerical variables in the dataset, focusing on gross pay and related earnings fields. Then we identify the top-paying jobs at Ohio State University, and evaluate how these earnings are distributed across various factors like gender and position.

Gross pay is categorized into meaningful brackets, allowing us to observe the distribution of earnings across different groups. We calculate the **mean gross pay** by gender, evaluate **pay brackets by gender**, and look at the interaction between **gender, gross pay, and position groups**.

## 7. Outliers

We analyze boxplots and assess the skewness and kurtosis of the dataset to understand the distribution of the numerical variables. Correlation analysis is conducted to identify the relationships between key numerical variables like gross pay, regular pay, and position groups.

We explore bivariate outliers by plotting **gross pay** against **regular pay** to identify any data points that deviate significantly from the general trend.

To automate the detection of outliers, we implement the **Isolation Forest** algorithm, highlighting potential anomalies in the dataset.

## 8. Models

This section will feature regression models used to gain further insights from the data and see how different algorithms deal with outliers.

---

## Conclusion

The analysis highlights key findings about the pay structure at Ohio State University, with a focus on understanding gender pay disparities. The project uses both traditional EDA techniques and machine learning algorithms to provide a comprehensive analysis of the dataset.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/OSU-2023-Earnings-EDA.git
