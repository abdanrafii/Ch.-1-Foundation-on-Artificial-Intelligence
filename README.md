# Ch.-1-Foundation-on-Artificial-Intelligence

# Foundation on Artificial Intelligence - Chapter 1

This repository contains assignments for Chapter 1 of the Foundation on Artificial Intelligence course. The assignments are designed to enhance understanding of Python programming, data manipulation, and visualization.

## Assignment Files
1. **01_Kelompok_B_2.ipynb**: Contains code for simulating a bank’s cash disbursement process based on customer savings amount.
2. **01_Kelompok_B_3.ipynb**: Contains data analysis tasks using the `HRDataset_v14.csv` dataset, including data aggregation, filtering, and visualization.

---

### 01_Kelompok_B_2.ipynb
This notebook focuses on helping a bank calculate the distribution of cash denominations (paper money and coins) based on a customer's requested amount.

#### Features:
- **Cash Calculation Logic**: Calculates the necessary number of each denomination, prioritizing larger bills.
- **Error Handling**: Handles inputs beyond the 1 billion Rupiah limit and invalid inputs.
- **Denomination Details**: Outputs the number of bills and coins for each denomination and the remaining uncashed amount, if any.

#### Sample Output:
```
Amount of currency Rp 100,000: 5
Amount of currency Rp 50,000: 3
...
Total Paper Money: 10
Total Coins: 5
Cannot be cashed out: 50
```

---

### 01_Kelompok_B_3.ipynb
This notebook involves data analysis tasks on employee data, using various aggregation functions and visualizations.

#### Key Analyses:
1. **Salary Statistics**: Computes min, median, max, and average salaries by marital status and gender.
2. **Top Termination Reasons**: Identifies the top 5 termination reasons.
3. **Employee Performance**: Determines recruitment sources for employees with high performance.
4. **Manager Count by Department**: Counts managers per department.
5. **Termination Ratios**: Calculates termination ratios by gender.

#### Visualizations:
- Scatter plots, bar charts, and pie charts for employee data insights.
- Boxplots and pair plots to illustrate salary distribution and termination factors.

### How to Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/abdanrafii/Ch.-1-Foundation-on-Artificial-Intelligence.git
   ```
2. **Install Dependencies**:
   Use `pip install -r requirements.txt` if there's a requirements file. Common libraries used include `pandas`, `matplotlib`, and `seaborn`.
3. **Open Jupyter Notebooks**:
   Open `01_Kelompok_B_2.ipynb` and `01_Kelompok_B_3.ipynb` in Jupyter Notebook or JupyterLab to run the code and explore the data analysis.

---
