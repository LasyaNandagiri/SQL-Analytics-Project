# SQL Analytics Project  
## Disease Management System — Relational Data Analysis & Reporting

**Project Type:** SQL Analytics & Database Analysis  
**Domain:** Healthcare / Disease Analytics  
**Primary Focus:** Relational Modeling, Analytical SQL, Reporting  

---

## Project Overview
This project delivers a **comprehensive SQL-based analytical solution** for a **Disease Management System**, designed to extract actionable insights from healthcare-related relational data. The analysis emphasizes **schema understanding, analytical query design, and structured reporting**, demonstrating how SQL can be used as a powerful standalone analytics tool.

The project integrates **database design concepts, analytical SQL techniques, and report-driven insights** to support clinical and operational decision-making.

---

## Business / Analytical Context
Healthcare datasets are typically stored across multiple relational tables representing patients, diseases, treatments, and outcomes. Meaningful insights require:
- Correct interpretation of database schemas
- Efficient joins across related entities
- Aggregation and analytical logic aligned with healthcare questions

This project addresses these challenges by translating **real-world disease management questions** into **structured SQL analytics**.

---

## Objectives
- Apply relational database principles to healthcare data
- Interpret and leverage a detailed data dictionary
- Write accurate and efficient SQL queries for analysis
- Generate structured analytical reports from SQL outputs
- Demonstrate SQL proficiency independent of BI or visualization tools

---

## Dataset & Schema
- **Domain:** Healthcare / Disease Management  
- **Data Model:** Relational schema with multiple interrelated tables  
- **Schema Documentation:** `DataDictionary.xlsx`, detailing:
  - Table definitions
  - Column descriptions and data types
  - Primary and foreign key relationships
  - Business meaning of attributes

The data dictionary serves as the **foundation for query logic, joins, and aggregations**.

---

## Methodology

### 1) Schema & Data Understanding
- Reviewed table relationships using the data dictionary
- Identified primary keys and foreign keys
- Mapped analytical questions to appropriate tables
- Ensured join paths preserved data integrity

---

### 2) SQL Query Design & Development
SQL queries were written to perform:

- **Data extraction and filtering**
- **Multi-table joins** (inner and outer joins)
- **Aggregations and grouping** for summary metrics
- **Subqueries and nested queries** for intermediate logic
- **Derived metrics** using calculated fields
- **Conditional logic** using `CASE WHEN`

All queries are consolidated and documented in:
- `SQL Queries.sql`

---

### 3) Analytical Techniques Applied
The project demonstrates the following SQL analytics techniques:

- Relational data analysis  
- Entity-relationship navigation  
- Aggregation-based reporting  
- Analytical query decomposition  
- Healthcare metric computation  
- Report-oriented SQL design  

Where applicable, queries reflect:
- Patient-level analysis
- Disease-level summaries
- Treatment-based comparisons
- Outcome-oriented metrics

---

### 4) Reporting & Interpretation
- Query results were validated against schema expectations
- Outputs were summarized and interpreted in an analytical report
- Findings were translated into healthcare-relevant insights

The final interpretations and conclusions are documented in:
- `DISEASE MANAGEMENT_Report.pdf`

---

## Tools & Technologies

### Core Technologies
- **SQL (Structured Query Language)**

### Database & Querying Concepts
- Relational database design
- Primary & foreign keys
- Normalized schemas
- Referential integrity

### Analytical SQL Techniques
- JOIN operations
- GROUP BY and aggregate functions
- Subqueries
- Conditional logic (`CASE WHEN`)
- Metric calculation and summarization

### Supporting Tools
- SQL IDE / Client  (PostgreSQL, SQL Server)
- Microsoft Excel (Data Dictionary)


---

## Repository Structure
```text
SQL-Analytics-Project/
├── SQL Queries.sql
├── DataDictionary.xlsx
├── DISEASE MANAGEMENT_Report.pdf
└── README.md
