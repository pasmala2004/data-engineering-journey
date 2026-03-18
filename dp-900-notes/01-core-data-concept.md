# Module 01: Core Data Concepts

## Types of Data
- **Structured**: Organized in tables (rows & columns)
- **Semi-structured**: JSON, XML (flexible schema)
- **Unstructured**: Images, videos, text files

---

## Types of Databases

### 1. Relational Databases
- Data stored in tables
- Uses SQL
- Example: Azure SQL Database

### 2. Non-Relational Databases
- More flexible schema

Types:
- **Key-Value Database** → Unique key + value  
- **Document Database** → JSON documents  
- **Column Family Database** → Data stored in columns  
- **Graph Database** → Nodes + relationships  

---

## Core Concepts

### OLTP (Online Transaction Processing)
- Used for day-to-day operations (CRUD)
- Operations:
  - Create
  - Retrieve
  - Update
  - Delete
- Ensures data integrity using **ACID**:
  - Atomicity
  - Consistency
  - Isolation
  - Durability
- Used in business applications (LOB)

---

### OLAP (Online Analytical Processing)
- Used for data analysis and reporting

#### Typical Workflow:
1. Data Extraction (ETL)
2. Data Storage (Data Lake / Lakehouse)
3. Data Transformation & Aggregation
4. Reporting & Dashboards

---

## Data Storage Systems

- **Data Lake**:
  - Stores raw data
  - File-based
  - Large scale

- **Data Warehouse**:
  - Structured relational database
  - Optimized for reporting

- **Data Lakehouse**:
  - Combines:
    - Data Lake (storage)
    - Data Warehouse (analytics + SQL)

---

## Roles in Data

- **Data Scientist**:
  - Works with raw data (often in data lakes)

- **Data Analyst**:
  - Queries structured data (data warehouse)

- **Business User**:
  - Uses dashboards and reports