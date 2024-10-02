# Banking_Analysis
![example](assets/How-to-analyse-banks-300x200.png)

## Problem statement
Understanding the factors that predict loan defaults ('charged-off') is essential for
optimizing risk management and reducing financial losses in the largest online loan marketplace.

## Methodology 
We will start by gathering loan data and conducting univariate analysis to understand the
distribution and summary statistics of variables such as Loan Status, Home Ownership, Grades, Verification
Status, etc. Next, bivariate analysis will explore relationships between these variables and loan default status
('charged-off'), identifying significant correlations and trends. These insights will guide targeted strategies for
risk assessment and management based on empirical data patterns.

## Getting Started
### Prerequisites
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, sklearn, scipy, imblearn

### Installation
- Clone the repository
```
git clone https://github.com/username/project.git
```
- Install required libraries
```
pip install pandas numpy matplotlib seaborn sklearn scipy imblearn
```

## Usage
Run the following command in the terminal to execute the project:
```
python main.py
```
## Overview of the Code

### 1. Exploratory Data Analysis

- Loading data
- Printing random sample of 10 rows to check data loading
- Printing data overview
- Printing numerical summary for Time and Amount columns
- Plotting distribution of Time feature
- Plotting distribution of Amount feature
- Counting number of fraud vs non-fraud transactions and displaying them with their ratio
- Plotting count of fraud vs non-fraud transactions in a bar chart

### 2. Data Processing

- Plotting heatmap to find any high correlations between variables
