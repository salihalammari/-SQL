# 01. Introduction
# SQL

Welcome to the first SQL chapter! 🤩

SQL (short for Structured Query Language) is a programming language designed to manage and retrieve data stored in databases.

It’s a staple in both Data Science and Web Dev.

Fun fact: SQL was developed at IBM in the 70s and named SEQUEL (Structured English Query Language); you can call it “S-Q-L” or “sequel.”

SQL databases are collections of tables, with rows and columns.

In this chapter, we will use a table called shows with data about popular TV shows. 📺

It looks something like this:

| id | name           | genre   | stream     | year | seasons | tomatometer |
|----|----------------|---------|------------|------|---------|-------------|
| 1  | Silicon Valley | Sitcom  |   HBO      | 2014 |  6      |    8.5      |
| 2  | The Last of Us | Horror  |   HBO      | 2023 |  1      |    8.7      |
| 3  | Squid Game     | Thriller|   Netflix  | 2021 |  1      |    8.0      |

There are seven columns: `id`, `name`, `genre`, `stream`, `year`, `seasons`, and `tomatometer`.


SQL statements, or queries, are instructions that the database understands. In other words, queries allow us to retrieve information from a database.

Let’s test out a query real quick. 🙌

