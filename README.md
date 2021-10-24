# Sales-Insights-Tableau-Dashboard

# Project Statement

A Delhi-based computer hardware manufacturing company AltiQ is facing challenges in dynamically changing market. Head Sales director of the company dwants to identify where the business is failing. So you have been appointed by the sales director yo build an interactive dashboard that provides business insight to perform data driven-decision to maximize company profit. So, it is required to analyze the sales data of the company from each and every aspect and make it visible for ease of decision making by getting answers of some questions like which market, in which year, which customer, what type of product,how much sales quantity, revenue and profit.

## Approach

### Business Understanding

Before venturing into the project, the AIMS grid was used for planning and laying the foundation for successful implementation.

<p align="center">
<img src="https://raw.githubusercontent.com/rppradhan08/sales-insight/master/images/aims_grid.PNG">
</p>

### Data Engineering Cycle

Once the foundations where laid, the entire pipeline for dataflow was finalized ([read more](https://www.altexsoft.com/blog/datascience/what-is-data-engineering-explaining-data-pipeline-data-warehouse-and-data-engineer-role/)).

<p align="center">
<img src="https://raw.githubusercontent.com/rppradhan08/sales-insight/master/images/Data Lifecycle.png">
</p>

Usually, in such scenarios data from the data source such as OLTP are transformed using the ETL process before it gets loaded to a Data Warehouse, which is then connected to a BI tool to carry out the analysis.

For our case study, we have used a Tableau for data analysis that has a live connection with a MySQL data source.

<p align="center">
<img src="https://raw.githubusercontent.com/rppradhan08/sales-insight/master/images/Sales_schema Chart.PNG"><br>Fig:Database Schema
</p>

### Analyzing data using MySQL

<p align="center">
<img src="https://raw.githubusercontent.com/rppradhan08/sales-insight/master/images/SQL%20Analysis.PNG"><br>Fig: SQL Analysis
</p>

### Creating Visualization using Tableau

<p align="center">
<img src="https://raw.githubusercontent.com/rppradhan08/sales-insight/master/images/dashboard_snap.PNG">
</p>
