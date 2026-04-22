# Digital Library SQL

## Overview

This SQL project models a digital library system with books, students, and issued books. It includes schema creation, sample data loading, and reporting queries.



## SQL Concepts Used

- Primary keys
- Foreign keys
- `JOIN`
- `WHERE`
- `COUNT`
- `ORDER BY`
- `DATEDIFF`
- `DATE_SUB`
- Subqueries

## Join Logic Used

- `IssuedBooks` joins with `Students` using `student_id`
- `IssuedBooks` joins with `Books` using `book_id`
- These joins help show overdue book details with both student and book information in a single result

## Screenshot

![Digital Library SQL Queries](./digital-library-sql.png)


## Author

Suru Harshit
