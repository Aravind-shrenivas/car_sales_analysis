# Car Sales Data Analysis - SQL Project

## Project Overview  
This project analyzes a relational database (`stores.db`) containing **sales transactions, customer data, products, employees, and payments** for a car sales business. The objective is to extract meaningful insights using **SQL queries** and **optimize business strategies** based on data-driven decision-making.  

Through this analysis, we aim to answer **three critical business questions**:  
1. **Which products should we order more of or less of?**  
2. **How should we match marketing and communication strategies to customer behavior?**  
3.  **How much can we spend on acquiring new customers?**  

Using **SQLite in Python**, we efficiently execute queries and document the findings in a structured manner.  

---

## Database Schema & Relationships  

The database consists of **eight key tables**:  

| **Table Name**     | **Description** |
|-------------------|-------------------------------------------|
| `customers`       | Stores customer details and contact information. |
| `employees`       | Contains employee records, roles, and office assignments. |
| `offices`         | Stores sales office locations and contact details. |
| `orders`          | Records customer sales orders. |
| `orderdetails`    | Line items for each sales order. |
| `payments`        | Stores customer payment transactions. |
| `products`        | Contains product details, pricing, and stock levels. |
| `productlines`    | Categorizes products into different lines. |

---

## Key Business Insights  

- Vintage cars and motorcycles are the priority for restocking. They sell frequently, and they are the highest-performance products.
- The VIP and non-VIP lists denote our most loyal customers and least engaged customers. Now that we have identified them, we can strategize on enhancing customer loyalty and attracting new customers effectively.
- LTV indicates the total profit an average customer generates over their lifetime with our store, helping us forecast future earnings. This prediction enables us to determine how much we can invest in acquiring new customers.

---

## Technologies Used  

- **Database:** SQLite (`stores.db`)  
- **Query Language:** SQL  
- **Data Analysis:** Python (Pandas, SQLite3)

---

## How to Run the Project  

1. Clone the repository:  

git clone https://github.com/Aravind-shrenivas/car_sales_analysis.git
cd car_sales_analysis

2. Install dependencies:

pip install pandas sqlite3

3. Open the Jupyter Notebook and run the SQL queries step by step.

---

## Author 

Aravind shrenivas Murali
Email: aravindshrenivas@gmail.com, aravindshrenivas@arizona.edu

---

## License

MIT License  

Copyright (c) 2025

---
