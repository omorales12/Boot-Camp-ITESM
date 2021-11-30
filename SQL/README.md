# SQL

## Required Tools
- PostgreSQL
- pgAdmin

## Objectives
- Create a data model to represent the objects and relationships in a dataset
- Create schemas, tables, and databases for relational data
- Retrieve data using advanced database queries

## What is SQL
SQL stands for **S**tructured **Q**uery **L**anguage. It is designed to efficiently handle large amounts of data, which is a highly valued capability for organizations.

## What is PostgreSQL (*Postgres*)?
It is an object-relational database system that uses the SQL language. PostgreSQL is used as the primary data store or data warehouse for many web, mobile, geospatial, and analytics applications.

## What is pgAdmin?
It is a management tool used for working with Postgres. It simplifies the creation, maintenance and use of database objects.

## Basic SQL

### Creating Tables and Basic Queries

``` sql
    CREATE TABLE prices_table(
        id INT,
        name VARCHAR(30) NOT NULL,
        price INT DEFAULT 0
    );
```



