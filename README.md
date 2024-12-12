# SQL Query Optimization Demo
This repository demonstrates SQL query optimization techniques.

## Problem Query
- Inefficient due to full table scan caused by the use of `LOWER()` function.

## Optimized Query
- Use indexing to speed up the query and avoid function calls on indexed columns.

## Results
- The performance improvement is demonstrated using `EXPLAIN ANALYZE`.
