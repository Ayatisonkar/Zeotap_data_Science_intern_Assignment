# Data Science Assignment

## Overview
This assignment aims to to perform exploratory data analysis (EDA), build predictive models, and derive actionable insights.
---

## Project Structure

### 1. **Tasks Overview**
- **Task 1: Exploratory Data Analysis (EDA)**
  - Analyze data distributions, detect anomalies, and identify trends.
  - Visualize key metrics to understand customer and transactional behavior.

- **Task 2: Data Cleaning and Preprocessing**
  - Handle missing values and outliers.
  - Standardize numerical data and encode categorical variables for clustering.

- **Task 3: Customer Segmentation**
  - Use clustering algorithms (e.g., K-Means) to group customers.
  - Evaluate cluster quality and analyze segment characteristics.

### 2. **Data Files**
- **Customers.csv**: Contains customer information including `CustomerID`, `Name`, `Region`, and `SignupDate`.
- **Transactions.csv**: Includes transactional details such as `TransactionID`, `CustomerID`, `ProductID`, `Quantity`, and `TotalValue`.
- **Products.csv**: (Optional) Provides product details like `ProductID`, `Category`, and `Price`.

### 3. **Deliverables**
- **Processed Datasets**: Cleaned and aggregated data ready for analysis.
- **Visualizations**: Scatter plots and PCA projections illustrating clusters.
- **PDF Report**: Summary of the clustering process, findings, and recommendations.

---

## Setup Instructions

1. **Environment Setup**
   - Ensure Python 3.8 or above is installed.
   - Install dependencies using the following command:
     ```bash
     pip install -r requirements.txt
     ```

2. **Execution Steps**
   - Place the dataset files (`Customers.csv`, `Transactions.csv`,`Products.csv`) in the project directory.
   - Run the Jupyter Notebook `Ayati_Sonkar_EDA.ipynb` or corresponding Python scripts to perform EDA on the data.
   - Run the Jupyter Notebook `Ayati_Sonkar_Lookalike.ipynb` or corresponding Python scripts to perform lookalike on the data.
   - Run the Jupyter Notebook `Ayati_Sonkar_Clustering.ipynb` or corresponding Python scripts to process the data.

3. **Output Generation**
   - Execute clustering algorithms to generate customer segments.
   - Visualize and export the results as plots and reports.

---





