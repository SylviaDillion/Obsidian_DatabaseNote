---
github_repo: Sylvia|ObsidianNote
---
# data
- raw facts
- building blocks of information
- unprocessed information

# information
- data processed to reveal meaning
- data with context

# Type of Data
- raw data
- pre-processed
- compressed

# Database
> shared, integrated computer structure that stores

- end user data(raw facts)
- metadata(data about data)

# Manual File System
- collection of file folders kept in file folders
- Organization within folders based on data's expected use(ideally logically related)
- System adequate for small amounts of data with few reporting requirements
- Finding and using data in growing collection of file folders became time-consuming and cumbersome

# Problems of File System Data Management
- Time-consuming, high-level activity
- As number of file expands, system administration becomes difficult
- Making changes in existing file structure is difficult
- File structure changes require modifications in all programs that use data in that file
- Modification are likely to produce errors, requiring additional time to "debug" the program
- Security features hard to program and therefore often omitted

# Data Redundancy
- Data redundancy results in data inconsistency
	Different and conflicting version of the same data appear in different places
-  Errors more likely to occur when complex entries are made in several different files and/or recur frequently in one or more files
- Data anomalies develop when required changes in redundant data are not made successfully

# Types of Data Anomalies
- update anomalies
- insertion anomalies
- deletion anomalies

---
# Data System Composition
is composed of five main parts:  **Hardware**, **Software**, **People**, **Procedure**, **Data**.
## Hardware
**physical parts of the computer**
It includes various **storage devices** like hard disks and input-output devices like monitors, printers etc.
	Hardware is the most visible part of any information system: the equipment such as **computers**, **scanners**, and **printers** that are used to **capture data, transform it and present it** to the user as output.

## Software
	Main component of a database management system
Software is **a collection or set of programs or instructions** that tell a computer what to do
It includes the **database software**, **operating system**, **network software** used to share the data with other users, and the applications used to access the data.
Some DBMS software examples include MySQL, PostgreSQL, Microsoft Access, SQL Server, FileMaker, Oracle, RDBMS, dBASE, Clipper, and FoxPro.

## People
**control and manage the databases**
- the people include **database administrators, software developer and end-user**
- Database administrator is the one who manages the complete database management system. **DBA takes care of the security of the DBMS, its availability, managing the license keys, managing user accounts and access, etc**

## Procedure
**general instructions to use a database management system**
This includes procedures to set up and **install a DBMS, To login and logout of DBMS software, manage databases, take backups, generate reports etc.**

## Data
The word data covers the **collection of facts stored in the database.**
Data stored in the database includes **structure data, nonstructural data, and logical data**
The typical database contains both the **metadata (data about data) and the actual (operational) data.**

# DBMS (database management system)
## Advantages of the DBMS
- End users have better access to more and bettermanaged data
- Promotes integrated view of organization’s operations
- Probability of data inconsistency is greatly reduced
- Possible to produce quick answers to ad hoc queries

## DBMS Functions
1. Data dictionary management
	defines data elements and their relationships
2. Data storage management
	stores data and related data entry forms, report definitions, etc.
3. Data transformation and presentation
	translates logical requests into commands to physically locate and retrieve the requested data
4. Security management
	enforces user security and data privacy within database
5. Multiuser access control
	uses sophisticated algorithms to ensure multiple users can access the database concurrently without compromising the integrity of the database
6. Backup and recovery management
	provides backup and data recovery procedures
7. Data integrity management
	promotes and enforces integrity rules
8. Database access languages and application programming interfaces
	provide data access through a query language
9. Database communication interfaces
	allow database to accept end-user requests via multiple, different network environments

![[Pasted image 20251102211707.png]]
# Why Database Design is Important
- Defines the database’s expected use
- Different approach needed for different types of databases
- Avoid redundant data
- Poorly designed database generates errors  
	- leads to bad decisions
	- can lead to failure of organization


![[Pasted image 20251102212127.png]]