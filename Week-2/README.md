# E-Commerce Order Management Database System

## Week 2 – Entity and Relationship Analysis

## Project Overview

This repository contains the **Week 2** deliverables of the **E-Commerce Order Management Database System** project. During this phase, the focus is on analyzing the entities involved in the system, identifying their attributes, defining Primary Keys (PK) and Foreign Keys (FK), and studying the relationships and cardinality between entities. This analysis forms the foundation for creating the Entity Relationship Diagram (ERD) and designing the database.

## Objective

The main objective of Week 2 is to:

* Identify all entities required for the system.
* List the attributes of each entity.
* Define Primary Keys (PK) for all entities.
* Identify Foreign Keys (FK) wherever applicable.
* Analyze the relationships between entities.
* Determine the cardinality of each relationship.
* Prepare the Entity and Relationship Analysis Report.

## Entities Used

The project uses the following core entities:

* Customer
* Category
* Product
* Supplier
* Order
* Order Details
* Payment
* Shipment
* Review

## Documents Included

* Entity Analysis Report.docx
* Entity Relationship Analysis Report.docx

## Primary Keys

Each entity contains a unique Primary Key:

* Customer → Customer_ID
* Category → Category_ID
* Product → Product_ID
* Supplier → Supplier_ID
* Order → Order_ID
* Order Details → Order_Detail_ID
* Payment → Payment_ID
* Shipment → Shipment_ID
* Review → Review_ID

## Foreign Keys

The following Foreign Keys establish relationships between entities:

* Product → Category_ID
* Order → Customer_ID
* Order Details → Order_ID
* Order Details → Product_ID
* Payment → Order_ID
* Shipment → Order_ID
* Review → Customer_ID
* Review → Product_ID

## Learning Outcomes

By completing Week 2, the following concepts were learned:

* Entity Identification
* Attribute Analysis
* Primary Key Identification
* Foreign Key Identification
* Relationship Analysis
* Cardinality Analysis
* Data Integrity Constraints
* Database Design Fundamentals

## Future Work

The analysis completed in Week 2 will be used in the upcoming project phases to:

* Create the Entity Relationship Diagram (ERD)
* Perform Database Normalization
* Design Database Tables
* Implement SQL Queries
* Generate Business Reports
