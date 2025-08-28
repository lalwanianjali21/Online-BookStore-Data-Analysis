# Online-BookStore-Data-Analysis

A polished SQL-driven data analysis project designed to extract meaningful insights from an online book store’s datasets. This project demonstrates skills in SQL querying, data wrangling, exploratory analysis.

##  Project Overview

You are given multiple datasets related to an online book store:
- `Books.csv`: Details about each book (e.g., title, author, genre, price).
- `Customers.csv`: Customer demographics and identifiers.
- `Orders.csv`: Purchase records linking books to customers.
- SQL questions file and a solved version to demonstrate query logic.

In this project, I:
1. Designed an efficient database schema using CSV sources.
2. Import and normalize the data into a relational SQL database.
3. Crafted SQL queries to answer key business questions:
   - Top-selling books and authors.
   - Monthly sales trends and revenue performance.
   - Customer purchase behavior and segmentation.
   - Genre popularity and pricing analysis.
4. Validate queries with edge-case checks.
5. Present results in a comprehensible format (e.g., tables, charts, or dashboards via external tools).

##  Data Files

| Filename                          | Description                                                  |
|----------------------------------|--------------------------------------------------------------|
| `Books.csv`                      | Book details: `book_id`, `title`, `author`, `genre`, `price` |
| `Customers.csv`                  | Customer data: `customer_id`, `name`, `email`, `region`      |
| `Orders.csv`                     | Orders info: `order_id`, `customer_id`, `book_id`, `date`    |
| `SQL - Only Questions.sql`       | Bare questions in `.sql` format                              |
| `SQL Queries – SOLVED.sql`       | Fully solved SQL Script                                      |

##  Usage Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/lalwanianjali21/Online-BookStore-Data-Analysis.git

2. **Load data into your SQL environment**

- Create a database (e.g., PostgreSQL, MySQL, SQLite).
- Create tables matching the CSV schema.
- Import data via COPY, LOAD DATA, or GUI tools.

3. **Run the solved SQL script**

```bash
mysql -u user -p online_bookstore < "SQL Queries – SOLVED.sql"

```
# About Me

I’m Anjali Lalwani, A Final Year B.Tech CSE-AI student passionate about data, SQL, and solving meaningful problems through code and logic.

# Contact 

Feel free to reach out to me at:
- **Email**: anjalilalwani442@gmail.com
- **LinkedIn**: [Anjali Lalwani](https://www.linkedin.com/in/anjali-lalwani-702a7924a)

   
