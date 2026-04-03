# Introduction to SQL with the Firebird DBMS

➡️ Related course: **[Introduction to SQL with the Firebird DBMS](https://stahe.github.io/en-sql-firebird-janv-2006/)**

## Overview

This document is an introduction to the **SQL (Structured Query Language)** language as applied to the **Firebird DBMS**.
It revises and adapts an older educational document written in **1991 for Oracle**, which was itself largely inspired by Oracle’s official documentation and the book:

* *SQL – Introduction, Programming, and Mastery*
  by **Christian Marée** and **Guy Ledant**, published by Eyrolles. 

SQL is a **standard language used to create, maintain, and query relational databases**.
It is largely independent of the database management system (DBMS) used, even though some DBMSs introduce proprietary extensions. 

## Why Firebird?

The examples in this document use the **Firebird DBMS**.
This choice is motivated by a feature that is particularly practical in an educational context: a Firebird database can be **contained in a single file**.

This allows, for example:

* easily copying a database to a **USB drive**
* using it on **different computers** (home, university, lab)
* working without complex infrastructure

## SQL Compatibility

Although the examples are written for Firebird, most can be reproduced with other relational DBMSs, for example:

* MySQL
* PostgreSQL
* Firebird
* SQL Server Express
* Microsoft Access
* Oracle

These systems all use SQL, sometimes with **product-specific variants or extensions**.

## Target Audience

This document is intended for:

* **beginners who want to learn SQL**
* people who want to **review the basics of the language**

It focuses on learning **fundamental SQL**.

## Scope Exclusions

Certain topics are intentionally not covered:

* stored procedures
* advanced SQL programming
* SQL APIs
* DBMS administration

The goal is to provide a **clear and step-by-step introduction to the SQL language**. 

Serge Tahé, january 2006