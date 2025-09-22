# Startup Ecosystem Database  

A PostgreSQL-based database management system designed to manage and analyze data within the startup ecosystem. This project tracks startups, founders, investors, mentors, accelerators, partnerships, and ecosystem resources, providing insights for collaboration, funding, and growth.  

---

## 📌 Features  
- Centralized database for startups, investors, mentors, and accelerators  
- ER diagrams and relational schema design (using Draw.io)  
- Normalized schema (up to 3NF) to remove redundancy and anomalies  
- DDL & DML scripts for database creation and population  
- SQL queries for funding analysis, stakeholder management, and ecosystem metrics  
- JDBC + Java GUI for CRUD operations (insert, update, delete, search)  
- Role-based access and user privileges for different stakeholders  

---

## 🛠️ Tech Stack  
- **Database:** PostgreSQL  
- **Backend / Interface:** Java (JDBC)  
- **Design Tools:** Draw.io (ER & Class Diagrams)  
- **Languages:** SQL, Java  
- **Other:** Normalization techniques (1NF–3NF), CRUD  
---

## 🚀 Getting Started  

### Prerequisites  
- PostgreSQL installed  
- Java (JDK 8+)  
- JDBC driver for PostgreSQL  

### Setup Instructions  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/startup-ecosystem-db.git
2. Create the database in PostgreSQL:
   ```bash
   CREATE DATABASE startup_ecosystem;
3. Run DDL scripts to create tables:
   ```bash
   psql -d startup_ecosystem -f ddl_scripts/create_tables.sql
4. Populate sample data using DML scripts:
   ```bash
   psql -d startup_ecosystem -f dml_scripts/insert_data.sql
5. Run SQL queries from /queries for analysis.

6. Use the Java GUI (/gui) for CRUD operations.
