# dialloTech-dabase-devops

 # 🏥 New York City Hospital Capstone Project
Overview
This capstone project focuses on analyzing hospital performance and healthcare outcomes across New York City. By combining robust data modeling, relational database design, and interactive visual analytics, the project aims to uncover patterns and insights that can support healthcare planning and decision-making.

## Objectives
Design an efficient healthcare data model representing hospital operations

Build a relational database in SQL Server to store and manage hospital data

Perform data analysis to explore patient admissions, treatments, outcomes, and resource utilization

Develop interactive Tableau dashboards to communicate findings to stakeholders

## Tools & Technologies
Erwin – Data modeling (conceptual, logical, and physical models)

SQL Server – Database implementation, data storage, and querying

SQL – Data manipulation and analysis

Tableau – Visualization and interactive dashboard development

Excel/CSV – Initial data formatting and ingestion

## Data Sources
New York State Department of Health (NYSDOH) – Hospital and patient discharge datasets

CMS Hospital Compare – Quality ratings and metrics

U.S. Census Bureau – Demographic and geographic context

Project Workflow
## Data Modeling:

Designed a healthcare data model in Erwin, capturing entities like hospitals, patients, diagnoses, treatments, and outcomes.

Generated physical model for implementation in SQL Server.

## Database Implementation:

Created tables, relationships, and indexes in SQL Server based on Erwin design.

Loaded and validated data from public health sources.

## Data Analysis:

Wrote SQL queries to extract insights on hospital utilization, outcomes, readmissions, and cost trends.

Visualization:

Built Tableau dashboards to present KPIs, heatmaps, and drill-down analyses by hospital, region, and time period.

Urban hospitals reported higher readmission rates, particularly in low-income ZIP codes.

Resource distribution disparities were evident in staffing levels across regions.

Seasonal peaks in ER admissions corresponded with demographic vulnerability.

## Folder Structure
graphql

📁 erwin-models/       # Data model files (.erwin) ``
📁 sql-scripts/        # SQL Server table creation, ETL, and queries``  
📁 tableau-dashboards/ # Packaged Tableau dashboards (.twbx)  ``
📁 data/               # Raw and cleaned datasets (CSV, Excel)  ``
📁 docs/               # Reports, presentation slides, and documentation``  
📄 README.md           # Project overview and setup  ``
## How to Use
Review Data Model: Open .erwin files to explore the conceptual/logical design.

SQL Server Setup:

Run scripts in /sql-scripts/ to create schema and load data.

Visualize:

Open .twbx files in Tableau Desktop to explore the dashboards interactively.

Author
[Your Name] – Data Modeling, Database Development, Analytics, and Visualization
