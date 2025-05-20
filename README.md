# 🧠  US Census Income Analysis using Orange

**Author: Christian Ifashe** | **date: 2025-02-20**

## 📚 Table of Contents

- [📁 Datasets Used](#-datasets-used)
- [🔍 Project Overview](#-project-overview)
  - [1. 🧹 Data Preprocessing](#1--data-preprocessing)
  - [2. ⚖️ Fairness in Income Distribution](#2--fairness-in-income-distribution)
  - [3. 🤖 Income Prediction](#3--income-prediction)
  - [4. 🗳️ US Election Demographics](#4--us-election-demographics)
  - [5. 🔬 Independent Data Mining Investigation](#5--independent-data-mining-investigation)
- [📝 Notes](#-notes)

## Introduction
Welcome to my data mining project. This project explores income patterns and demographic factors using anonymized US census data. The entire analysis was conducted using the **Orange Data Mining** platform.
The project report can be accessed [here](https://github.com/ifashec123/Census-Data-Analysis-Orange/blob/main/dataminingcw_report_2.pdf)

## 📁 Datasets Used
- `Census_data.csv`: Contains demographic and income data for individuals in the US. (9 x 1.04 million)
- `Attribute_values.csv`: Maps numerical attribute codes to human-readable labels. (2 x 856)
- `voting_2020.csv`: Provides state-level results for the 2020 US presidential election. (15 x 548)

## 🔍 Project Overview

This project involved several stages of analysis, with a focus on both descriptive and predictive data mining tasks. The core components of the project include:

### 1. 🧹 Data Preprocessing
- Reduced the dataset to 5,000 records for faster computation.
- Decoded numeric attributes into readable formats (e.g., states, race, sex).
- Handled missing data and outliers.
- Grouped and recoded features such as education, occupation, and place of birth.
- Conducted exploratory data analysis using visualizations and summary statistics.

### 2. ⚖️ Fairness in Income Distribution
- Visualized income and log-income distributions using histograms and Zipf plots.
- Investigated income disparities by sex, race (white vs. non-white), and birthplace (US vs. non-US).
- Performed statistical t-tests to assess bias significance.
- Analyzed correlations between income/log-income and age, hours worked, and education.

### 3. 🤖 Income Prediction
- Explored the relationship between income and years of education.
- Estimated average monetary gains per year of education.
- Created a binary income classification: "low income" vs. "high income".
- Trained and compared at least 5 classification models.
- Performed feature ranking and model explainability using SHAP and permutation importance.
- Assessed alignment between explainability results and feature rankings.

### 4. 🗳️ US Election Demographics
- Mapped 2020 election results, mean income, and educational attainment by state.
- Visually compared geographic patterns across variables.
- Tested the hypotheses:
  - "Low-income states voted for Trump."
  - "States with high educational attainment voted for Biden."

### 5. 🔬 Independent Data Mining Investigation
- Developed and tested an original hypothesis using the dataset.
- Applied relevant visual, statistical, and modeling techniques.
- Justified methodological choices and used rigorous statistical validation.

## 📝 Notes
- All analysis was conducted using **Orange**, a visual data mining tool.
- Screenshots of results (not step-by-step) are included in the report to verify outcomes.

Heres a link to the [project report](https://github.com/ifashec123/Census-Data-Analysis-Orange/blob/main/dataminingcw_report_2.pdf)
---

Thank you for exploring this project! Feel free to browse the files and visuals to see how data mining techniques can uncover patterns in socioeconomic data.
