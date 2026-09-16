# PostgreSQL Revenue Analysis – SQL Practice

## Overview

This repository contains my PostgreSQL SQL practice focused on analyzing revenue data and solving business-oriented analytical questions.

The main goal of this practice was to move beyond basic SQL syntax and develop the ability to build multi-step analytical queries using CTEs, aggregations, and window functions.

## Dataset

A small sample `orders` table was used for practice.

| Column | Description |
|---|---|
| order_id | Unique order identifier |
| order_date | Date of the order |
| revenue | Revenue generated from the order |

## Business Questions

The queries in this repository answer questions such as:

1. What is the total revenue for each month?
2. What is the running total of revenue over time?
3. What percentage of total revenue does each month contribute?
4. What is the 2-month moving average of revenue?
5. What is the 3-month moving average of revenue?
6. Which months generated revenue above their 3-month moving average?
7. What was the previous month's revenue?
8. Which months increased by more than ₹2,000 compared with the previous month?
9. What was the month-over-month (MoM) revenue growth percentage?
10. Which months experienced positive revenue growth?

## SQL Concepts Practiced

- SELECT and filtering
- Aggregate functions
- GROUP BY
- EXTRACT()
- Common Table Expressions (CTEs)
- Window functions
- LAG()
- Running totals
- Moving averages
- Percentage of total
- Month-over-month growth
- Filtering calculated results
- Multi-stage analytical queries

## Key Learning

A major focus of this practice was understanding how to break a business problem into multiple SQL stages.

For example:

Raw Orders
↓
Monthly Revenue
↓
Previous Month / Moving Average
↓
Growth Calculation
↓
Business Filter

This helped me practice writing SQL queries that answer business questions rather than only practicing individual SQL commands.

## Tools

- PostgreSQL
- SQL
- GitHub

## Note

This is a learning/practice repository using a small sample dataset. It is intended to document my SQL learning progress and analytical problem-solving practice.
