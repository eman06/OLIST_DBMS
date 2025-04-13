# OLIST_DBMS
A SQL Server database project analyzing Brazil's Olist e-commerce dataset. Includes schema design, foreign key relationships, data import, and advanced queries for business insights.
# Olist E-commerce SQL Server Analysis

This project is a SQL Server-based analysis of the [Olist Brazilian E-commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). It covers database creation, schema design, relationships, data import, and advanced SQL queries for real-world business insights.

---

## 📦 Dataset Overview

The Olist dataset contains Brazilian e-commerce data including:

- Customers
- Orders
- Payments
- Products
- Sellers
- Reviews
- Geolocation

---

## 🧱 Schema Design

Each CSV file corresponds to a table. Relationships were defined using appropriate foreign keys. The schema includes:

- `customers`
- `orders`
- `order_items`
- `products`
- `sellers`
- `order_reviews`
- `order_payments`
- `product_category_translation`
- `geolocation`

---

## 🛠 Setup Instructions

1. **Create a new SQL Server database named `olistfinal`.**
2. Run the scripts in the `schema/` folder:
   - `create_tables.sql` to create all tables
   - `foreign_keys.sql` to add foreign key constraints
3. Import data from the CSV files into the respective tables (use SQL Server Management Studio or any ETL tool).
4. Run queries from the `queries/` folder to perform analysis.

---

## 🔍 Key Analysis Queries

- Top 10 best-selling product categories
- Average delivery time per state
- Payment type distribution
- Sellers with highest review scores
- Revenue by state and category

See `queries/` folder for SQL files.

---

## 📂 Project Structure
olistfinal-sql-server-analysis/ │ ├── README.md ├── schema/ │ ├── create_tables.sql │ └── foreign_keys.sql │ ├── data/ │ ├── customers.csv │ ├── orders.csv │ ├── order_items.csv │ └── ... (etc.) │ ├── queries/ │ ├── top_sellers.sql │ ├── avg_delivery_time.sql │ └── category_analysis.sql │ └── notebooks/ (Optional for Jupyter/SSMS notebooks)


---

## 📊 Insights & Use Cases

- How fast are orders delivered per region?
- Which sellers are most reliable?
- Which product categories generate the most revenue?
- Customer behavior by state and city.

---

## 📎 Source

- [Kaggle Dataset – Olist E-commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## 📧 Contact

Made by a 4th-semester Computer Science student exploring data analysis and SQL Server database design. Feel free to contribute or ask questions!
feel free to email me on emannihsan@gmail.com for the datset.
