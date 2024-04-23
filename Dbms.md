# DBMS

Database Management System (DBMS) is a software system that allows users to define, create, maintain, and control access to databases. It serves as an interface between the database and the end-users or application programs, ensuring efficient and organized management of data.

# key aspects of a DBMS:

1) Data Organization: DBMS organizes data into structured formats, typically tables, rows, and columns, based on predefined schemas. This structured organization allows for efficient storage, retrieval, and manipulation of data.

2) Data Integrity and Security: DBMS ensures data integrity by enforcing constraints and rules defined during database design. It also provides mechanisms for data security, such as access control and encryption, to protect sensitive information from unauthorized access or manipulation.

3) Data Querying and Manipulation: Users can retrieve, update, insert, and delete data from the database using SQL (Structured Query Language) or other query languages supported by the DBMS. These queries allow users to interact with the database and perform various operations on the data.

4) Concurrency Control and Transaction Management: DBMS manages concurrent access to the database by multiple users or applications to ensure data consistency. It employs techniques like locking and timestamp-based concurrency control to handle simultaneous transactions effectively. Additionally, it supports transaction management, enabling users to execute multiple database operations as a single logical unit, ensuring atomicity, consistency, isolation, and durability (ACID properties).

5) Data Backup and Recovery: DBMS provides mechanisms for data backup and recovery to prevent data loss due to hardware failures, system crashes, or human errors. It allows users to create backups of the database at regular intervals and restore the data to a consistent state in case of failures.

6) Data Modeling and Schema Design: Before creating a database, users define its structure and organization using data modeling techniques. DBMS supports various data models, such as relational, hierarchical, network, or object-oriented, allowing users to choose the most suitable model for their requirements. It also assists in schema design, defining the structure, constraints, and relationships of the database entities.

7) Scalability and Performance Optimization: DBMS offers features for scaling databases to accommodate growing data volumes and optimizing performance to ensure efficient data processing. It includes indexing, query optimization, caching, and partitioning techniques to enhance database performance and scalability.

# Data Models

1) Data models provide a structured way to represent and organize data within a database. They define the logical structure of the database and the relationships between different types of data. 

2) Relational Data Model: The relational model organizes data into tables, where each table consists of rows (tuples) and columns (attributes). Relationships between tables are established through keys, such as primary keys and foreign keys. Relational databases, such as MySQL, PostgreSQL, and Oracle, implement this model.

3) Entity-Relationship (ER) Model: The ER model represents entities (objects), attributes of entities, and relationships between entities. Entities are represented as rectangles, attributes as ovals, and relationships as diamonds. This model is commonly used in database design to visualize and specify the structure of a database.

4) Hierarchical Data Model: The hierarchical model organizes data in a tree-like structure, with parent-child relationships between data elements. Each parent can have multiple children, but each child has only one parent. This model was popular in early database systems, such as IMS (Information Management System).

5) Network Data Model: The network model extends the hierarchical model by allowing each child to have multiple parents, creating a more flexible structure. Data is organized into nodes and links, representing entities and relationships between them. This model was popular in the 1960s and 1970s, but it's less commonly used today.


# Database languages

Database languages are specialized programming languages used to interact with databases. They enable users to perform various operations such as querying, updating, and managing data stored in a database.


1) SQL (Structured Query Language):

SQL is a standard language for relational database management systems (RDBMS).
It is used to perform operations like data retrieval (SELECT), data manipulation (INSERT, UPDATE, DELETE), and data definition (CREATE, ALTER, DROP).
SQL is a declarative language, meaning that users specify what they want to retrieve or manipulate rather than how to do it.
Variants of SQL include MySQL, PostgreSQL, SQLite, Oracle SQL, Microsoft SQL Server, and others.

2) PL/SQL (Procedural Language/SQL):

PL/SQL is an extension of SQL used in Oracle databases.
It allows users to write procedural code, including loops, conditionals, and exception handling, within SQL statements.
PL/SQL is often used to create stored procedures, functions, triggers, and packages for database programming and automation.

3) T-SQL (Transact-SQL):

T-SQL is an extension of SQL used in Microsoft SQL Server databases.
It includes additional features such as procedural programming constructs (e.g., IF...ELSE, WHILE loops), error handling, and system functions.
T-SQL is commonly used for database administration, development, and business intelligence tasks.

4) Data Definition Languages (DDL):

DDLs are used to define the structure and organization of a database schema.
They include commands like CREATE TABLE, ALTER TABLE, and DROP TABLE for creating, modifying, and deleting database objects.

5) Data Manipulation Languages (DML):

DMLs are used to manipulate data within a database.
They include commands like SELECT, INSERT, UPDATE, and DELETE for querying, inserting, updating, and deleting data in database tables.

6) Data Control Languages (DCL):

DCLs are used to control access to the database and manage user permissions.
They include commands like GRANT and REVOKE for granting and revoking privileges on database objects.


# Database Administrator

A Database Administrator (DBA) is a professional responsible for the design, implementation, maintenance, and security of an organization's databases. They play a critical role in ensuring that databases run smoothly, efficiently, and securely to meet the needs of the organization. 

1) Database Design and Planning:

Collaborating with stakeholders to understand business requirements and design database schemas that meet those requirements.
Choosing appropriate data models, database platforms, and technologies based on the organization's needs and constraints.
Planning for scalability, performance optimization, and disaster recovery.

2) Database Installation and Configuration:
Installing and configuring database management systems (DBMS) software on servers or cloud platforms.
Setting up database instances, configuring parameters, and allocating resources such as memory, CPU, and storage.
Ensuring proper integration with other systems and applications.

3) Database Security:
Implementing and maintaining security measures to protect databases from unauthorized access, data breaches, and other security threats.
Managing user access and permissions, including role-based access control (RBAC), to ensure that users have appropriate privileges.
Monitoring database activity and auditing logs to detect and respond to security incidents.

4) Data Backup and Recovery:
Developing and implementing backup and recovery strategies to prevent data loss and ensure business continuity.
Scheduling and automating regular backups, including full backups, incremental backups, and transaction log backups.
Testing backup and recovery procedures to verify their effectiveness and reliability.

5) Performance Monitoring and Tuning:
Monitoring database performance metrics such as CPU usage, memory utilization, disk I/O, and query execution times.
Identifying performance bottlenecks and tuning database configurations, indexes, and queries to improve efficiency and response times.
Analyzing and optimizing database schema design and data access patterns.

# Database Users

Database users are individuals or entities who interact with a database system to perform various tasks, such as querying data, updating records, and generating reports. These users can be categorized into different roles based on their responsibilities and permissions within the database environment.

1) End Users:

End users are individuals who directly interact with the database system to retrieve information, input data, or perform transactions.
They may use front-end applications, such as web interfaces or desktop software, to access and manipulate data stored in the database.
Examples of end users include employees entering sales orders, customers browsing products on an e-commerce website, or students accessing their 
grades online.

2) Database Administrators (DBAs):

Database administrators are responsible for managing and maintaining the database system, ensuring its reliability, performance, and security.
They perform tasks such as database design, installation, configuration, backup and recovery, security management, and performance tuning.
DBAs may also be responsible for setting up user accounts, defining access controls, and providing technical support to database users.

3) Database Developers:

Database developers are responsible for designing, implementing, and optimizing database schemas, queries, and stored procedures.
They write SQL queries, create database objects (tables, views, indexes), and develop application code that interacts with the database.
Database developers work closely with software developers, business analysts, and other stakeholders to ensure that database systems meet 

4) application requirements.

Data Analysts and Report Writers:
Data analysts and report writers analyze data stored in the database to derive insights, generate reports, and make data-driven decisions.
They write complex queries, perform data aggregation, visualization, and statistical analysis to extract meaningful information from the database.
Data analysts may use business intelligence (BI) tools, reporting software, or custom scripts to access and analyze data.

5) System Administrators:

System administrators are responsible for managing the underlying infrastructure and resources that support the database system.
They oversee server maintenance, network configuration, security updates, and performance monitoring to ensure the reliability and availability of the database environment.
System administrators may also manage backups, disaster recovery plans, and high-availability solutions to minimize downtime and data loss.

# Three Schema architecture of DBMS

![alt text](dbms-three-schema-architecture.png)

1) Internal Schema

The internal level has an internal schema which describes the physical storage structure of the database.
The internal schema is also known as a physical schema.
It uses the physical data model. It is used to define that how the data will be stored in a block.
The physical level is used to describe complex low-level data structures in detail

2) Conceptual Level

The conceptual schema describes the design of a database at the conceptual level. Conceptual level is also known as logical level.
The conceptual schema describes the structure of the whole database.
The conceptual level describes what data are to be stored in the database and also describes what relationship exists among those data.
In the conceptual level, internal details such as an implementation of the data structure are hidden.
Programmers and database administrators work at this level.

3) External Level

At the external level, a database contains several schemas that sometimes called as subschema. The subschema is used to describe the different view of the database.
An external schema is also known as view schema.
Each view schema describes the database part that a particular user group is interested and hides the remaining database from that user group.
The view schema describes the end user interaction with database systems.