# Ohio State University 2023 Earnings - EDA and Models

## Overview

In this project, I conduct an exploratory data analysis (EDA) of **The Ohio State University 2023 Combined Earnings** dataset. I examine the structure of the data, investigate both categorical and numerical variables, and explore the gender pay gap through various visualizations and statistical techniques. This repository includes not only my EDA but also model implementations to identify outliers and detect patterns in earnings data.

## About the Dataset

The **Ohio State University 2023 Combined Earnings** dataset includes salary and position information for faculty and staff, with fields like gender, position group, and gross pay. My analysis focuses on identifying patterns, such as gender pay disparities and position-related pay trends.

## Analyzing Categorical Data

I begin by analyzing the categorical variables, particularly the distributions of **gender** and **position groups**. My goal is to understand the representation of these categories across the dataset. I also explore gender distribution within different position groups, generating visualizations to reveal trends or imbalances.

## Analyzing Numerical Data

Next, I provide a detailed summary of the numerical variables, focusing on gross pay and related earnings fields. I identify the highest-paying jobs at Ohio State University and analyze how earnings are distributed by factors like gender and position.

I categorize gross pay into meaningful brackets to observe earnings distribution across various groups. Additionally, I calculate the **mean gross pay** by gender, analyze **pay brackets by gender**, and examine the interaction between **gender, gross pay, and position groups**.

## Outlier Detection

To understand the distribution of numerical variables, I analyze boxplots and assess skewness and kurtosis. I conduct correlation analysis to explore relationships between variables like gross pay, regular pay, and position groups.

I investigate bivariate outliers by plotting **gross pay** against **regular pay** to find data points that significantly deviate from the general trend. To automate outlier detection, I use the **Isolation Forest** algorithm, which highlights potential anomalies in the dataset.

## Modeling

In this section, I implement regression models to gain further insights from the data and evaluate how different algorithms handle outliers.

---

## Conclusion

My analysis uncovers key insights into the pay structure at Ohio State University, particularly around gender pay disparities. By combining traditional EDA techniques with machine learning algorithms, I provide a comprehensive analysis of the dataset.
