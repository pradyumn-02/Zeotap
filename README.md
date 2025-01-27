# Zeotap
Zeotap Data Science assignment
# eCommerce Transactions Dataset Analysis

## Overview

This project involves analyzing an eCommerce transactions dataset with **Customers.csv**, **Products.csv**, and **Transactions.csv**. The objectives are to perform **Exploratory Data Analysis (EDA)**, implement **Customer Segmentation** using clustering, and build a **Lookalike Model**. The analysis generates actionable insights and models to improve business decisions.

## Key Findings

- **Number of clusters**: 4
- **Davies-Bouldin Index**: 0.8651
- **Cluster Summary**:

  | Cluster | Avg Total Value | Avg Quantity | Avg Transaction Date |
  |---------|-----------------|--------------|----------------------|
  | 0       | 6263.45         | 23.00        | 8.43                 |
  | 1       | 1273.37         | 5.27         | 2.36                 |
  | 2       | 2982.41         | 10.87        | 4.39                 |
  | 3       | 4477.57         | 16.10        | 6.31                 |

## Installations

Install dependencies:

```bash
pip install pandas numpy sklearn matplotlib seaborn
