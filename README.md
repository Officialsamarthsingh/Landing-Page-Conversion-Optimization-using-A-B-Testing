# Landing Page Conversion Optimization using A/B Testing

## Project Overview

This project analyzes the effectiveness of a redesigned landing page using A/B Testing. The objective was to determine whether the new landing page significantly improves user conversion rates compared to the existing version.

Using statistical hypothesis testing, confidence intervals, and exploratory data analysis, the project evaluates whether the observed difference in conversion rates is meaningful enough to support a business decision.

---

## Business Problem

An e-commerce company introduced a new landing page design to increase user conversions. Before deploying the new design to all users, the company wanted to validate whether the change resulted in a statistically significant improvement in conversion performance.

## Business Question

Should the company replace the existing landing page with the new version?

---

### Dataset Information

Attribute          | Value
Total Records      | 294,478
Experiment Groupsb | Control / Treatment
Outcome Variable   | Converted (1) / Not Converted (0)
Traffic Allocation | Approximately 50/50 Split
Experiment Type    | A/B Testing

Key Columns

- user_id
- timestamp
- group
- landing_page
- converted

---

### Project Workflow

1. Data Understanding
2. Data Cleaning and Validation
3. Exploratory Data Analysis (EDA)
4. Experiment Validation
5. Hypothesis Testing
6. Confidence Interval Analysis
7. Business Recommendations

---

### Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Jupyter Notebook

---

### Exploratory Data Analysis

The analysis included:

- User distribution across control and treatment groups
- Conversion rate comparison
- Hourly conversion trends
- Daily traffic analysis
- Daily conversion trends
- Weekday conversion analysis

The experiment showed balanced traffic allocation and stable user behavior throughout the testing period.

---

### Statistical Analysis

- Null Hypothesis (H₀)

The new landing page does not improve the conversion rate compared to the existing landing page.

 - Alternative Hypothesis (H₁)

The new landing page improves the conversion rate compared to the existing landing page.

### Statistical Method

A Two-Proportion Z-Test was performed to compare conversion rates between the control and treatment groups.

### Results

Metric              | Value
Z-Statistic         | -1.311
P-Value             | 0.905
Confidence Interval | [-0.38%, +0.08%]

---

### Key Findings

- Traffic was evenly distributed between experimental groups.
- The treatment page showed a slightly lower conversion rate than the control page.
- The observed difference was not statistically significant.
- The confidence interval included zero, indicating uncertainty regarding any real performance improvement.
- There was insufficient evidence to conclude that the new landing page improved conversions.

---

### Business Recommendation

Based on the statistical analysis, the new landing page should not be deployed at this time.

The experiment did not demonstrate a significant improvement in conversion performance. Future testing should focus on alternative page designs, audience segmentation, and additional experimentation to identify opportunities for conversion optimization.

---

### Repository Structure

Landing_Page_Conversion_Optimization_using_AB-Testing/
│
├── data/
├── notebooks/
├── presentation/
├── images/
├── README.md
└── requirements.txt

---

## Author

### Samarth Singh

Aspiring Data Analyst with a focus on business analytics, experimentation, statistics, and data-driven decision-making.
