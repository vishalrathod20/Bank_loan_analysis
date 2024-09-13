# Bank Analysis Project

## Overview

The Bank Analysis Project is a comprehensive examination of banking data using Excel. This project aims to uncover insights into banking operations, including customer behavior, transaction patterns, and branch performance. The repository includes both the dataset and the problem statement files to facilitate the analysis.

## Project Structure

- **`dataset/`**: Contains the data files used for analysis.
  - `financial_loan.xlsx`: The primary dataset used for analysis.
- **`problem_statement/`**: Contains the problem statement and analysis goals.
  - `problem_statement.docx`: A detailed description of the problem statement and objectives.

## Dataset

The dataset provided in `financial_loan.xlsx` includes various attributes related to banking operations:

## Problem Statement

The Bank Loan Report aims to provide a comprehensive analysis of our bank's lending activities and performance. The objective is to monitor key loan metrics, evaluate the quality of loans, and visualize trends to support data-driven decision-making. Below are the specific questions and key performance indicators (KPIs) we need to address:

### Dashboard 1: Summary

1. **Total Loan Applications**
   - Calculate the total number of loan applications received during a specified period.
   - Track Month-to-Date (MTD) Loan Applications and Month-over-Month (MoM) changes.

2. **Total Funded Amount**
   - Determine the total amount of funds disbursed as loans.
   - Monitor MTD Total Funded Amount and MoM changes.

3. **Total Amount Received**
   - Track the total amount received from borrowers.
   - Analyze MTD Total Amount Received and MoM changes.

4. **Average Interest Rate**
   - Compute the average interest rate across all loans.
   - Monitor MTD average interest rate and MoM variations.

5. **Average Debt-to-Income Ratio (DTI)**
   - Calculate the average DTI for borrowers.
   - Track MTD average DTI and MoM fluctuations.

### Good Loan vs Bad Loan KPIs

1. **Good Loans**
   - **Good Loan Application Percentage**: Calculate the percentage of loan applications classified as 'Good Loans.'
   - **Good Loan Applications**: Total number of loans with status 'Fully Paid' and 'Current.'
   - **Good Loan Funded Amount**: Total amount of funds disbursed as 'Good Loans.'
   - **Good Loan Total Received Amount**: Total amount received from borrowers for 'Good Loans.'

2. **Bad Loans**
   - **Bad Loan Application Percentage**: Calculate the percentage of loan applications classified as 'Bad Loans.'
   - **Bad Loan Applications**: Total number of loans with status 'Charged Off.'
   - **Bad Loan Funded Amount**: Total amount of funds disbursed as 'Bad Loans.'
   - **Bad Loan Total Received Amount**: Total amount received from borrowers for 'Bad Loans.'

### Dashboard 2: Overview

1. **Monthly Trends by Issue Date**
   - Line Chart showing trends in 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received.'

2. **Regional Analysis by State**
   - Filled Map representing 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received' by state.

3. **Loan Term Analysis**
   - Donut Chart depicting loan statistics by different loan terms.

4. **Employee Length Analysis**
   - Bar Chart illustrating lending metrics by borrower employment length.

5. **Loan Purpose Breakdown**
   - Bar Chart showing loan metrics based on loan purposes.

6. **Home Ownership Analysis**
   - Tree Map displaying loan metrics by home ownership status.

### Dashboard 3: Details

- **Objective**: Provide a comprehensive view of all essential loan data, including key metrics, borrower profiles, and loan performance, in a user-friendly interface.

This report will help us track the health of our loan portfolio, identify trends, and inform lending strategies.

## Analysis Methodology

1. **Data Cleaning**: Handled missing values, inconsistencies, and outliers in the dataset.
2. **Data Exploration**: Performed initial exploratory analysis to understand data distribution and key statistics.
3. **Segmentation**: Categorized customers based on their transaction behaviors using clustering techniques.
4. **Trend Analysis**: Analyzed transaction amounts and frequencies over time using time-series analysis.
5. **Branch Comparison**: Compared performance metrics for different branches to identify high and low performers.
6. **Financial Insights**: Derived key financial metrics to assess the bank's financial health.

## Results and Insights

The results of the analysis are presented in the Excel file and include:

- **Customer Segmentation Report**: Detailed report on customer segments with visualizations.
- **Transaction Trends**: Graphs and charts showing transaction patterns over time.
- **Branch Performance Metrics**: Comparative analysis of branch performance.
- **Financial Health Report**: Insights into the bank's financial health based on the dataset.

## Usage

1. Download the dataset and problem statement files from this repository.
2. Open the `financial_loan.xlsx` file in Excel to view the data and analysis results.
3. Refer to the `problem_statement` file for detailed objectives and analysis goals.

## Contributing

Contributions to this project are welcome. If you have suggestions or improvements, please submit a pull request or open an issue.

