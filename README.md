# Complex SQL Queries (ClassicModels)

## Project Overview
This repository showcases data manipulation proficiency using the industry-standard **ClassicModels** schema—a relational database representing an international scale-model car and vehicle distributor. 

**Analytical Data Retrieval:** <br>
A comprehensive suite of optimized SQL queries engineered to extract business insights, handle complex multi-table relationships, and execute precise aggregations.

---

## Database Schema Architecture
The database maps out a full corporate logistics network including employees, offices, customer accounts, orders, products, and incoming payments. 

The schema enforces strict relational boundaries to guarantee transactional consistency:
* **One-to-Many Pointers:** Linking sales representatives (`employees`) directly to corporate client accounts (`customers`).
* **Composite Primary Keys:** Utilized in tables like `orderdetails` (`orderNumber`, `productCode`) to seamlessly map many-to-many intersections between orders and warehouse inventory products.
* **Self-Referencing Keys:** Implemented in the employee table (`reportsTo` tracking supervisor `employeeNumber`) to model hierarchical organizational management.

---

## Core SQL Concepts Demonstrated

The scripts in this project demonstrate a strong grasp of data engine manipulation across several advanced relational mechanics:

### 1. Multi-Table Joins & Schema Navigation
Navigating the database to stitch records across deep tables—such as linking raw client profiles (`customers`) through order registries (`orders`) to evaluate exact fulfillment line items (`orderdetails`).

### 2. Analytical Aggregations & Grouping
Synthesizing bulk records into high-level business intelligence dashboards using aggregate functions (`COUNT`, `SUM`, `AVG`) combined with `GROUP BY` and logical `HAVING` filters to isolate specific metrics.

### 3. Advanced Query Logic & Analytical Problem Solving
Formulating customized, multi-layered queries to evaluate data edge cases, extract contextual statistics, and showcase the full relational power of structured query statements.

---

## Academic Context
This portfolio project represents individual coursework completed during the CSC2001F curriculum at the University of Cape Town. It validates a practical foundation in structured query mechanics, schema traversal and relational analytical thinking.
