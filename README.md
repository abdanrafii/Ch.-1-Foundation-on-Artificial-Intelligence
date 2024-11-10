---

# Foundations of Artificial Intelligence - Chapter 1 (Team Project in Google Colab)

This repository contains team-based assignments in foundational AI topics, focused on programming, data analysis, and visualization. The tasks are designed to build understanding through practical applications on real-world data.

---

## Notebooks Overview

### 1. Cash Denomination Calculation (`01_Kelompok_B_2.ipynb`)

This notebook demonstrates a Python solution for calculating Indonesian currency denominations based on a specified balance, taking into account the range of available banknotes and coins.

- **Goal**: Calculate the quantity of each denomination required to fulfill a given balance up to Rp 1 billion, displaying any remaining balance that cannot be withdrawn.
  
- **Key Steps**:
  1. **Input Validation**: Ensures the input is an integer within the acceptable range (Rp 0 to Rp 1 billion).
  2. **Denomination Calculation**: Prioritizes larger denominations, calculating the required quantities for banknotes and coins.
  3. **Output**: Displays a breakdown of banknotes and coins, with total counts and an indication of any residual amount.

---

### 2. Data Analysis & Visualization (`01_Kelompok_B_3.ipynb`)

This notebook explores the HRDataset to perform various data analyses and generate visualizations, showcasing key insights about salary distribution, performance scores, terminations, and more.

- **Goal**: Conduct detailed data analysis and visualizations on employee data to uncover patterns and trends.

- **Key Analyses**:
  - **Salary Statistics by Marital Status and Gender**: Compute minimum, median, maximum, and average salary statistics.
  - **Top-5 Reasons for Termination**: Identifies the most common termination reasons.
  - **Performance by Recruitment Source**: Analyzes recruitment sources linked to high performance scores.
  - **Manager Count by Department**: Counts unique managers in each department.
  - **Termination Ratio by Gender**: Calculates the termination ratio segmented by gender.

- **Key Visualizations**:
  1. **Termination Ratio by Gender**: A bar chart of termination ratios by gender.
  2. **Salary vs. Engagement Survey**: Scatter plot with colors indicating termination status.
  3. **Terminations by Department**: Bar chart showing termination counts per department.
  4. **Termination Percentages by Position**: A pie chart illustrating position-based termination percentages.
  5. **Salary Distribution by Marital Status and Termination Status**: Boxplot of salaries based on marital and termination status.
  6. **Relationship Analysis**: Pairplot of key metrics (e.g., salary, engagement, satisfaction, absences) by termination status.

---

## Running the Notebooks

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the `.ipynb` files (`01_Kelompok_B_2.ipynb` and `01_Kelompok_B_3.ipynb`) to Colab.
3. For `01_Kelompok_B_3.ipynb`, make sure the HR dataset is accessible (either via the provided URL or by uploading the dataset directly).

---

This README provides an overview for easy navigation and clear instructions to run the code and interpret the results, making it an ideal reference for project replication and further development.

---
