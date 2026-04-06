Power BI Data Transformation and Analysis
A comprehensive data visualization project that transforms raw, unorganized Excel data into an interactive business intelligence dashboard. This project demonstrates end-to-end data handling, from ETL (Extract, Transform, Load) processes to advanced DAX modeling.

Features
  - ETL Pipeline: Utilizes Power Query (M Language) to clean, pivot, and de-duplicate raw Excel records.
  - Data Modeling: Implemented a Star Schema to optimize query performance and establish clear relationships between dimension and fact tables.
  - Interactive Dashboards: Features dynamic filtering, drill-through actions, and custom tooltips for deep-dive analysis.
  - Advanced DAX: Includes custom measures for Key Performance Indicators (KPIs) such as Year-over-Year (YoY) growth and rolling averages.

Technical Implementation
1. Data Cleaning (Power Query)
  The raw data required significant preprocessing, including:
  - Type Conversion: Fixing date formats and currency locales.
  - Conditional Columns: Creating custom categories for segmented analysis.
  - Null Handling: Implementing logic to handle missing values without biasing the dataset.

2. The Data Model
  The report is built on a structured model to ensure data integrity:
  - One-to-Many Relationships: Connecting lookup tables (Products, Calendar) to transaction records.
  - Time Intelligence: A dedicated Date Table was generated to support complex temporal analysis.

Getting Started
Prerequisites:
  - Microsoft Power BI Desktop.
  - Access to the data/raw_data.xlsx file (linked as the data source).

View the Project
  1. Open the /reports folder.
  2. Launch the .pbix file.
  3. If the data source path is broken, go to Transform Data > Data Source Settings and point it to the local raw_data.xlsx.
