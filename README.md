# 📊 Project Title: Power BI Data Cleaning and Preparation Using Power Query

This project focuses on cleaning, transforming, and preparing raw business data using Power Query in Power BI for better analysis and reporting.

## 📑 Table of Contents

* "Project Overview" (#-project-overview)
* "Data Sources & Architecture" (#-data-sources--architecture)
* "Data Transformation ETL" (#-data-transformation-etl)
* "Data Model DAX" (#-data-model--dax)
* "Dashboard Features" (#-dashboard-features)
* "Key Insights" (#-key-insights)
* "How To Use" (#-how-to-use)

---

## 🎯 Project Overview

Business Problem

Raw datasets often contain duplicate records, missing values, and inconsistent formatting, making analysis difficult in Power BI.

##  Objective

The objective of this project is to clean and prepare datasets using Power Query in Power BI to make the data ready for reporting and business analysis.

### Target Audience

- Data Analysts
- Business Analysts
- Students learning Power BI
- Reporting Teams



## 🗃️ Data Sources & Architecture

### Source Systems

The project uses local CSV files:

- List of Orders.csv
- Order Details.csv
- Sales Target.csv

### Data Volume

- List of Orders: First 500 rows used
- Order Details: Transaction-level sales data
- Sales Target: Monthly target data

### Storage Mode

Import Mode was used in Power BI.



## ⚙️ Data Transformation (ETL)

## Tool Used

Power Query Editor

##
Key Cleanups

The following transformations were applied:

- Imported datasets into Power BI
- Limited rows using Keep Top Rows
- Changed data types (Order Date → Date, Amount & Target → Fixed Decimal Number)
- Formatted Customer Name using Proper Case
- Merged City + State to create Location column
- Created Profit Margin custom column
- Added Profit Status conditional column
- Merged tables using Order ID
- Checked missing and duplicate values
- Applied sorting and filtering
- Performed grouping and aggregation



## 🧠 Data Model & DAX

### Model Type

Basic relational model using table relationships.

### Fact Tables

- Order Details
- Orders Data

### Dimension Tables

- List of Orders
- Sales Target

### Relationships Created

- List of Orders ↔ Order Details using Order ID
- Order Details ↔ Sales Target using Category



## 🖥️ Dashboard Features

Data Preparation Features

- Data import and transformation
- Row limiting and data type management
- Text formatting and column creation
- Conditional columns for profit classification
- Data merging and cleaning
- Sorting and filtering
- Grouping and aggregation
- Relationship management

## Design Theme

Simple and clean Power BI data preparation workflow.



## 💡 Key Insights

## Trend A

Customer order and sales data were successfully combined for better analysis.

## Trend B

Profit performance was categorized into Loss, Break-Even, and Profit using conditional columns.

## Recommendation

Proper data cleaning should always be completed before dashboard creation to improve accuracy and reporting quality.



# 🚀 How To Use

1. Install Power BI Desktop.
2. Open the Power BI project file.
3. Import the datasets (List of Orders, Order Details, Sales Target).
4. Open Transform Data in Power Query Editor.
5. Apply the cleaning and transformation steps.
6. Create relationships using Manage Relationships.


