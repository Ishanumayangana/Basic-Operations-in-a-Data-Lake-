# Data Lake Operations: Exploring Sales Data with Python

This project demonstrates fundamental operations in a data lake environment using Python. It showcases how to retrieve, filter, and analyze a sales dataset, alongside optional visualization to gain insights.

---

## Table of Contents
- [Objective](#objective)
- [Dataset Description](#dataset-description)
- [Features](#features)
- [Setup Instructions](#setup-instructions)
- [Tasks Overview](#tasks-overview)
- [Results](#results)
- [Visualization (Optional)](#visualization-optional)
- [Contributing](#contributing)
- [License](#license)

---

## Objective

The objective of this project is to perform basic operations in a data lake using Python. Students will explore data retrieval, filtering, basic analysis, and visualization to extract meaningful insights from a sales dataset.

---

## Dataset Description

The dataset used in this project is a CSV file named `sales_data.csv`. It contains the following columns:
- **TransactionID**: Unique identifier for each transaction.
- **ProductID**: Unique identifier for each product.
- **ProductName**: Name of the product.
- **QuantitySold**: Quantity of the product sold.
- **Price**: Unit price of the product.
- **Revenue**: Revenue generated for the transaction.
- **Timestamp**: Date and time of the transaction.

### Sample Data:
| TransactionID | ProductID | ProductName | QuantitySold | Price  | Revenue | Timestamp           |
|---------------|-----------|-------------|--------------|--------|---------|---------------------|
| 1             | 101       | Product_A   | 15           | 10.50  | 157.50  | 2022-01-01 08:00:00 |
| 2             | 102       | Product_B   | 8            | 15.75  | 126.00  | 2022-01-01 10:30:00 |

---

## Features

1. **Data Retrieval**: Load the sales dataset into a Pandas DataFrame for analysis.
2. **Data Exploration**:
   - View the first 5 rows of the dataset.
   - Determine the total number of rows and columns.
   - Identify unique products.
3. **Data Filtering**: Extract rows where `QuantitySold` is greater than 10.
4. **Basic Analysis**:
   - Calculate total revenue.
   - Identify the product generating the highest revenue.
5. **Visualization (Optional)**: Generate a bar chart of quantities sold for the top 5 products.

---

## Setup Instructions

### Prerequisites
- Python 3.7 or later
- Required Python libraries:
  - `pandas`
  - `matplotlib`

Install dependencies:
```bash
pip install pandas matplotlib
