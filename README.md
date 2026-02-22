# statistics-trends-assignment
# Statistics and Trends Assignment  
## Stock Market Analysis – July 2025

### Overview

This project analyses daily stock market data for July 2025.  
The objective of this assignment is to apply data cleaning, statistical analysis, and data visualisation techniques using Python.

The analysis includes:

- A relational plot (line graph of stock prices)
- A categorical plot (histogram of daily returns)
- A statistical plot (correlation heatmap)
- Calculation and interpretation of the four main statistical moments:
  - Mean
  - Standard Deviation
  - Skewness
  - Kurtosis

This project demonstrates the use of data preparation techniques and version control using Git.

---

## Dataset

The dataset contains daily stock market information for July 2025, including:

- Date
- Ticker
- Open Price
- Close Price
- High Price
- Low Price
- Volume Traded
- Market Cap
- PE Ratio
- Dividend Yield
- EPS
- 52 Week High
- 52 Week Low
- Sector

Four stocks with the highest number of observations were selected to ensure sufficient data for statistical analysis.

---

## Methods

### 1. Data Cleaning
- Converted the `Date` column to datetime format
- Sorted data by ticker and date
- Calculated daily percentage returns
- Removed missing values generated from return calculation

### 2. Relational Analysis
A line plot was created to visualise stock price movements over time.

### 3. Distribution Analysis
Histograms were used to analyse the distribution of daily returns for each stock.

### 4. Statistical Analysis
A correlation heatmap was created to evaluate relationships between stock returns.

The four statistical moments were computed for each stock:

- **Mean** – Average daily return  
- **Standard Deviation** – Volatility (risk)  
- **Skewness** – Asymmetry of return distribution  
- **Kurtosis** – Presence of heavy tails or extreme values  

---

## Key Observations

- Volatility differs across sectors.
- Correlation analysis indicates varying levels of co-movement between stocks.
- Skewness and kurtosis suggest that return distributions may deviate from normality.
- Due to the limited time horizon (one month), higher-order moments may be sensitive to short-term fluctuations.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook
- Git & GitHub

---

## Version Control

This project was managed using Git.  
Commits were made during development to track progress and maintain reproducibility.

---

## How to Run

1. Open the Jupyter Notebook file.
2. Ensure the dataset CSV file is in the same directory.
3. Run all cells sequentially.
4. Visualisations and statistical outputs will be generated automatically.

---

## Author

Sindhu Mandadi
Statistics and Trends Module
