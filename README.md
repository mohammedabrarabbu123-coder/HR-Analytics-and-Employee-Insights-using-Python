# HR Analytics and Employee Insights using Python

This project provides a comprehensive analysis of employee data to uncover organizational trends, gender distribution, and pay equity. By leveraging Python's data analysis and visualization libraries, this project transforms raw HR data into actionable business insights.

## Project Overview

The primary goal of this repository is to analyze HR metrics across various departments and locations. Key analyses include:

* **Demographics:** Gender distribution within the organization and across specific departments.
* **Compensation Analysis:** Identifying pay distribution and trends based on gender and location.
* **Geographic Insights:** Visualizing the workforce distribution across different office locations (e.g., Bellevue, Wellington, Los Angeles).
* **Performance Evaluation:** Analyzing employee ratings to assess organizational performance health.

## Dataset

The analysis is performed on an Excel dataset (`HR analytics.xlsx`) containing 1,015 employee records with the following attributes:

* **Name:** Employee identifier.
* **Gender:** Male or Female.
* **Department:** Organizational unit (e.g., Sales, Engineering, Support).
* **Pay:** Annual compensation.
* **Loc:** Office location.
* **Rating:** Performance scores (e.g., Very Good, Average, Poor).

## Key Features & Visualizations

The Jupyter Notebook includes several data visualizations generated with `Matplotlib` and `Seaborn`:

1. **Gender Distribution Pie Chart:** A high-level view of the organizational gender split.
2. **Departmental Heatmap:** A cross-tabulation of gender counts across different departments to identify diversity trends.
3. **Location-based Stacked Bar Charts:** Insights into how many males and females work in each specific geographic hub.

## Tech Stack

* **Language:** Python 3
* **Libraries:** - `Pandas`: For data manipulation and cleaning.
* `Matplotlib`: For core plotting and chart customization.
* `Seaborn`: For advanced statistical visualizations and heatmaps.
* `NumPy`: For numerical operations.



## Installation & Usage

1. **Clone the repository:**
```bash
git clone https://github.com/mohammedabrarabbu123-coder/hr-analytics-and-employee-insights-using-python.git

```


2. **Install dependencies:**
Ensure you have Python installed, then run:
```bash
pip install pandas matplotlib seaborn numpy openpyxl

```


3. **Run the Analysis:**
Open the `.ipynb` file in Jupyter Notebook or Google Colab and run the cells sequentially to reproduce the findings.

## Sample Findings

Initial data processing reveals that the organization maintains a diverse workforce across 12 unique departments. The use of heatmaps in the project highlights specific areas where gender representation is balanced versus where recruitment efforts might be focused.
