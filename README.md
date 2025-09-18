# assignment3_mda

## Overview

This assignment analyzes a dataset of economic variables at the **CCAA level** (Comunidad Autónoma) using descriptive statistics and matrix-based analysis techniques. The goal is to gain hands-on experience with foundational tools in multivariate data analysis, such as:

- Mean vectors  
- Covariance and correlation matrices  
- Data standardization  
- Eigen decomposition

These are essential techniques in exploratory data analysis (EDA), dimensionality reduction, and economic modeling.

## Tasks

The assignment includes the following analytical steps:

1. **Compute the mean vector** of the dataset.
2. **Construct the centered data matrix** \( X_c \), where all variables (columns) have mean zero.
3. **Calculate the cross-product matrix**:  
   \[
   X_{pc} = X_c^T X_c
   \]
4. **Derive the covariance matrix** \( S \) using:
   \[
   S = \frac{X_c^T X_c}{n - 1}
   \]
5. **Standardize the dataset** to obtain the standardized matrix \( X_s \).
6. **Compute the correlation matrix** \( R \).
7. **Perform eigen decomposition** of both \( X_c^T X_c \) and \( S \).
8. **Construct the dispersion and correlation matrices** of \( X_s \).
9. **Extract eigenvalues and eigenvectors** from the correlation matrix.

## Purpose

This project provides practical experience in the use of **linear algebra techniques** and **descriptive statistics** as applied to **multivariate economic datasets**. These tools form the backbone of many modern techniques in economics, machine learning, and quantitative social sciences.

## Repository Contents

The repository includes:

- 📄 `Assignment.Rmd` — Main R Markdown file with code and narrative  
- 📁 `data/` — Folder containing the input dataset  
- 📁 `results/` — Output matrices, tables, and plots  
- 📄 `README.md` — This documentation file  
- 📝 Assignment instructions (in comments or separate PDF)
