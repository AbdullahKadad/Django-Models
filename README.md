# Django-Models

## SQL vs. NoSQL Databases: What's the Difference?

**SQL databases** are relational databases that store data in tables with predefined schemas.

They use structured query language (SQL) for querying and managing data.

Examples include MySQL, PostgreSQL, and SQLite.

**NoSQL databases** are non-relational databases that do not require a fixed schema.

They can store data in various formats like key-value pairs, document stores, column stores, or graph databases.

Examples include MongoDB, Redis, Cassandra, and Neo4j.

---

## What is an ORM – The Meaning of Object Relational Mapping

**Object-Relational Mapping (ORM)** is a programming technique that converts data between incompatible type systems, i.e., object-oriented programming languages and relational databases.

Key points:

- ORM maps objects from an application's domain model to tables in a relational database.
- It allows developers to work with objects rather than database tables and SQL.
- ORM frameworks handle complex SQL queries, database schema migrations, and optimize performance.

---

## Django Models

**Django Models** are Python classes used to define the structure of database tables in Django applications.

They represent database tables as classes with attributes that define the table fields.

Key concepts:

- Models define data structures and behaviors of application data.
- Fields in Django models map to database columns.
- Models facilitate database operations like CRUD (Create, Read, Update, Delete).
