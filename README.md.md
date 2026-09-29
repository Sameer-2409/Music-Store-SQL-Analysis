# Music Store SQL Analysis

## Project Overview

This project analyzes an online music store database using SQL.

The database contains information about artists, albums, tracks, genres,
customers, employees, invoices, invoice line items, playlists, and media
types.

The objective of the project is to use SQL queries to explore the music
store data and answer business-oriented questions related to customers,
sales, artists, genres, and purchasing behavior.

## Database and Tools

-   PostgreSQL
-   pgAdmin 4
-   SQL

## Database Schema

The project uses a relational database consisting of the following
tables:

-   `Artist`
-   `Album`
-   `Track`
-   `Genre`
-   `MediaType`
-   `Playlist`
-   `PlaylistTrack`
-   `Customer`
-   `Employee`
-   `Invoice`
-   `InvoiceLine`

The database schema shows the relationships between these tables and
their primary/foreign-key relationships.

## Project Analysis

The SQL analysis is divided into three levels.

### 1. Easy

The first section covers:

-   Identifying the senior-most employee based on job title
-   Finding countries with the highest number of invoices
-   Finding the highest invoice values
-   Identifying the city generating the highest invoice revenue
-   Finding the customer who has spent the most money

### 2. Moderate

The second section covers:

-   Identifying customers who listen to Rock music
-   Finding the top 10 artists with the most Rock tracks
-   Finding tracks longer than the average track length

### 3. Advanced

The advanced section covers:

-   Finding customer spending on the best-selling artist
-   Finding the most popular music genre for each country
-   Finding the highest-spending customer in each country
-   Handling cases where the maximum spending or purchases are shared

## SQL Concepts Used

The project demonstrates the use of:

-   SELECT
-   WHERE
-   ORDER BY
-   GROUP BY
-   Aggregate Functions
-   DISTINCT
-   JOIN
-   Subqueries
-   CTEs
-   Window Functions
-   `ROW_NUMBER()`
-   `COUNT()`
-   `SUM()`
-   `AVG()`
-   `MAX()`
-   `LIMIT`

## Project Files

``` text
Music-Store-SQL-Analysis/
│
├── data/
│   ├── album.csv
│   ├── artist.csv
│   ├── customer.csv
│   ├── employee.csv
│   ├── genre.csv
│   ├── invoice.csv
│   ├── invoice_line.csv
│   ├── media_type.csv
│   ├── playlist.csv
│   ├── playlist_track.csv
│   └── track.csv
│
├── Music_Store_database.sql
├── Music_Store_Query.sql
├── schema_diagram.png
└── README.md
```

## Key Business Questions

Some of the questions explored in this project include:

1.  Who is the senior-most employee?
2.  Which countries have the most invoices?
3.  Which city generates the highest invoice revenue?
4.  Who is the highest-spending customer?
5.  Who are the Rock music listeners?
6.  Which artists have the most Rock tracks?
7.  Which tracks are longer than the average track length?
8.  Which artist has generated the highest sales?
9.  Which genre is most popular in each country?
10. Who is the highest-spending customer in each country?

## Source

This project is based on the Music Store SQL analysis project and its
associated dataset/schema. The original project materials and
explanation are retained as part of the project reference.

## Author

Sameer Chaurasia
