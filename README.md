

# **Sales Data Cleaning and Analysis Project**

This project demonstrates a comprehensive workflow for cleaning and analyzing sales data. It employs data profiling, missing value treatment, outlier removal, and exploratory data analysis (EDA) to generate actionable insights, including RFM analysis.

---

## **Table of Contents**
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Dataset Overview](#dataset-overview)
6. [Project Workflow](#project-workflow)
7. [How to Run](#how-to-run)
8. [Results](#results)
9. [License](#license)

---

## **Project Overview**
The goal of this project is to clean and analyze a transactional dataset. By removing inconsistencies, visualizing trends, and performing RFM (Recency, Frequency, Monetary) analysis, the project supports strategic decision-making for business optimization.

---

## **Features**
- Data cleaning:
  - Handling missing values
  - Removing duplicates
  - Addressing outliers
- Exploratory Data Analysis:
  - Identifying top-selling products and countries
  - Monthly sales trends
- RFM Analysis for customer segmentation
- Visualization using Matplotlib and Seaborn

---

## **Technologies Used**
- **Python**: Core programming language
- **Pandas**: Data manipulation and cleaning
- **Seaborn & Matplotlib**: Data visualization
- **NumPy**: Numerical operations
- **Scikit-learn**: Scaling and preprocessing
- **YData Profiling**: Data profiling
- **Google Colab**: Development environment

---

## **Installation**
To set up the project locally, follow these steps:
1. Clone this repository:
    ```bash
    git clone https://github.com/your_username/your_repository.git
    ```
2. Install the required libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn ydata-profiling sidetable
    ```

---

## **Dataset Overview**
- **Source**: The dataset (`data.csv`) contains transactional data, including:
  - `InvoiceNo`: Invoice number
  - `StockCode`: Product code
  - `Description`: Product description
  - `Quantity`: Quantity sold
  - `InvoiceDate`: Date of purchase
  - `UnitPrice`: Price per unit
  - `CustomerID`: Unique customer identifier
  - `Country`: Customer's country

---

## **Project Workflow**
### 1. Data Profiling and Inspection
- Generated an initial report of data statistics.
- Identified missing values, incorrect data types, and duplicates.

### 2. Data Cleaning
- Removed rows with missing customer information.
- Filtered out transactions with zero or negative quantity and price.
- Addressed outliers in `Quantity` (>10,000) and `UnitPrice` (>5,000).
- Ensured no duplicate rows.

### 3. Exploratory Data Analysis (EDA)
- Visualized:
  - Top-selling products and countries.
  - Monthly sales trends.
  - Combined sales trends by top 10 countries and months.

### 4. RFM Analysis
- Calculated:
  - **Recency**: Days since the last purchase for each customer.
  - **Frequency**: Number of purchases per customer.
  - **Monetary**: Average purchase value for each customer.

---

## **How to Run**
1. Upload the dataset (`data.csv`) to the workspace.
2. Execute the script step-by-step in Google Colab or any Python environment.
3. Adjust any paths or settings in the script as needed.

---

## **Results**
### Key Insights:
- Identified the top 10 products and countries contributing to sales.
- Monthly and country-wise trends provide actionable business insights.
- Segmented customers based on RFM analysis for targeted marketing.





