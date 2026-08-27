 Snowflake

Overview
This folder contains the Snowflake database setup and SQL scripts.

 Contents
- Database creation
- Schema creation
- Tables
- Views
- SQL scripts
- Screenshots

  # Snowflake

Snowflake was used as the cloud data warehouse to store and analyze the e-commerce data loaded from Shopify through Fivetran.

## Database Creation

Created the `TEST` database in Snowflake to store the e-commerce project data.

## Schema Creation

Created the `SHOPIFY_X` schema inside the `TEST` database to organize Shopify-related tables and database objects.

## Tables

Shopify data was stored in multiple tables within the `SHOPIFY_X` schema. These tables contain the data required for further analysis and reporting.

## Views

Created SQL views to provide reusable and simplified datasets for analytical queries.

## SQL Scripts

SQL scripts were used for data cleaning, exploratory analysis, customer metrics, RFM analysis, CLV analysis, retention and cohort analysis, and identification of at-risk customers.

## Screenshots

This folder contains screenshots showing the Snowflake database, schema, tables, views, and SQL query execution.
