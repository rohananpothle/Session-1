# Session-1
Power Bi basics

# Power-Bi-Session-1


# What is Power BI?

**Power BI is a business analytics and data visualization platform developed by Microsoft that enables users to connect to multiple data sources, transform raw data, and create interactive dashboards and reports.**

# **Difference between Excel and Power Bi?**


  | Feature                      | **Excel**                                                      | **Power BI**                                                                           |
  | ---------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
  | **Purpose**                  | Primarily used for **data entry, analysis, and calculations**. | Designed for **data visualization, reporting, and business intelligence**.             |
  | **Data Handling Capacity**   | Handles **limited data** (slow with very large datasets).      | Handles **millions of rows efficiently** using Power Query and Data Model (DAX).       |
  | **Visualization**            | Basic charts and pivot tables.                                 | **Interactive, dynamic dashboards** with advanced visuals (maps, KPIs, slicers, etc.). |
  | **Automation & Updates**     | Manual refresh; formulas must be updated.                      | **Automatic refresh** from live or scheduled data sources.                             |
  | **Collaboration**            | Shared via files (email, OneDrive, etc.).                      | Shared via **Power BI Service (cloud)** with role-based access and real-time updates.  |
  | **Data Connectivity**        | Connects mainly to local files or limited databases.           | Connects to **hundreds of sources** (SQL, Azure, APIs, web, etc.).                     |
  | **Modeling & Relationships** | Limited relationship modeling.                                 | Built-in **data modeling** using relationships, DAX, and Power Query.                  |
  | **Use Case**                 | Best for **individual analysis** or small datasets.            | Best for **enterprise-level analytics** and **interactive reporting**.                 |


# What is DAX?

  1. DAX stands for Data Analysis Expressions.
  2. It’s a formula language used in Power BI to create custom calculations and measures — similar to Excel formulas but much more powerful.
  3. DAX helps us perform calculations like totals, averages, year-to-date values, and comparisons between data.
  4. In short, DAX is what makes Power BI dynamic and analytical.

# Intoaduction:

1. BI tool that is used in data analytics domain for data visualization purpose.
2. It is cloud-based business analysis and intelligence service by Microsoft. It is a collection of business intelligence and data visualization tools such as software services, apps and data connectors.
3. User-friendly tool offering drag-drop functionalities to generate the report and dashboard.

# Platforms

1. Power BI Desktop : For creating and designing reports and data models.
2. Power BI Service : For publishing, sharing, and collaborating on Power BI reports. (SaaS i.e., software as a service) need to login cloud.
3. Power BI Mobile : For viewing dashboards and reports on smartphones and tablets. (IOS, Android)
4. Power BI Gateway : Power BI service is cloud-based, and your data might be stored locally (on-premises) — Power BI can’t directly reach that local data due to security firewalls. So, the Gateway helps establish a secure tunnel between the two.

# Flow chart:

Data Sources → Power Query → Data Model → Visualization → Publishing → Consumption

  <img width="591" height="186" alt="Architecture" src="https://github.com/user-attachments/assets/c7479a84-a210-48bd-b30e-b473a4d4cbd7" />


# Power BI Pricing:

| **Version**                              | **Description**                                             | **Limitations**                                                           |
| ---------------------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------------------- |
| **Power BI Desktop (Free)**              | Free tool to build reports locally using Power Query & DAX. | No sharing/collaboration; limited to local `.pbix` files.                 |
| **Power BI Pro**                         | For sharing & collaboration across users in the cloud.      | Requires license for each user; limited dataset (1 GB) & 8 refreshes/day. |
| **Power BI Premium (Per User/Capacity)** | For large data, AI features, and enterprise sharing.        | Costly; mainly suited for big teams or org-wide deployment.               |


# Data connectivity ?

  1. Import Mode : Get Data → (Excel, SQL, CSV, Web, etc.)
  2. DirectQuery Mode : Get Data → SQL Server → Select DirectQuery → Load tables
  3. Live Connection : Get Data → Power BI Datasets/Analysis Services

| **Feature**                 | **Import Mode**                                                           | **DirectQuery Mode**                                             | **Live Connection**                                                                              |
| --------------------------- | ------------------------------------------------------------------------- | ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| **1️⃣ Data Storage**        | Data is **copied & stored** inside Power BI (.pbix file).                 | Data **stays in the source**; only queries are sent when needed. | Connects **directly to an existing model** (like SSAS/Power BI Dataset). No data stored locally. |
| **2️⃣ Performance**         | **Fastest** (data preloaded in memory).                                   | **Slower**, depends on database speed and network.               | **Depends** on the remote model’s performance.                                                   |
| **3️⃣ Data Refresh**        | Needs **manual or scheduled refresh** to update data.                     | **Always up-to-date** (real-time queries).                       | **Always live**, updates instantly from connected model.                                         |
| **4️⃣ Modeling Capability** | Full modeling—can create relationships, measures, and calculated columns. | Limited modeling—some DAX and transformations restricted.        | **No modeling allowed**—you use existing model as-is.                                            |



# Data Analysis:

  1. Collect data
  2. Data understand
  3. Cleaning
  4. Data modeling
  5. Visualization
  6. Dashboard

# Extensions:

1. .pbix - Packaged workbook
2. .pbit - Template/ Without Data

# Data Types:

1. Text - No symbol
2. Numeric - Summation symbol
3. Date - Calendar symbol


# Componentas of DESKTOP:

1. Report View
2. Table View
3. Model View
4. Power query

# Power Query:

# Data Cleaning & Transformation
1. Remove duplicates / blanks / nulls
2. Rename, remove, or reorder columns
3. Change data types (e.g., text → number)
4. Trim & clean text (remove spaces, unwanted characters)
5. Replace values or fill missing data (up/down)

# Data Enrichment

1. Add Custom Columns using formulas.
2. Conditional Columns (IF/ELSE logic).
3. Index Columns (create row numbers).
4. Extract values from text (first/last N characters).

# Data Type Conversion & Formatting

1. Convert between text, number, date, or time types.
2. Format date/time fields (Year, Month, Quarter).
3. Create new date columns (e.g., “Year-Month”).

# Refresh & Automation

1. All transformations are recorded as M code steps.
2. Automatically refresh data when the source updates.

# KPIs: To track one key metric
# Dashboard: A summary view containing multiple KPIs and visuals.

# Why dashboard important for the buisiness:
Data dashboards are vital for business for several reasons:
1. Data Accessibility
2. Efficiency
3. Goal Tracking
4. Informed Decision Making
5. Predictive Analysis
6. Reduce time spent building reports
7. Reduce human error.
