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

### How to Run in Google Colab
1. **Open Google Colab**:
   - Go to [Google Colab](https://colab.research.google.com/) and sign in with your Google account.

2. **Upload Notebooks**:
   - Upload `01_Kelompok_B_2.ipynb` and `01_Kelompok_B_3.ipynb` by selecting **File > Upload Notebook**.

3. **Install Required Libraries**:
   - Once the notebook is open, run the following command to install necessary libraries:
     ```python
     !pip install pandas matplotlib seaborn
     ```

4. **Load the Dataset**:
   - In **01_Kelompok_B_3.ipynb**, the dataset `HRDataset_v14.csv` is loaded directly from a URL. Ensure your internet connection is active so the notebook can retrieve the data:
     ```python
     data = pd.read_csv('https://raw.githubusercontent.com/Rietaros/kampus_merdeka/main/HRDataset_v14.csv')
     ```

5. **Run the Cells**:
   - Go through each cell in the notebook and execute it to see outputs and visualizations.
