# Introduction to Data Warehousing

## Basic Concepts

* Companies run their businesses with OLTP (On-Line Transaction Processing) - also known as "Systems of Record"
  * Sales suport, order tracking, banking actions, customer support etc.
  
* Companies want to know things about their business (perform analytics)
  * Report on results
  * Historical analysis
  * Identify trends
  * Predict future results
  
* This can be accomplished in a couple of ways: 
  1. Directly against the **OLTP** system
  2. Building a dedicated Data Warehouse system (**OLAP**)
  
* What is a Data Warehousing?
  * Data Warehousing is a system used for reporting and data analysis
  * Data Warehouses are a central repository for data from one or more sources
  * Data Warehouses store current and historical data

* Terms used with Data Warehousing?
  * Warehousing
  * Analytics
  * Operational Analytics
  * Mining
  * Enterprise Data Warehouses (EDW)
  * Operational Data Store (ODS)
  * Physical Data Marts
  * Logical Data Marts
  * On-line Analytic Processing (OLAP)
  
* ETL and ELT (Extract Transform Load and Extract Load Transorm)
  * How data moves in the infrastructure which includes a Data Warehouse
  
* DSS (Decision Support System ) 
  * Turning data into information
  
* Mixed workloads vs dedicated analytic platforms
  * Benefits of optimizing systems for a particular workload

* Data Warehouse characteristics
  * Batch based vs continual data ingest
  * Cleansed
  * Re-structured
  * Optimized for reporting, querying, analytics
  * Organizes data into non-volatile, subject-specific groupings
  * Multiple data sources
  
* On-line Analytic Processing (OLAP)
  * Relational OLAP (ROLAP)
  * Multi-dimensional OLAP (MOLAP)
  
* Facts, Dimentsions, Start-Schema, Snowflake, Hierarchies, Cubes


* What is **EDW (Enterprise Data Warehouse)** ?

  * It's  combination of:
  1. Copy of Operational Systems
  2. Trusted Data
  3. Deep analytics & modeling
  4. Reporting & interactive analysis
