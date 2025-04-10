 🍕  Dominos_Pizza_project_sql
This project focuses on performing **SQL-based data analysis** on a mock Domino’s Pizza sales dataset. The goal is to extract meaningful insights related to pizza sales, customer behavior, and order patterns using structured queries.

 📊 Project Overview

In this SQL project, you'll explore a simulated Domino's Pizza sales database to answer business-related questions using **SQL queries**. This includes basic data retrieval, aggregation, and multi-table joins for in-depth analysis.



 🗂️ Dataset Schema (Assumed)

- orders
  - `order_id` (Primary Key)
  - `order_date` (Datetime)

- order_details
  - `order_details_id` (Primary Key)
  - `order_id` (Foreign Key)
  - `pizza_id` (Foreign Key)
  - `quantity`

- pizzas
  - `pizza_id` (Primary Key)
  - `pizza_type_id` (Foreign Key)
  - `size`
  - `price`

- pizza_types
  - `pizza_type_id` (Primary Key)
  - `name`
  - `category` (e.g., Classic, Veggie, Chicken, etc.)



✅ Basic SQL Tasks

1. **Total number of orders placed**
2. **Total revenue generated from pizza sales**
3. **Highest-priced pizza**
4. **Most common pizza size ordered**
5. **Top 5 most ordered pizza types with quantities**

 🔄 Intermediate SQL Tasks

6. **Total quantity of each pizza ordered (using joins)**
7. **Total quantity of each pizza category ordered**
8. **Distribution of orders by hour of the day**
9. **Category-wise distribution of pizzas**
10. **Daily average number of pizzas ordered**


