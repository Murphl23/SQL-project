Database Systems Course Project (SQL Server)

This repository contains the schema for a relational database designed as part of a university database systems course.

Schema Overview
- Person: stores people records
- CreditCard: credit cards owned by people
- Stock: items available for purchase
- Buys: purchase transactions referencing Stock and CreditCard
- Place: store or location information
- Works: models a many-to-many relationship between workers and places
- WorkShift: tracks work shifts and references Works via a composite key

Files
- schema.sql: table definitions with primary keys, composite keys, and foreign key constraints

Technologies
- Microsoft SQL Server
- SQL Server Management Studio

Notes
This project focuses on relational modeling, normalization, and enforcing data integrity through constraints.
