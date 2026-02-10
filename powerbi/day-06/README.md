# Day 6 – Power BI Dataset Creation & Data Model

## Dataset Creation
Instead of using a static CSV, the dataset used in this dashboard
was **generated using SQL queries** from a relational database.

The SQL file contains:
- Required joins
- Filters
- Aggregations
- Business logic used to shape the final dataset

This approach ensures:
- Reproducibility
- Clean data modeling
- Better alignment between SQL and Power BI

## Files Included
- `dataset_query.sql` – SQL used to create the analytical dataset
- `data-model.png` – Power BI data model screenshot

## Data Model
- Star schema
- Fact table generated via SQL
- Dimension tables connected using one-to-many relationships

## What I Learned
- Designing analytics-ready datasets using SQL
- Reducing transformation load inside Power BI
- Importance of clean upstream data
