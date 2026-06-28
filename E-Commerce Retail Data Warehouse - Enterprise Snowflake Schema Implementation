📌 Project Overview
This repository contains a production-grade implementation of an E-Commerce Retail Data Warehouse built using a Snowflake Schema design pattern. The project demonstrates the full end-to-end analytics pipeline: engineering a normalized relational data warehouse architecture in a backend database, optimization for complex relational traversal, and surfacing business-ready datasets for enterprise BI platforms.

🛠️ Tech Stack
Backend Database: Microsoft SQL Server

Data Modeling: Snowflake Schema (Dimensional Modeling)

Business Intelligence & Visualization: Power BI & MicroStrategy (MSTR)

🏗️ Architecture & Dimensional Modeling Approach
As a professional with 4 years of experience handling enterprise data structures, this project implements a Snowflake Schema to address data redundancy and optimize storage metrics. Low-cardinality attributes—such as geographical boundaries and product classifications—have been abstracted from primary dimension tables into explicit, normalized sub-dimensions to ensure strict data integrity.

Data Layer Hierarchy & Structural Relationships
Backend Foundation (SQL Server): Hosts the entire relational structure, leveraging optimized data types, indexing strategies, and primary/foreign key constraints to ensure referential integrity.

Core Metrics Layer (FactSales): A transactional grain fact table recording granular, line-item sales metrics including quantities, unit prices, and derived line-item revenue.

Normalized Product Hierarchy: A multi-layered dimension branch where individual stock items (DimProduct) map to localized sub-categories (DimSubCategory), which then roll up into master operational categories (DimCategory).

Normalized Customer & Geo Hierarchy: Customer profile data (DimCustomer) is decoupled from physical locations by mapping directly to a centralized geographic master register (DimGeography) containing cities, states, postal codes, and countries.

Conformed Time Dimension (DimDate): A unified calendar master table supporting standard date metrics, calendar quarters, and yearly blocks to enable seamless time-series and trend analytics.

📊 Business Intelligence & Visualization
Once the underlying analytical data models are structured and fully processed inside SQL Server, the semantic data warehouse layer is hooked directly into front-end business intelligence ecosystems.

For this implementation, Power BI and MicroStrategy (MSTR) are integrated strictly for enterprise visualization purposes. These tools consume the dimensional tables to transform raw relational data streams into clean, scannable corporate dashboards, grid matrices, and executive-ready reports.
