# sql-library-management-project-
  # Library Management System — SQL Analytics Project
  
  ## Project Description
  A relational database project built in MySQL modelling the full operational lifecycle of a library.
  Covers 6 interconnected tables — branch, employees, members, books, issued_status, return_status —
  with complete DDL schema, foreign key constraints, realistic sample data, and 17 SQL queries
  progressing from basic SELECT/GROUP BY to multi-table JOINs, HAVING filters, and date arithmetic.
  
  ## Tech Stack
  - Database : MySQL (compatible with PostgreSQL)
  - Tools    : MySQL Workbench / pgAdmin / DBeaver
  - Language : SQL (DDL + DML + DQL)
  
  ## Repository Structure
  schema/    — CREATE TABLE + ALTER TABLE (FK constraints)
  data/      — INSERT scripts for all 6 tables
  queries/   — 17 numbered SQL files (01_select_members.sql ... 17_emp_issued_method2.sql)
  README.md  — this file
  
  ## Key Queries Highlighted
  Q12 — HAVING clause: members who borrowed more than 3 books
  Q13 — Date arithmetic JOIN: days between issue and return
  Q14/15 — Top 3 most issued books (two methods compared)
  Q16/17 — Employee workload report (two GROUP BY approaches)
