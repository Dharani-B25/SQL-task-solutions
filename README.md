# SQL Task Solutions

Welcome to the **SQL Task Solutions** repository! This repository contains comprehensive SQL scripts designed for practicing database creation, table schema definition, data insertion, and solving various real-world data analysis queries across different domain datasets.

### Repository Structure & Modules

The repository is organized into five standalone SQL scripts, following a logical sequence from foundational SQL concepts to domain-specific analytical problems:

### 1. Employee Table Script (`Employee_Table_Script.sql`)
Focuses on core database administration and employee management data analytics.
* **Database:** `Employee_db`
* **Table:** `Employee`
* **Key Topics Covered:**
  * Basic Data Selection (`SELECT`, `WHERE`, `LIKE`, `IN`, `BETWEEN`)
  * Data Sorting (`ORDER BY`, `LIMIT`)
  * Aggregations & Metrics (`COUNT`, `AVG`, `MAX`, `MIN`, `SUM`)
  * Grouping & Filtering (`GROUP BY`, `HAVING`)
  * Advanced SQL Logic (`CASE WHEN` salary categorization, date/age functions using `TIMESTAMPDIFF`)

### 2. Operators & Expressions (`Operators & Expressions.sql`)
Designed as a beginner-friendly tutorial for understanding fundamental SQL operators and syntax logic.
* **Database:** `demo_db`
* **Table:** `Employees`
* **Key Topics Covered:**
  * Arithmetic Operators (`+`, `-`, `*`, `/`, `%`)
  * Comparison & Logical Operators (`AND`, `OR`, `NOT`)
  * String Operations & Pattern Matching (`CONCAT`, `UPPER`, `LOWER`, `LENGTH`, `LIKE`)
  * Date Functions (`CURDATE`, `NOW`, `DATE_ADD`)
  * Operator Precedence & Practice Queries

### 3. Student Career Analysis (`StudentCareer_Table Script.sql`)
Analyzes student academic metrics, skill sets, career goals, and placement outcomes.
* **Database:** `Student_db`
* **Table:** `StudentCareer`
* **Key Topics Covered:**
  * Complex Data Selection & Query Filtering
  * Department & Job Goal Summaries
  * Window Functions (`ROW_NUMBER()`, `DENSE_RANK()`, `PARTITION BY`)
  * Common Table Expressions (`WITH CTE AS ...`)
  * Subqueries for department-relative salary expectations

### 4. Healthcare Data Analysis (`Table_data_script.sql`)
Explores patient health records, disease metrics, hospital stay durations, and treatment billing analytics.
* **Database:** `hospitality`
* **Table:** `PatientRecords`
* **Key Topics Covered:**
  * Patient Demographics & Disease Distribution
  * Hospital Stay Calculations (`DATEDIFF`)
  * Revenue & Billing Analytics by Disease and Location
  * Medical Risk Identifiers (High BP, High Cholesterol, High BMI checks)
  * Multi-level Ranking using `RANK() OVER (PARTITION BY ...)`


### 5. Movies Data Analysis (`movies_data.sql`)
Focuses on relational database design, data normalization, and entertainment industry data querying.
* **Database:** `movies`
* **Tables:** `MOVIES`, `act_mast`, `lang_mast`, `mov_det`
* **Key Topics Covered:**
  * Relational Schema Normalization (Master tables & foreign key maps)
  * Database Joins (`INNER JOIN`)
  * Actor, Director, and Release Year Summaries
  * Multi-language Film Statistics
