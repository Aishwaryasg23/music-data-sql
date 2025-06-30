# 🎵 Music Store Data Analysis (SQL)

## 📌 Table of Contents
- [About](#about)
- [Project Description](#project-description)
- [What I Did](#what-i-did)
- [Main Key Points](#main-key-points)
- [Usage](#usage)
- [Features](#features)
- [How to Run](#how-to-run)
- [Contributing](#contributing)
- [License](#license)

---

## 📖 About

This project focuses on analyzing a fictional music store's database using SQL. It is designed to strengthen SQL skills by solving business-related data problems with varying levels of difficulty—ranging from easy to hard.

---

## 📂 Project Description

**Database Used**: `music_store`  
**Language**: SQL (T-SQL for Microsoft SQL Server)

The SQL file contains analytical queries categorized into:
- Easy: Basic `SELECT`, `ORDER BY`, and `GROUP BY`
- Moderate: `JOIN` operations, filtering by genre, artist analysis
- Hard: Common Table Expressions (CTEs), revenue calculations, nested queries

---

## ✅ What I Did

In this project, I worked on various SQL queries that reflect real-world business intelligence needs, including:

- Retrieved all employee data and ranked employees by job level.
- Identified the country with the highest number of invoices.
- Listed the top 3 highest total invoice amounts.
- Analyzed top cities by total invoice value.
- Found top 3 customers based on total amount spent.
- Used joins to get rock music listeners' emails and names.
- Determined the top 10 artists with the most rock songs.
- Calculated average track duration and filtered above-average tracks.
- Created a CTE to find the best-selling artist and customers supporting them.

This work demonstrates my knowledge of SQL fundamentals, aggregations, joins, subqueries, and CTEs for solving complex business questions.


---

## 📌 Main Key Points

- 🔸 **Top employee** identified using `ORDER BY levels DESC`.
- 🔸 **Country with highest invoice count** extracted using `GROUP BY billing_country`.
- 🔸 **Top 3 invoices** listed by total amount.
- 🔸 **Top cities** determined by summed invoice totals.
- 🔸 **Top 3 spending customers** identified via joins between `customer` and `invoice`.
- 🔸 **Rock music listeners' details** fetched using nested `IN` queries and genre filters.
- 🔸 **Most featured rock artists** calculated using joins and group counts.
- 🔸 **Average track length** computed, and above-average tracks listed.
- 🔸 **Best-selling artist and supporting customers** found using CTE and multi-level joins.

These highlight skills in filtering, joining multiple tables, working with aggregates, subqueries, and Common Table Expressions (CTEs).

---

## 🚀 Usage

1. Set up a SQL Server environment.
2. Import or connect to the `music_store` sample database.
3. Open the provided SQL script: `music-store-data-analysis-sql.sql`
4. Run queries section-wise to get outputs and insights.

---

## ✨ Features

- 📊 Insightful queries on sales, customers, and music trends
- 🔍 Difficulty-wise organization (Easy → Hard)
- 📈 Business-focused KPIs like top customers, sales by genre
- 🧠 Practice with real-world SQL patterns (`JOIN`, `CTE`, aggregates)

---

