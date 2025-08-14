## Task 6: Sales Trend Analysis Using Aggregations

### Objective
Analyze **monthly revenue** and **order volume** from the `online_sales` dataset using SQL aggregation functions.

### Dataset
**Table:** `online_sales`  

**Columns:**
- `order_id` (INTEGER) – Unique order identifier  
- `order_date` (DATE) – Date of the order  
- `amount` (REAL) – Order revenue amount  
- `product_id` (INTEGER) – Product identifier  

### SQL Logic
Following the given hints:

1. **Extract month/year**  
   ```sql
   EXTRACT(MONTH FROM order_date)
   EXTRACT(YEAR FROM order_date)

### Tools Used

SQLite (in-memory database for demonstration)

Pandas (for displaying results in Jupyter Notebook)
