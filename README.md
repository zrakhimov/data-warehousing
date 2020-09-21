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
  
* Follow up to this course is a **Big Data**

### Market Observations

1. There's increasing pressure to perform analytics where data gets created.

2. Event-driven applications will enable new analytic use cases

3. Business applications are leveraging both SQL and NoSQL data in structured repositories for analytics

4. Hybrid cloud capabilities of software support economies of scope

5. Private cloud needs cloud-scale convenience.

6. Diverse data sources support an ecosystem of innovation


## Business Requirements and Business Process Dimension Models

* Kimball Lifecycle

This is basically a diagram outlining the various flows and objects required in a data warehouse. As we go through this topic, we'll touch on every box on this diagram.

![Kimball Lifecycle](week-2/images/kimball-lifecycle.png)

We're going to talk about **dimentional modelling** and **business requirements**

### Business Requirement

* Data Warehouse shouldn't be built based on IT, rather **should be business driven**
* IT organization is ultimately responsible for **implementation**, but all the sponsorship and drive will come from the busines side.

* **Data Warehouse** - most lines of businesses have their own unique requirements. 
  * Internet
  * Landline
* **Enterprise-level Data Warehouse** - strategy that crossess all lines of businesses and pulls all the warehouses together.
  * Enterprise-leve business requirements:
    - Conduct business and IT interviews
    - Conduct reviews of enterprise requirements
    - Well defined success criteria
    - Data Auditing / Data Profiling
    - Interview Summary
    - Business Requirements category to supporting business process:
    
    ![Alt](week-2/images/business-processes.png)
    
    
    

























