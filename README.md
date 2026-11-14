# Tiki-E-Commerce-Product-Sales-Seller-Performance-Analysis
# Tiki E-Commerce Sales Drivers: End-to-End Data Analysis & Hypothesis Testing

## Overview
This project investigates the key determinants driving product sales performance on **Tiki**, one of Vietnam's major e-commerce platforms. Using an end-to-end data analytics pipeline—from automated API data collection to rigorous statistical hypothesis testing—the analysis evaluates how pricing strategies, customer feedback, product listing quality, and seller reputation impact cumulative sales volume across 10 distinct product categories.

---

## Repository Structure

```text
tiki-ecommerce-sales-analysis/
├── data_raw/                                        # Raw CSV datasets extracted via Tiki APIs (*_raw.csv)
├── data_processed/                                  # Cleaned, merged, and feature-engineered datasets
├── results/                                         # Statistical test outputs (tiki_hypothesis_results.xlsx) & figures
├── 01_tiki_api_data_collection.ipynb                # Automated API scraper across 10 product categories
├── 02_data_cleaning_and_feature_engineering.ipynb   # Data merging, Isolation Forest anomaly detection, & feature creation
├── 03_univariate_exploratory_analysis.ipynb         # Descriptive statistics, distribution checks, & log1p transformations
├── 04_multivariate_eda_and_multicollinearity.ipynb  # Correlation analysis, VIF, ICC seller effects, & Tiki Trading segmentation
├── 05_statistical_hypothesis_testing.ipynb          # Hypothesis testing (9 hypotheses), Holm-Bonferroni correction, & robustness checks
└── README.md
