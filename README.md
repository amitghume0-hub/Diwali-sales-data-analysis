# 🛍️ Diwali Sales Data Analysis

## Project Overview

This project is a detailed **Exploratory Data Analysis (EDA)** of sales data generated during the Diwali festival season in India. The primary objective was to uncover meaningful patterns in customer purchasing behavior, identify high-value demographics, and pinpoint top-selling products and states to provide actionable insights for future marketing and inventory strategies.

## Key Findings & Business Insights

The analysis yielded a highly specific customer profile, which is the main deliverable of this project:

> **The most promising customer segment comprises Married women, aged 26-35 years, primarily residing in Uttar Pradesh, Maharashtra, and Karnataka. These buyers are predominantly employed in the IT, Healthcare, and Aviation sectors, and their preferred purchases fall under the Food, Clothing, and Electronics categories.**

This insight can be used to target marketing campaigns, optimize stock levels, and customize product offerings.

## Technical Details

### Technologies Used

* **Language:** Python
* **Libraries:**
    * `Pandas` for data loading, cleaning, and manipulation
    * `NumPy` for numerical operations
    * `Matplotlib` & `Seaborn` for statistical data visualization

### Data Preparation Steps

1.  **Data Loading:** Read the `Diwali_Sales_Data.csv` dataset.
2.  **Cleaning:** Dropped irrelevant columns (`Status`, `unnamed1`).
3.  **Missing Value Handling:** Removed all rows with missing values (specifically in the `Amount` column).
4.  **Data Type Correction:** Converted the `Amount` column to integer type for accurate calculations and visualization.

### Exploratory Data Analysis Highlights

* Analyzed total orders and sales amount across **Gender** and **Age Groups**.
* Identified the **Top 10 States** by number of orders and sales amount.
* Visualized sales and orders based on **Occupation** and **Marital Status**.
* Determined the **Top Product Categories** by sales revenue (`Food`, `Clothing`, `Electronics` were top sellers).
* Identified the **Top 10 Products** (by `Product_ID`) based on the number of orders.

## How to Run the Project

1.  **Clone the repository:**
    ```bash
    git clone <Your-Repository-URL>
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  **Run the analysis:**
    The analysis is contained within the **`Diwali_Sales_Analysis.ipynb`** Jupyter Notebook. Open and run the cells sequentially to reproduce the analysis and visualizations.
    ```bash
    jupyter notebook Diwali_Sales_Analysis.ipynb
    ```

## Author

- **Amit Ghume**
- **Email:** amitghume0@gmail.com
- **Connect on LinkedIn:** [linkedin.com/in/amit-ghume-7b8b13375](https://www.linkedin.com/in/amit-ghume-7b8b13375)
