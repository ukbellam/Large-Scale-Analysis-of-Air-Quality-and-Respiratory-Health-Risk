# Large-Scale-Analysis-of-Air-Quality-and-Respiratory-Health-Risk
This project examines how air pollutants (PM2.5, PM10, NO₂, CO, O₃) affect respiratory health outcomes using large-scale data to uncover key risk factors and support data-driven public health improvements.
Large-Scale Analysis of Air Quality and Respiratory Health Risk
Overview

This project analyzes the relationship between air quality indicators (PM2.5, PM10, NO₂, SO₂, CO, and O₃) and respiratory health outcomes (asthma, COPD, and lung infections) using large-scale environmental datasets. The goal is to understand how pollution levels affect respiratory health risks across different regions and time periods and to support data-driven public health decisions for improving air quality.

Objectives

Process large-scale air pollution datasets efficiently using Apache Spark (PySpark)
Clean, preprocess, and normalize pollutant readings
Perform statistical and machine learning analysis to identify pollution–health relationships
Apply Principal Component Analysis (PCA) to reduce dimensionality while retaining key variance
Evaluate Spark’s performance on single and multiple virtual machines

Dataset

Dataset: U.S. Pollution Data (2000–2016)
Source: https://www.kaggle.com/datasets/sogun3/uspollution
Contains over 1.4 million records with daily pollutant levels (PM2.5, O₃, SO₂, NO₂, CO) and geographical details

Methodology

Data Ingestion – Load multiple CSV files into Spark DataFrames
Preprocessing – Handle missing values, smooth noisy data, and normalize features
Statistical Analysis – Perform correlation, regression, and chi-square tests
Dimensionality Reduction (PCA) – Reduce correlated variables into fewer uncorrelated components
Performance Testing – Compare Spark execution speed on single vs. multiple VMs

Tools and Technologies

Apache Spark (PySpark)
Spark SQL and MLlib
Python Libraries: pandas, numpy, matplotlib, seaborn
Environment: Hadoop cluster, Jupyter Notebook, or Google Colab

Team Contributions

Dennis Owusu – Correlation Analysis
Mary Nnipaa Meteku – Data Cleaning and Missing Value Handling
Uttam Kumar Bellamkonda – Regression Analysis
Fredrick Damptey – Chi-Square Test for Feature Selection
Sucharitha Reddy Dammareddygari – Dimensionality Reduction (PCA)

Expected Outcomes

A clean and well-structured dataset for air quality analysis
Identification of key pollutants linked to poor air quality and respiratory health risks
PCA components summarizing main pollution trends
Performance comparison of Spark in distributed environments
Insights supporting public health and air quality improvement strategies
