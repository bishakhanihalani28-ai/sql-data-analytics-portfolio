# Music Store SQL Analysis

## Project Overview

This project shows SQL analysis of a digital music store database.

The goal of this project is to practise writing SQL queries to answer realistic business questions related to customers, invoices, revenue, artists, genres, tracks and sales performance.

This project helped me understand how SQL can be used to explore a relational database, join multiple tables, calculate business metrics, and turn raw data into meaningful insights.

## Business Context

A digital music store wants to better understand its sales performance and customer behaviour.

The business wants to answer questions such as:

- Which customers generate the most revenue?
- Which countries have the highest sales?
- Which music genres are most popular?
- Which artists or tracks contribute most to sales?
- How does invoice and customer data help understand business performance?

Using SQL, this project explores the database and answers these questions through structured queries.

## Tools Used

- Google Colab
- SQLite
- SQL
- Chinook Music Store Database

## Dataset

The project uses the Chinook sample database, which represents a digital music store.

The database includes tables related to:

- Customers
- Invoices
- Invoice items
- Tracks
- Albums
- Artists
- Genres
- Employees
- Playlists

This makes it useful for practising SQL joins, aggregations, filtering and business analysis.


## Business Questions Answered

The analysis focuses on questions such as:

1. What are the total sales of the music store?
2. Which customers spent the most money?
3. Which countries generated the highest revenue?
4. Which genres are most popular by sales?
5. Which artists generated the most revenue?
6. Which tracks were purchased the most?
7. What is the average invoice value?
8. Which employees support the highest-value customers?
9. Which countries have the most customers?
10. What insights can the store use to improve sales and customer targeting?

## Example Analysis Areas

### Revenue Analysis

SQL was used to calculate total revenue, average invoice value, and revenue by country.

### Customer Analysis

Customer-level queries helped identify the highest-value customers and understand where customers are located.

### Product and Music Analysis

Track, genre and artist data were joined with invoice data to understand which music categories and artists contributed most to sales.

### Employee and Support Analysis

Employee and customer tables were used to explore which support representatives managed customers contributing higher revenue.


## Key Insights

Some of the insights explored in this project include:

- Revenue is concentrated among certain customers and countries.
- Genre and artist performance can help the business understand customer preferences.
- Customer and invoice data can be used to identify high-value customers.
- SQL joins are essential for connecting business questions across multiple tables.

## Files in This Folder

```text
01_music_store_analysis/
│
├── README.md
├── music_store_sql_analysis.ipynb
└── screenshots/
    └── query_results.png
