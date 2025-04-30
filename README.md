# MS_Fabric_LAB_1
# Microsoft Fabric Lakehouse Creation Project

## Overview
This project demonstrates how to create and work with a **Lakehouse** using **Microsoft Fabric**. The steps in this exercise include setting up a workspace, creating a lakehouse, uploading a dataset, transforming the data into a managed table, running SQL queries, creating visual reports, and exploring the data through a semantic model.

The main goal of this exercise is to understand the Lakehouse architecture within Microsoft Fabric, blending the flexibility of data lakes with the query power of data warehouses.

## Project Steps

- **Create a Workspace:**  
  A new workspace was created in Microsoft Fabric with the appropriate licensing mode (Trial).

- **Create a Lakehouse:**  
  A new lakehouse was created within the workspace, providing a OneLake storage-backed environment for data files and tables.

- **Upload Data:**  
  The `sales.csv` dataset was downloaded and uploaded into a subfolder (`data`) inside the lakehouse.

- **Create a Table:**  
  The uploaded CSV file was loaded into a new table named `sales` using the Lakehouse explorer.

- **Explore Files and Shortcuts:**  
  Inspected the uploaded files and explored the shortcut creation features to reference external data without physically copying it.

- **Run SQL Queries:**  
  Used the automatically created SQL endpoint to query the `sales` table, performing aggregation to calculate total revenue per item.

- **Create a Visual Query:**  
  Built a visual query using drag-and-drop functionality, grouped sales data, and explored transformation capabilities.

- **Build a Report:**  
  Created a Power BI report with a **Clustered Bar Chart** visualization showing the quantity of items sold, using the sales table.

- **Save and Organize Resources:**  
  All created resources (lakehouse, SQL endpoint, semantic model, and report) were saved and validated within the workspace.

## Technologies Used
- Microsoft Fabric
- OneLake Storage
- Delta Lake Table Format
- SQL Analytics Endpoint
- Power BI (reporting inside Fabric)

## Screenshots
Screenshots documenting each step have been uploaded to this repository for reference.

## Requirements
- Microsoft Fabric Trial License
- Web Browser (Edge, Chrome, etc.)
- Basic knowledge of SQL and data analytics

## Additional Resources
- [Learn more about Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/)
- [Delta Lake Documentation](https://delta.io/)

---

**Project Completed by:** [Nejdet Yalcin]



---
