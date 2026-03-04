# SSAS Sales Analysis Cubes

This repository contains a Business Intelligence project developed using **SQL Server Analysis Services (SSAS)**.  
The project demonstrates the design and implementation of **three OLAP cubes** for sales analytics using a **star schema data model**.

---

## Technologies Used

- Microsoft SQL Server
- SQL Server Analysis Services (SSAS)
- Visual Studio
- Multidimensional Data Modeling

---

## Project Overview

The project focuses on building **multidimensional OLAP cubes** to support analytical queries and business reporting.

Three cubes were created to analyze sales data from different perspectives and demonstrate SSAS cube design.

---

## Data Model

The cubes are built using a **Star Schema** architecture.

### Fact Table
**FactSales**
- ProductID
- CustomerID
- SalesmanID
- ChannelID
- TimeID
- Qty
- TotalPrice

### Dimensions
- Product Dimension
- Customer Dimension
- Time Dimension
- Channel Dimension
- Salesman Dimension

---

## Cubes Implemented

- Sales.cube
- Sales1.cube
- Sales2.cube

Each cube supports multidimensional analysis using measures, dimensions, and hierarchies.

---

## Features

- OLAP cube design using SSAS
- Star schema data model
- Measures for sales analytics
- Dimension relationships
- Time hierarchy for Year and Quarter analysis

---

## Author

Moaz Achraf Sophy  
Junior BI Developer | Data Analyst