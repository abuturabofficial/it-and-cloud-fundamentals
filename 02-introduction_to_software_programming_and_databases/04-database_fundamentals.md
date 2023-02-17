<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Types of Data, Sources, and Uses](#types-of-data-sources-and-uses)
  - [What is data?](#what-is-data)
    - [Forms of data](#forms-of-data)
    - [Types of data](#types-of-data)
    - [Data Sources](#data-sources)
    - [Using data](#using-data)
- [Database Fundamentals and Constructs](#database-fundamentals-and-constructs)
  - [What is a database?](#what-is-a-database)
  - [Components of a database](#components-of-a-database)
  - [Database constructs](#database-constructs)
  - [Database query](#database-query)
  - [Database constraints](#database-constraints)
  - [Database characteristics](#database-characteristics)
  - [Flat file vs. database](#flat-file-vs-database)
- [Database Roles and Permissions](#database-roles-and-permissions)
  - [Database permissions](#database-permissions)
    - [Permission commands](#permission-commands)
  - [Database roles](#database-roles)
    - [Benefits of roles](#benefits-of-roles)
- [Database types](#database-types)
    - [Structured data type](#structured-data-type)
    - [Semi-structured data type](#semi-structured-data-type)
    - [Unstructured data type](#unstructured-data-type)
  - [Relational database](#relational-database)
  - [Non-relational database](#non-relational-database)
- [Interfacing with Databases](#interfacing-with-databases)
  - [What is a database interface?](#what-is-a-database-interface)
  - [Principles of a database interface](#principles-of-a-database-interface)
  - [How to access a database](#how-to-access-a-database)
- [Database Management](#database-management)
  - [Managing databases with SQL commands](#managing-databases-with-sql-commands)
    - [SQL command Categories](#sql-command-categories)
  - [Inputting and importing data](#inputting-and-importing-data)
  - [Extracting data from a database](#extracting-data-from-a-database)
- [Backing Up Databases](#backing-up-databases)
  - [What is a database backup?](#what-is-a-database-backup)
    - [Physical database backups](#physical-database-backups)
    - [Logical database backups](#logical-database-backups)
    - [Backup pros and cons](#backup-pros-and-cons)
  - [Database backup methods](#database-backup-methods)
  - [Backup Management](#backup-management)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Types of Data, Sources, and Uses

### What is data?

A set of characters gathered and translated for some purpose, usually analysis

![](images/Pasted%20image%2020230217143041.png)

Common types:
- Single character
- Boolean (true or false)
- Text (string)
- Number (integer or floating point)
- Picture
- Sound
- Video

![](images/Pasted%20image%2020230217143228.png)

#### Forms of data

 ![](images/Pasted%20image%2020230217143341.png)

#### Types of data

Categorized by level and rigidity

**Structured data**
- Structured in rows and columns
- Well-defined with rigid structure
- Relational databases
- Microsoft SQL server
- IBM Db2
- Oracle database

**Semi-structured data**
- Some organizational properties
- Not in rows or columns
- Organized in hierarchy using tags and metadata
- Non-relational database

**Unstructured data**
- No identifiable structure, specific format, sequence, or rules
- Most common include text, email
- Also images, audio files, and log files

**Examples of Semi and Unstructured data**
- MonoDB
- Hbase
- Cassandra DB
- Oracle NoSQL DB

#### Data Sources

![](images/Pasted%20image%2020230217144419.png)

#### Using data

Data sources may be internal or external

**Internal**
- Collects data from reports or records from organization
- Known as internal sourcing
- Accounting
- Order processing
- Payroll
- Order shipping

**External**
- Collects data from outside the organization
- Known as external sourcing
- Social media feeds
- Weather reports
- Government
- Database and research

## Database Fundamentals and Constructs

### What is a database?

![](images/Pasted%20image%2020230217144750.png)

### Components of a database

**Schema**
- Collection of tables of data
- A database can have more than one schema

**Table**
- One or more columns of data
- Two or more columns of stored data

**Column**
- A pillar of information containing one or more data or values
- Can contain dates, numeric or integer values, alphabetic values

**Row**
- A horizontally formatted line of information like rows in Excel
- 100s or 1000s rows of data are typically in a table

### Database constructs

**Queries**
- Request for data
- Provide answers
- Perform calculations
- Combine data
- Add, change, or delete data

**Constraints**
- Primary and foreign key enforce rules
- Values in columns not repeated
- Limit the type of data
- Ensure data accuracy and reliability

### Database query

![](images/Pasted%20image%2020230217145405.png)

### Database constraints

![](images/Pasted%20image%2020230217145529.png)

### Database characteristics

 ![](images/Pasted%20image%2020230217145648.png)

### Flat file vs. database

| Flat File                        | Database                                 |
| -------------------------------- | ---------------------------------------- |
| Stores data in single table      | Uses multiple table structures           |
| Set in various application types | Tables are organized in rows and columns |
| Sorted based on column values    | One piece of data per column             |
| Solution for simple tasks        | Faster, more efficient, more powerful    |

![](images/Pasted%20image%2020230217150114.png)

![](images/Pasted%20image%2020230217150159.png)

## Database Roles and Permissions

### Database permissions

Three types of permissions:

**Database**
- Right to execute a specific type of SQL statement
- Access second person’s object
- Controls use of computing resources
- Does not apply to DBA

**System**
- Right to perform any activity
- Ability to add or delete columns and rows

**Object**
- Right to perform specific actions
- Allows user to INSERT, DELETE, UPDATE, or SELECT data
- Object’s owner has permissions for object

#### Permission commands

![](images/Pasted%20image%2020230217150715.png)

### Database roles

![](images/Pasted%20image%2020230217150813.png)

#### Benefits of roles

![](images/Pasted%20image%2020230217150909.png)

## Database types

#### Structured data type

- Tabular data, columns, and rows
- These databases are called relational databases
- Formed set of data
- All rows have same columns

![](images/Pasted%20image%2020230217151149.png)

#### Semi-structured data type

- Some structure
- Documents in JavaScript Object Notation (JSON) format
- Include key-value stores and graph database

![](images/Pasted%20image%2020230217151315.png)

#### Unstructured data type

- Not in pre-defined structure or data model
- Text heavy files, but may contain numbers and dates
- Videos, audio, sensor data, and other types of information

![](images/Pasted%20image%2020230217151438.png)

### Relational database

| Relational                                                          | Non-Relational                                                                                                                   |
| ------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| Structured to recognize relations among stored items of information | Stores data in a non-tabular form, and tends to be more flexible than the traditional, SQL-based, relational database structures | 

![](images/Pasted%20image%2020230217151905.png)

### Non-relational database

![](images/Pasted%20image%2020230217152011.png)

Permit storing, store data in a format that closely meets the original structure.

Most common types of data stores:
- **Document data stores**
	- Handles
		- Objects
		- Data values
	- Named string fields in an entity referred to as a document
	- Generally store data in the form of JSON documents
![](images/Pasted%20image%2020230217152507.png)

- **Key-value stores**
![](images/Pasted%20image%2020230217152546.png)

- **Column-oriented databases**
![](images/Pasted%20image%2020230217152637.png)

- **Graph databases**
![](images/Pasted%20image%2020230217152812.png)

## Interfacing with Databases

### What is a database interface?

Enable users to input queries to a database

![](images/Pasted%20image%2020230217153214.png)

### Principles of a database interface

![](images/Pasted%20image%2020230217153302.png)

### How to access a database

Types of access:

**Direct**
- Enters SQL commands
- Selects a menu
- Accesses tables directly
- Works well with locally stored database or local area network

**Programmatic**
- Accesses' database using programming language
- Enables data to be used in more ways
- Safer than using direct access
- Oracle databases support access from many languages
- Might be necessary to perform a query with a supported language

**User interface**
- Microsoft Access permits access to user interface
- Optional user interface may be needed
- Oracle offers MySQL Workbench as a graphical user interface
- Allows ability to input queries without the query language
- Menu-base interface
- Forms-based interface
- GUI displays schema in diagrammatic form
- Specific query by manipulating diagram
- GUIs utilize both menus and forms
- GUIs using point device to pick sections of displayed schema diagram
- Natural language interfaces accepts user requests and tries to interpret it
- These interfaces have own schema like database conception schemas
- Search engine example of entering and retrieving information using natural language

**Query**
- Find specified data using SELECT statement
- Query and reporting function included with software like Microsoft Access
- Query Builder’s GUI is designed to enhance productivity and simplify query tasks
	- SQL or SQL displayed visually
	- Has pane displaying SQL text
	- Related tables determined by Query Builder that constructs join command
	- Query and update database using SELECT statement
	- Quickly view and edit query results
	- Examples: 
		- Chartio Visual SQL
		- dbForge Query Builder for SQL Server
		- Active Query Builder
		- FlySpeed SQL
		- QueryDbVis Query Builder
- Drag multiple tables, views, and columns to generate SQL statements

## Database Management

### Managing databases with SQL commands

- Queries refer to request information from a database
- Queries generate data of different formats according to function
- Query commands perform the data retrieval and management in a database

![](images/Pasted%20image%2020230217155210.png)

#### SQL command Categories

**DDL**
- SQL commands that define database schema
- Create, modify, and delete database structures
- Not set by general user

**DML**
- SQL commands that manipulate data

**DCL**
- SQL commands for rights, permissions, and other database system controls

![](images/Pasted%20image%2020230217155819.png)

### Inputting and importing data

Data is input manually into a database through queries.

![](images/Pasted%20image%2020230217155953.png)

Another way is through importing data from different sources.
- SQL Server Import Export Wizard
- SQL Server Integrated Services (or SSIS)
- OPENROWSET function

### Extracting data from a database

![](images/Pasted%20image%2020230217160329.png)

## Backing Up Databases

### What is a database backup?

Two backup types:
- Logical
- Physical

![](images/Pasted%20image%2020230217160537.png)

#### Physical database backups

- Needed to perform full database restoration
- Minimal errors and loss
- Full or incremental copies

#### Logical database backups

- Copies of database information
- Tables, schemas, procedures

#### Backup pros and cons

| Physical backup                      | Logical backup                  |
| ------------------------------------ | ------------------------------- |
| Pros:                                | Pros:                           |
| Simple and fast, despite format      | Only selected data is backed up |
| Mirror copy loaded to another device | Saves time and storage          |
| Cons:                                | Cons:                           |
| Used only to recreate system         | No file system information      |
| Cannot do full restore               | Complications restoring process | 

### Database backup methods

**Full**
- Stores copies of all files
- Preset schedule
- Files are compressed but may need large storage capacity

**Differential**
- Simplifies recovery
- Requires last full backup
- Last differential back up for full recovery

**Incremental**
- Saves storage
- Back up files generated or updated since last backup

**Virtual**
- Uses' database to track and maintain data
- Helps avoid pitfalls of other backup methods

### Backup Management

![](images/Pasted%20image%2020230217161508.png)