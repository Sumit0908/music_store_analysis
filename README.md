# 🎵 Music Data Analysis Project

A SQL-based data analysis project exploring sales, customer behavior, and music trends using a digital music store dataset.

---

## 📘 Project Description

This project simulates the role of a data analyst working for a digital music platform. Using SQL, we analyze transactional and customer data to uncover insights such as:

- Top-performing music genres and artists  
- Country-wise revenue generation  
- Customer purchase behavior  
- Monthly sales trends

The dataset used is inspired by the [Chinook Database](https://github.com/lerocha/chinook-database), a sample database commonly used in SQL learning environments.

---

## 🧩 Dataset Overview

| Table Name     | Description |
|----------------|-------------|
| `Customer`     | Customer information (name, country, etc.) |
| `Invoice`      | Invoice headers (date, customer, total amount) |
| `Invoice_Line` | Line items in invoices (track, quantity, price) |
| `Track`        | Details of individual music tracks |
| `Album`        | Albums associated with tracks |
| `Artist`       | Artist information |
| `Genre`        | Genre classification for tracks |

---

## 🎯 Key Business Questions

1. Which genres are most popular by country?
2. Who are the top 5 customers by total spend?
3. Which artists generate the most revenue?
4. What are the monthly revenue trends?
5. What genre does each customer prefer most?
6. What are the most purchased tracks?

---

## 💻 SQL Queries

All SQL queries are organized in the [`queries/`](./queries/) folder and include:

- `top_genres_by_country.sql`
- `top_customers.sql`
- `artist_sales.sql`
- `monthly_sales_trend.sql`
- `customer_genre_preferences.sql`
- `most_purchased_tracks.sql`

Each script is self-contained and can be run independently in an SQL client.

---

## 📊 Sample Insights

| Country   | Top Genre | Revenue |
|-----------|-----------|---------|
| USA       | Rock      | $12,300 |
| Canada    | Pop       | $8,540  |
| Germany   | Rock      | $9,100  |

---

## 🧠 Skills Demonstrated

- SQL joins (INNER, LEFT)
- CTEs and subqueries
- Aggregation and filtering
- Grouping and ordering
- Data storytelling

---

## 🚀 How to Use

1. Clone the repository  
2. Load the data into a PostgreSQL or SQLite environment (e.g., Chinook DB)
3. Open and execute queries in your SQL editor  
4. Modify or expand queries as needed for your own analysis

---

## 📁 Project Structure


