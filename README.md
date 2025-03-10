# Megaline Prepaid Plans Analysis 📊

## Overview
This project analyzes customer behavior to determine which prepaid plan—**Ultimate** or **Surf**—generates higher revenue. We use a dataset of 500 Megaline telecom clients from 2018 to conduct data-driven insights.

The analysis follows a structured approach, including data preparation, exploration, transformation, and statistical evaluation. 📈 Full details are provided in the sections below.

---

# Analysis Steps
### 1️⃣ Data Initialization & Preparation
- Import necessary libraries (`pandas`, `NumPy`, `Matplotlib`, `SciPy`).
- Check data structure (`.info()`).
- Identify and outline potential data quality issues.

### 2️⃣ Data Exploration & Quality Check
- Review descriptive statistics (`.describe()`).
- Examine sample records (`.sample()`).
- Count unique values (`.nunique()`).
- Analyze value distributions (`.value_counts()`).
- Identify missing values (`.isna().sum()`, `.notnull().sum()`).

### 3️⃣ Data Transformation
- Clean text data (`.strip()`, `.split()`).
- Convert incorrect data types.
- Handle missing values.
- Remove duplicates (if any).

### 4️⃣ Descriptive Analytics
- Merge relevant datasets.
- Create visual charts to explore trends.
- Perform statistical tests.
- Compute key metrics.

### 5️⃣ Results Summary
- Present statistical findings.
- Compare key revenue metrics between plans.
- Provide business recommendations.