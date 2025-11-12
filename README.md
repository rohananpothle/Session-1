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

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Visualizations:

# Slicers, Timeline and KPIs:

  1. Add slicers and timelines to the dashboard. Connect them with all neccessary charts to make them dynamic. Slicers can be used as filters to dashboard.
  2. To filter according to the dates, months or years timelines can be added to the dashborad.
  3. KPI cards are specific, measurable values that indicates how effectively a company is achieving its key business onjectives and goals.

# Formatting:

  1. Add colors, changes font size, background color, etc to make dashboard more appealing and easy to understand.

# Charts

1. Bar chart: Compare categorical data horizontally (e.g., sales by product).
2. Clustur chart: Compare multiple measures side-by-side across categories.
3. Line chart: Show data trends or changes over time (continuous data).
4. Area Chart: Display trends over time with filled color emphasizing volume.
5. Stacked area chart : Show part-to-whole contribution over time.
6. 100 % stacked chart : Compare percentage contribution of categories across a whole.
7. Line stacked chart : Combine trends (line) and totals (columns).
8. Line cluster chart : Compare grouped columns with a line trend.
9. Ribbon chart : Visualize ranking changes across categories over time.
10. Water fall chart : Show how values increase or decrease sequentially to a final total.
11. Funner chart : Represent stages in a process (e.g., sales pipeline).
12. Scatter chart : Show relationship or correlation between two numeric variables.
13. Pie chart : Display proportion or percentage contribution of categories.
14. Donut chart : Like a pie chart but with a central space for total or label.
15. Treemap : Show hierarchical data as nested rectangles sized by value.
16. MAP : Plot geographic data points using latitude and longitude or country names.
17. Filled MAP : Color entire regions or areas to represent intensity (choropleth).
18. Gauge : Display progress toward a single target (e.g., KPI goal).
19. Card : Show a single numeric value clearly (e.g., total sales).
20. Multi-Card : Display multiple key metrics side-by-side.
21. KPI : Highlight goal achievement by showing current value vs. target trend.
22. Table : Display detailed data with rows and columns for precise comparison.

# Visual Type: Gauge Chart
Purpose: To compare your current performance (YTD) against a target — for example, previous year’s revenue or a goal value.

<img width="643" height="448" alt="image" src="https://github.com/user-attachments/assets/7d87ccf1-0567-4e4a-ac1f-903c1c419ce7" />
<img width="223" height="521" alt="image" src="https://github.com/user-attachments/assets/49522236-8641-4c2a-9e13-714995ea8c10" />


| Element                  | Meaning                                                              | Example in Your Visual                                          |
| ------------------------ | -------------------------------------------------------------------- | --------------------------------------------------------------- |
| **Main Number (Center)** | The **current value** — typically *Sales YTD*.                       | `36.26M` → current year’s YTD revenue                           |
| **Blue Arc**             | Portion of the gauge filled — it shows **progress toward target**.   | The blue part represents how much of your goal you’ve achieved. |
| **Grey/White Arc**       | Remaining part to reach your **target**.                             | Still-to-achieve part of the previous year’s YTD or set target. |
| **Left Label (0.00M)**   | The **minimum value**, often 0 or a baseline.                        |                                                                 |
| **Right Label (72.52M)** | The **maximum value**, typically your **target or last year’s YTD**. |                                                                 |
| **Title**                | Describes what the visual represents.                                | “Sales YTD and Previous Year Revenue”                           |



DAX:

1. HD_Rate_By_Asthma = 
    VAR TotalAsthma = CALCULATE(COUNTROWS(Heart_disease),ALLSELECTED(Heart_disease),Heart_disease[Asthma]="Yes")
    VAR HeartDiseaseDueAsthma = CALCULATE(COUNTROWS(Heart_disease),ALLSELECTED(Heart_disease),Heart_disease[Asthma]="Yes",Heart_disease[HeartDisease]="Yes")
    RETURN
    IF(
        TotalAsthma > 0,
        DIVIDE(HeartDiseaseDueAsthma,TotalAsthma)*100,
        BLANK()
    )

2. HD_Rate_By_Diabet = 
    VAR TotalDiabetic = CALCULATE(COUNTROWS(Heart_disease),ALLSELECTED(Heart_disease),Heart_disease[Diabetic]="Yes")
    VAR DiabeticHeartDisease = CALCULATE(COUNTROWS(Heart_disease),ALLSELECTED(Heart_disease),Heart_disease[Diabetic]="Yes",Heart_disease[HeartDisease]="Yes")
    RETURN
    IF(
        TotalDiabetic > 0,
        DIVIDE(DiabeticHeartDisease,TotalDiabetic)*100,
        BLANK()
    )

3. HD_Rate_By_KidneyDisease = 
    VAR TotalKidneyDisease = CALCULATE(COUNTROWS(Heart_disease),ALLSELECTED(Heart_disease),Heart_disease[KidneyDisease]="Yes")
    VAR HeartDiseaseDueKidneyDisease = CALCULATE(COUNTROWS(Heart_disease),ALLSELECTED(Heart_disease),Heart_disease[KidneyDisease]="Yes",Heart_disease[HeartDisease]="Yes")
    RETURN
    IF(
        TotalKidneyDisease > 0,
        DIVIDE(HeartDiseaseDueKidneyDisease,TotalKidneyDisease)*100,
        BLANK()
    )

4. HD_Rate_By_SkinCancer = 
    VAR TotalSkinCancer = CALCULATE(COUNTROWS(Heart_disease),ALLSELECTED(Heart_disease),Heart_disease[SkinCancer]="Yes")
    VAR HeartDiseaseDueSkinCancer = CALCULATE(COUNTROWS(Heart_disease),ALLSELECTED(Heart_disease),Heart_disease[SkinCancer]="Yes",Heart_disease[HeartDisease]="Yes")
    RETURN
    IF(
        TotalSkinCancer > 0,
        DIVIDE(HeartDiseaseDueSkinCancer,TotalSkinCancer)*100,
        BLANK()
    )

5. HD_Rate_By_Stroke = 
    VAR TotalStroke = CALCULATE(COUNTROWS(Heart_disease),ALLSELECTED(Heart_disease),Heart_disease[Stroke]="Yes")
    VAR StrokeHeartDisease = CALCULATE(COUNTROWS(Heart_disease),ALLSELECTED(Heart_disease),Heart_disease[Stroke]="Yes",Heart_disease[HeartDisease]="Yes")
    RETURN
    IF(
        TotalStroke > 0,
        DIVIDE(StrokeHeartDisease,TotalStroke)*100,
        BLANK()
    )

6. Heart_Disease_Rate = 
    VAR Total_pop = COUNTROWS(Heart_disease)
    VAR Heart_diseased_pop = CALCULATE(COUNTROWS(Heart_disease), Heart_disease[HeartDisease] = "Yes")
    RETURN
    IF(
      Total_pop > 0,
      DIVIDE(Heart_diseased_pop, Total_pop) * 100,
     BLANK()
    )
   
8. Count_population = COUNTROWS(Heart_disease)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Session - 3:

1. What is Dashboard?
2. What is KPI?
3. Difference between KPI and Dashboard.
4. What is tool tip.
5. Row level security (RLS)?
6. Deploying or Publishing the dashboard?
