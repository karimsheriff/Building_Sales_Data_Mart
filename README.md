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
<div>
  <img src = "https://github.com/karimsheriff/Sales_Data_Mart/blob/main/Snapshots/Data_Model.png">
</div>
<br>
Then, I used SSIS to create Fact table and the dimention packages separately for:<br>
<ul>
  <li>Integrating the data from data source.</li>
  <li>Transforming and processing data.</li>
  <li>And then load data after applying the transformation, and apply full and slow-changing dimension (SCD) loading.</li>
</ul>

# Fact_Sales
<div>
  <img src = "https://github.com/karimsheriff/Sales_Data_Mart/blob/main/Snapshots/Fact_Sales1.png">
  <img src = "https://github.com/karimsheriff/Sales_Data_Mart/blob/main/Snapshots/Fact_Sales2.png">
</div>

## Fact Data
<div>
<img src = "https://github.com/karimsheriff/Sales_Data_Mart/blob/main/Snapshots/Fact_Result.png">
</div>

# Dim_Product
<div>
  <img src = "https://github.com/karimsheriff/Sales_Data_Mart/blob/main/Snapshots/Product_Dim1.png">
  <img src = "https://github.com/karimsheriff/Sales_Data_Mart/blob/main/Snapshots/Product_Dim2.png">
</div>

## Dim_Product Data
<div>
<img src = "https://github.com/karimsheriff/Sales_Data_Mart/blob/main/Snapshots/Product_Result.png">
</div>

# Dim_Customer
<div>
  <img src = "https://github.com/karimsheriff/Sales_Data_Mart/blob/main/Snapshots/Customer_Dim1.png"> 
</div>

## Dim_Customer Data
<div>
<img src = "https://github.com/karimsheriff/Sales_Data_Mart/blob/main/Snapshots/Customer_Result.png">
</div>

# Dim_Territory
<div>
  <img src = "https://github.com/karimsheriff/Sales_Data_Mart/blob/main/Snapshots/Territory_Dim.png">
</div>

## Dim_Territory Data
<div>
 <img src = "https://github.com/karimsheriff/Sales_Data_Mart/blob/main/Snapshots/Territory_Result.png">
</div>

# Dim_Date
<div>
  <img src = "https://github.com/karimsheriff/Sales_Data_Mart/blob/main/Snapshots/Date_Dim.png">
</div>

## Dim_Date Data
<div>
 <img src = "https://github.com/karimsheriff/Sales_Data_Mart/blob/main/Snapshots/Date_Result.png">
</div>











