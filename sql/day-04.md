# 🗓️ Day 4 – SQL Functions

# Functions Used
1. Date functions
2. String functions
3. Numeric functions

# Queries Practiced
-- Extract year from order date

SELECT EXTRACT(YEAR FROM order_date) AS order_year FROM orders;


-- Uppercase product names

SELECT UPPER(product_name) FROM products;


-- Round prices

SELECT ROUND(price, 2) FROM products;


# What I Learned

1. Data transformation using functions
2. Preparing data for analysis
