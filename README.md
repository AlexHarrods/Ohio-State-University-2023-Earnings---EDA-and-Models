# Ohio State University 2023 Earnings - EDA and Models

## Overview

This project provides an exploratory data analysis (EDA) of **The Ohio State University 2023 Combined Earnings** dataset. It explores the structure of the data, investigates object and numerical variables, and delves into gender pay gap analysis through various visualizations and statistical techniques. This repository includes not only the EDA but also model implementations to identify outliers and patterns in the earnings data.

## About the Dataset
The **Ohio State University 2023 Combined Earnings** dataset provides salary and position information for faculty and staff. The data has fields such as gender, position group, gross pay, and more. The analysis focuses on identifying patterns, such as gender pay disparities and position-related pay trends.

## Analyze Object Data

We start by analyzing the categorical variables, focusing on the distribution of **gender** and **position groups**. The goal is to understand how evenly these variables are represented in the dataset. Then we explore how gender distribution varies across different position groups. We generate visualizations to uncover any observable trends or imbalances.

## Analyze Numerical Data

We provide a detailed summary of the numerical variables in the dataset, focusing on gross pay and related earnings fields. Then we identify the top-paying jobs at Ohio State University, and evaluate how these earnings are distributed across various factors like gender and position.

Gross pay is categorized into meaningful brackets, allowing us to observe the distribution of earnings across different groups. We calculate the **mean gross pay** by gender, evaluate **pay brackets by gender**, and look at the interaction between **gender, gross pay, and position groups**.

## Outliers

We analyze boxplots and assess the skewness and kurtosis of the dataset to understand the distribution of the numerical variables. Correlation analysis is conducted to identify the relationships between key numerical variables like gross pay, regular pay, and position groups.

We explore bivariate outliers by plotting **gross pay** against **regular pay** to identify any data points that deviate significantly from the general trend.

To automate the detection of outliers, we implement the **Isolation Forest** algorithm, highlighting potential anomalies in the dataset.

## Models

This section will feature regression models used to gain further insights from the data and see how different algorithms deal with outliers.

---

## Conclusion
The analysis highlights key findings about the pay structure at Ohio State University, with a focus on understanding gender pay disparities. The project uses both traditional EDA techniques and machine learning algorithms to provide a comprehensive analysis of the dataset.
