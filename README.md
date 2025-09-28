Online Bookstore – Window Functions Project
Problem Statement

We want to study sales in an online bookstore. Customers buy books, and we need to use SQL window functions to see sales trends, customer groups, and top books.

Database Schema

customers: customer_id (PK), name, region

books: book_id (PK), title, category

transactions: transaction_id (PK), customer_id (FK), book_id (FK), sale_date, amount

These tables are connected:

A customer can make many transactions.

A book can appear in many transactions.

How to Run Scripts

Run create_tables.sql (sets up tables).

Run insert_data.sql (adds sample data).

Run queries.sql (runs window function queries).

Queries and Purpose

Top 5 books per region/quarter → shows bestsellers in each place and time.

Running monthly sales totals → shows how sales increase month by month.

Month-over-month growth → compares each month with the previous one.

Customer spend quartiles → splits customers into 4 groups by spending.

3-month moving average → smooths sales trends over time.

Key Findings

Some books sell much better in certain regions.

Sales are growing, but some months drop.

A small group of customers spend the most.

Moving averages help show the real sales trend without big ups and downs.

Integrity Statement

All sources were properly cited. Implementations and analysis represent original work. No AI-generated content was copied without attribution or adaptation.

References

Oracle SQL Documentation

PL/SQL Tutorial (TutorialsPoint)

W3Schools SQL Window Functions

GeeksforGeeks SQL Window Functions Guide

Academic lecture notes

Database textbook (course material)

SQLShack – SQL Ranking Functions

TowardsDataScience – Intro to Window Functions

Oracle LiveSQL Examples

Class slides from AUCA
