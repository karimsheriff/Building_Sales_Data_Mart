# Sales_Data_Mart
## Project Description:
This project focuses on designing and implementing a data mart leveraging the capabilities of SSIS (SQL Server Integration Services) and SQL Server.
A data mart serves as a purpose-built subset of a data warehouse, tailored to meet the specific analytical requirements of a particular department, team,or business unit within an organization.It is structured around a dimensional model,typically utilizing star schemas consisting of dimension tables describing various attributes and a central fact table containing numerical measures.

### Key Project Tasks:
<ul>
<li>Data Extraction from AdventureWorks2022 (OLTP):</li>
Extracting data from the AdventureWorks2022 database to serve as the primary data source for the data mart.<br>
<li>Data Cleansing and Preprocessing:</li>
Ensuring data quality by cleansing and preprocessing extracted data to eliminate inconsistencies and inaccuracies.<br>
<li>Design of the Star Schema:</li>
Designing the dimensional model, including the star schema, to serve as the foundation of the data mart,This involves identifying key dimensions and measures relevant to sales analysis.
<li>Development of ETL Processes:</li>
Developing ETL (Extract, Transform, Load) processes using SSIS or other ETL tools to facilitate the movement of data from the source system to the data mart.
</ul><br>
### Steps With Snapshots:
First, I used SQL server to design the data warehouse structure, employing star schema.<br>
<ul>
  <li> Fact Table : Sales</li>
<li> Dimentions : Customer , Product , Territory , Date</li>
</ul><br>














