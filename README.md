# AgroCoop

A Java-based academic application for managing agricultural producers, products and deliveries, with business rules for pricing and reporting.

The project was developed to practice **Object-Oriented Programming, business logic, exception handling and relational database modeling**.

---

## About the Project

AgroCoop is a terminal-based application designed to support basic operations of an agricultural cooperative.

The system allows users to register producers and agricultural products, record deliveries and generate reports based on the registered data.

The project focuses on applying software development fundamentals through a simple domain-oriented structure.

---

## Features

- Register and remove agricultural producers
- Search producers by name
- Register and remove agricultural products
- Search products by name
- Register product deliveries
- Validate delivery quantities
- Calculate delivery values using different pricing strategies
- Generate revenue reports by producer
- Generate producer rankings by delivered volume
- Generate institutional delivery consolidations

---

## Tech Stack

### Programming

- Java
- Object-Oriented Programming
- Interfaces
- Polymorphism
- Collections
- Exception Handling
- Business Rules

### Database

- MySQL
- SQL
- Relational Database Modeling
- Primary and Foreign Keys

> The current Java application manages runtime data in memory.  
> The project also includes a MySQL SQL schema designed for future persistent storage.

---

## Project Architecture

The project uses a simple separation of responsibilities:

```text
src/
├── exception/
│   └── Custom exceptions
│
├── main/
│   └── Application entry point
│
├── model/
│   ├── Domain entities
│   ├── Pricing strategies
│   └── Business abstractions
│
└── service/
    └── Business operations
