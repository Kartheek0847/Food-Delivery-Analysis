# 🍔 Food Delivery Data Analysis

## 📌 Project Overview
This project performs an end-to-end analysis of a food delivery dataset to understand customer behavior, restaurant performance, and revenue trends. The analysis involves handling **heterogeneous data formats** (CSV, JSON, and SQL) and merging them into a single comprehensive dataset for insight generation.

## 📂 Datasets Used
The analysis combines three distinct data sources:
1.  **`orders.csv`**: Transactional data containing order IDs, dates, and amounts.
2.  **`users.json`**: Customer demographic details (Name, City, Membership Status).
3.  **`restaurants.sql`**: Restaurant metadata (Cuisine, Ratings) parsed directly from SQL `INSERT` statements.

## 🚀 Key Features & Analysis
* **Data Integration:** Successfully merged structured (CSV), semi-structured (JSON), and unstructured (SQL dump) data using **Pandas**.
* **Customer Segmentation:** Analyzed spending habits of **Gold vs. Regular** members across different cities.
* **Performance Metrics:** Identified top-performing cuisines, high-revenue cities, and rating-based revenue correlations.
* **Temporal Analysis:** Determined peak revenue quarters and order trends over time.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Regular Expressions (re), JSON
* **Tool:** Jupyter Notebook

## 📊 Key Insights Derived
* **Top Revenue City:** Chennai leads in revenue contribution from Gold members.
* **Most Valuable Cuisine:** Mexican cuisine has the highest average order value.
* **High-Value Customers:** Identified ~2,500 distinct users with a total spend of over ₹1000.
* **Rating Correlation:** Restaurants with ratings between **4.6 – 5.0** generated the highest total revenue, proving quality drives sales.

## ⚙️ How to Run
1.  Clone this repository:
    ```bash
    git clone [https://github.com/YourUsername/Food-Delivery-Analysis.git](https://github.com/YourUsername/Food-Delivery-Analysis.git)
    ```
2.  Install dependencies:
    ```bash
    pip install pandas notebook
    ```
3.  Open the Jupyter Notebook:
    ```bash
    jupyter notebook Food_Delivery_Analysis.ipynb
    ```

---
*This project was completed as part of a Data Analysis Internship assessment.*
