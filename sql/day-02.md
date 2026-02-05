# 🗓️ Day 2 – SQL Filtering & Aggregation

# Concepts Covered:
1. WHERE clause
2. GROUP BY
3. HAVING

# Queries Practiced
-- Orders above ₹1000

SELECT * FROM orders WHERE total_amount > 1000;


-- Total sales per customer

SELECT customer_id, SUM(total_amount) AS total_spent
FROM orders
GROUP BY customer_id;


-- Customers with spending > ₹5000

SELECT customer_id, SUM(total_amount) AS total_spent
FROM orders
GROUP BY customer_id
HAVING SUM(total_amount) > 5000;


# What I Learned

1. Filtering rows using conditions
2. Aggregating data
3. Difference between WHERE and HAVING
