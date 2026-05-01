# Integrated Asset & Experiment Analytics Database

## Project Overview
This graduate-level end-to-end analytics engineering project was developed to design and implement a centralized analytics database that integrates laboratory asset management data with laboratory experiment data for improved operational visibility, maintenance compliance analysis, and cross-department traceability.

This project demonstrates full database lifecycle development from business requirements gathering through conceptual modeling, relational implementation, SQL analytics, Python reporting, and NoSQL conversion.

---

## Business Problem
Many biotechnology organizations manage:
- Enterprise Asset Management (EAM) systems for laboratory assets, maintenance, and location tracking
- ELN/LIMS systems for laboratory experiments, samples, and timelines

Because these systems are siloed, organizations struggle with:
- limited visibility of which assets were used in experiments
- difficult compliance and audit traceability
- inefficient manual cross-referencing
- poor cross-functional reporting

This project solves this by designing one integrated analytics database.

---

## Technical Skills Demonstrated
- Business Requirements Analysis
- EER Conceptual Modeling
- UML Class Diagram Design
- Relational Schema Mapping
- Database Normalization (3NF)
- MySQL Database Development
- Advanced SQL Query Engineering
- Python Jupyter Notebook Analytics & Visualization
- MongoDB Compass NoSQL Conversion
- Aggregation Pipeline Querying

---

## Conceptual & Relational Design
Developed:
- Enhanced Entity Relationship (EER) Model
- UML Class Diagram
- Normalized 10-Table Relational Schema

### Main Tables
- Experiment
- Asset
- Maintenance
- Sample
- Asset_Experiment

### Reference Tables
- Department
- Location
- Experiment_Type
- Sample_Type
- Maintenance_Type

The Asset_Experiment associative table resolves many-to-many asset usage tracking across experiments.

---

## SQL Engineering Highlights
Implemented advanced SQL analytical queries including:
- Simple condition filtering
- Aggregate reporting queries
- INNER JOIN and LEFT JOIN operations
- Nested subqueries
- Correlated subqueries
- EXISTS / NOT EXISTS logic
- UNION queries
- Subqueries in SELECT and FROM

These queries were used to analyze:
- overdue maintenance usage
- experiments with no sample records
- longest experiment durations
- asset service conditions
- sample volume trends

---

## Python Analytics Application
Built a Jupyter Notebook application connected to MySQL using Python to:
- execute SQL queries
- retrieve analytical datasets
- generate visual charts
- support reporting outputs

Visual analytics included:
- total experiments by status
- total samples by experiment
- experiments longer than average completion time

---

## MongoDB NoSQL Implementation
Converted the relational database into MongoDB collections and executed:
- document filtering
- projection queries
- sorting
- $lookup joins
- $unwind transformations
- $group aggregations

This demonstrated relational-to-NoSQL database translation and query flexibility.

---

## Tools & Technologies
MySQL | SQL | Python | Jupyter Notebook | MongoDB Compass | EER Modeling | UML Modeling | Database Normalization

---

## Included Files
- Full Technical Project Documentation PDF
- Project Presentation Slides

---

## Author
Charlotte Sy  
M.S. Data Analytics Engineering | Northeastern University
