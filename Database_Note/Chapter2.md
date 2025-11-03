# Database System Concepts
- **Data**: Information stored in a structured form
- **Database**: A structured collection of data stored electronically
- **DBMS(Database Management System)**: A software system that manages databases and allow users to interact with data
- **Data Model**: The way data is logically structured and represented
- **Queries**: A way to retrieve or manipulate data using languages like SQL.

# Data Schema
- **Entity**: A definable thing--such as a person, object, concept and event, that can have data stored about it.
- **Attribute**: A property or characteristics of an entity. Shown in columns and rows
- **Relationship**: How entities act upon each other or are associated with each other
- **Relation**: a relation with columns and rows
- **Tuple**: a tuple is a row of a relation
- **Cardinality**: the cardinality of a relation is the number of tuples it contains

# Characteristics of a Relation
![[Pasted image 20251103205037.png]]

# E-R Diagram(Entity Relationship Diagram)
An Entity Relationship Diagram is a type of flowchart that illustrates how "entities" such as people, objects, or concepts relate to each other within a system. 
> Also known as ERDs or ER Models, they use a defined set of symbols such as rectangles, diamonds, ovals and connecting lines to depict the **interconnectedness** of entities, relationships and their attributes.

**Rectangles**->entity sets
**Diamonds**->relationship sets
**Lines**->link attributes to entity sets and entity sets to relationship sets
**Ellipses** represent attributes
		a. **Double Ellipses** represents multivalued attributes
		b. **Dashed Ellipses** denote derived attributes
**Underline** indicates primary key attributes

# Key
**composite key** is a key that contains **two or more** attributes
**primary key** is a **candidate key** chosen to be the main key for the relaton
> If you know the value of the primary key, you will be able to** uniquely** identify a single row.

**surrogate key** is a **unique**, **numeric** value that is added to a relation to serve as the primary
> Surrogate key values have no meaning to users and are usually hidden on forms, queries, and reports.
> A surrogate key is often used in place of a composite primary key.

A **foreign key** is a **primary key** from one table placed into another table.

**Referential integrity** states that every value of a foreign key must match a value of an existing primary key.

# The Problem of Null Values
A Null is often **ambiguous**. It could mean:
- The column value is not appropriate for the specific row.
- The column value is not decided
- The column value is unknown

# Database Architecture
## 1-Tier Architecture
**directly available to the user** 
- frequently updated ❎
- Multiple users ❎
- A direct and simple method of modifying or accessing the database ✅

## 2-Tier Architecture
The database resides on **a server**, and **a client application** accesses the data through a DBMS

- use it simultaneously by multiple users✅
- being handled solely by the server, it has a high processing capability
- Direct connection and enhanced performance provide faster access to the database.

## 3-Tier Architecture
Involves **a client (user interface), application server (logic processing), and database server (data storage)**. This is common for enterprise systems.

- **Database (Data) Tier**: This is where the actual database is stored and managed.
- **(Middle) Tier**: This layer contains the application or software that connects the user to the database.
- **User (Presentation) Tier**: This is the part the user interacts with, like a web interface or app. The user doesn’t see or know about the database behind it.