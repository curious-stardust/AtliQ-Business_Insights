# AtliQ-Business_Insights
The primary objective of the dashboard is to provide in-depth insights into key areas such as Finance, Marketing, Sales, and Supply Chain, enabling data-driven decision-making across various business sectors.

# Overview: 

AtliQ Hardwares is an end to end computer Hardware and Peripheral Manufacturer. With a rapidly growing presence in the electronic goods sector over the past few years, AtliQ has expanded its operations worldwide. The company distributes its products through three primary channels: direct sales, retailers, and distributors, ensuring a wide reach across diverse markets.

# Problem statement:

AtliQ Hardwares is facing challenges in the LATAM region due to the lack of effective data analytics. Currently, the company relies on Excel files, surveys, and intuition for analysis, which, while traditional, fall short in today’s market environment. To make better-informed decisions and stay competitive, establishing a dedicated analytics team has become crucial for AtliQ Hardwares.

This dashboard is a complete view on the Business data from 2019-2022.

# Key Skills

**Key life skills I gained from the course:**

* Developing a problem-solving mindset
* Learning to independently find solutions using free resources
* Seeking hints and tips rather than exact answers
* Breaking down complex questions into simpler parts for better understanding
* Strengthening my grasp of the fundamentals

**Soft skills I gained from the course:**
* Asking meaningful and relevant questions
* Delivering engaging presentations during project meetings
* Communicating effectively with stakeholders

**Project Management Knowledge Gained:**
* Gaining insight into the structure and purpose of project meetings
* Understanding the problem statement and the project kick-off process
* Key components of a project charter
* Conducting stakeholder analysis and mapping
* Understanding User Acceptance Testing (UAT)

**Tools and Technical Knowledge Gained:**
* Data extraction and cleanup using MySQL (introduction to SQL databases)
* Installation and setup of Power BI Desktop
* Data modeling (Star and Snowflake schemas)
* Data transformation using Power Query
* Creating calculated columns and DAX measures
* Selecting appropriate visuals based on data requirements
* Verifying data accuracy in Power BI and Excel
* Implementing conditional formatting to highlight data anomalies
* Designing KPI indicators
* Using bookmarks to switch between visuals
* Applying functions like CALCULATE, DIVIDE, SWITCH, FILTER, and more
* Creating tooltips to display trends
* Setting up personal gateways for auto-refresh
* Dashboard design principles and color coding for reports
* Optimization and file size reduction using DAX Studio

# Domain knowledge:

**Fiscal year** - 12-month Financial year of a company that need not be the same as calendar year,  it is used to track the expenses and finances of the company and is a specific time frame for budgeting, planning and reporting financial activities
 
**YTD and YTG** - Year to date is from the start of FY until is the current date and Year to go is the next day from the current date until the end of that FY.

**OLTP (online transaction processing)**

**OLAP (online analytical processing)**

**ETL (extract transform load)**

**Data Catalogue**

**Data Warehouse**

**Gross price** - Total price of the product before any deductions or discounts

**Gross Margin** - percentage of revenue a company keeps after deducting the cost of goods sold (COGS)

**Net sales** - net revenue gained by a company from selling its products

**Net Profit** - Money left with the company after subtracting all expenses like COGS, tax, operational expenses and other miscellaneous expenses from its total revenue generated.

**Pre/Post-invoice deductions**- Deductions done for a customer before or after the final bill is generated, usually as a discount for bulk orders or any return of damaged products etc.

**Net invoice sales** - actual amount payed by the customer while buying the products

**Cost of goods sold (COGS)** - Refers to the total cost involved in producing the goods, this includes Manufacturing cost, freight cost and other costs 

**Operational expenses** - Expenses that include rent of office spaces, electricity bill, employee salaries,  repairs and maintenance along with marketing and advertisements

**Inventory Management** - Keeping track of the amount of products available, out-of stock and excess products. It also includes prevention of over-stocking or under-stocked and maintenance of the stored products properly

**Forecast Accuracy** - Prediction of sales, product demand and cost performance of the company in future. In a scale of 0 to 1 if the forecast accuracy is greater than 0.7, then the company’s forecast is considered accurate

**Absolute net error** - Absolute (positive) error value difference between forecasted value and actual value

# Dataset details

There are two types of datasets in the data model: Dimension tables and Fact Tables

|Dimension Table|Fact Table|
| --- | --- |
| contain Raw descriptive data such as product details, customer information, region, category etc, that help structure the data into understandable format | hold quantitative data such as sales or revenue etc, used to analyse the business trends over a period of time |
| Remain stable as changes are less frequent | Updated frequently based on new changes or transactions or events |
| Used to categorise or filter the data in fact tables | Aggregated to analyse trends |
| Dimension tables surround the fact table, providing attributes (details) for filtering, grouping and analysing the data in Fact tables | Fact Tables are usually at the centre of a data model where a foreign key links to multiple dimension tables |

# Data Modelling

Data modelling is the process of organising and structuring data so that it can be stored in a database and easily retrieved for analysis. It helps define how different pieces of data relate to one another and how they are grouped together. It can be defined as creating a blue print of how data is stored.
There are two ways of organising the data called as star schema and snowflake schema
Star schema has the fact table in the centre surrounded by dimension tables resembling a star, hence the name.
Snowflake schema is a extension of star schema where the dimension tables are further broken down into more tables connected to it and in-turn the dimension tables are connected to fact tables.

# Project outcome

This dashboard provides key insights into AtliQ Hardware’s overall performance from FY 2019 - 2022 by transforming raw data into meaningful visuals and analytics to make better strategic decisions. The following outcomes were achieved:

**Channel Performance:** It allows stakeholders to compare the effectiveness of various sales channels and see where they can focus their efforts to drive higher revenue

**Data-Driven Insights:** By switching from manual data methods to real-time analytics, the dashboard enables more informed decision-making and trend forecasting especially in the LATAM market

**Visualisations:** With clear and interactive visuals, the dashboard simplifies complex data, making it easier for the team to monitor key performance indicators (KPIs) and track overall business health.
