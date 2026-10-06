# Chapter 5: Databases and Data Management

## 1. What is a database?

A database is a place where an application stores data.

Examples:

- user accounts
- product information
- messages
- blog posts
- payment records

## 2. Types of databases

### SQL databases

- MySQL
- PostgreSQL
- SQLite

### NoSQL databases

- MongoDB
- Firebase Firestore
- Redis

## 3. SQL basics

```sql
CREATE TABLE users (
  id INT PRIMARY KEY,
  name VARCHAR(100),
  email VARCHAR(100)
);

INSERT INTO users (id, name, email)
VALUES (1, 'Alice', 'alice@example.com');
```

## 4. CRUD operations

CRUD means:

- Create
- Read
- Update
- Delete

## 5. Database design

Learn:

- tables
- primary keys
- foreign keys
- relationships
- indexing
- normalization

## 6. Why databases matter

Without a database, websites cannot store or retrieve data in a structured way.

## 7. Final note

Databases are the foundation of websites that need user accounts, products, comments, and dynamic content.
