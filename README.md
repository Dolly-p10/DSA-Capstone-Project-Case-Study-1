# DSA-Capstone-Project-Case-Study-1

## Amazon Product Review Analysis

### Project Overview

This Data Analysis project explores Amazon product and customer review data to uncover actionable insights. The goal is to support better decision-making in areas like product improvement, marketing strategy, and customer engagement through structured Excel-based analysis.

### Project Problem

In a highly competitive e-commerce environment like Amazon, businesses often struggle to interpret massive volumes of product and customer review data effectively. Without proper analysis:

- High-performing products might go unnoticed
- Poor ratings may persist unaddressed
- Marketing efforts may fail to target the right product segments.

This project solves that problem by analyzing structured product data to highlight:

- Which products drive the most engagement
- How discount levels affect ratings
- Where review volume can signal potential improvements.

### Project Objectives
- Identify opportunities for product improvement
- Provide insight to guide marketing strategies
- Improve customer engagement based on reviews and ratings

### Data Sources

The dataset was sourced from a Digital Learning Management System (LMS) platform as part of a case study project.

### Data Cleaning & Preparation

The dataset was cleaned and transformed using Microsoft Excel. Key cleaning steps included:
- Removing duplicates and handling missing values
- Splitting multi-level categories
- Creating helper columns for:
  - Price range buckets
  - Discount percentage range
  - Review counts (by summing-up comma-separated review IDs)
  - Potential revenue calculations
- Formatting the dataset as a Table to enable efficient PivotTable creation

### Tools Used
Microsoft Excel used for:
- Data Import and Structuring
- Data Cleaning
- PivotTable Calculations
- Visual Dashboards with Charts

### Exploratory Data Analysis (EDA)

Key business questions answered:
- What is the total number of reviews per category?
- Which products have the highest number of reviews?
- How does the rating relate to the level of discount?
- Identify the top 5 products in terms of rating and number of reviews combined
- What is the total potential revenue by category?
- How many products have 50% or more discount?

### Data Analysis Techniques

This section include examples of Excel formulas used during the project, such as:

``` Excel formulas
=N2 * S2

=LEN(U2)-LEN(SUBSTITUTE(U2,",",""))+1

=IF(N2<10000,"<₹10,000", IF(N2<=50000,"₹10,000-₹50,000", IF(N2<=100000,"₹51,000-₹100,000",">₹100,000")))
```

### Final Analysis & Dashboard

A clean Excel dashboard was developed to visualize the insights using bar charts for categorical comparisons


