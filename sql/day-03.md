# 🗓️ Day 3 – SQL Joins

# Business Scenario
Analyze customer orders by joining multiple tables.

# Queries Practiced
-- INNER JOIN

SELECT c.customer_name, o.order_id, o.total_amount
FROM customers c
INNER JOIN orders o ON c.customer_id = o.customer_id;


-- LEFT JOIN

SELECT c.customer_name, o.order_id
FROM customers c
LEFT JOIN orders o ON c.customer_id = o.customer_id;

# What I Learned

1. Difference between INNER and LEFT JOIN
2. Joining tables using foreign keys
3. Avoiding duplicate data confusion
