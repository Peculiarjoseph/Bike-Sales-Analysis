# Bike Sales Analysis
![240_F_361080070_9XQOrqHLvEwL8789XAqVEFpuLADGYyRX](https://github.com/user-attachments/assets/6e395ac4-4728-4367-b179-597c18be2b09)

# Role: Data Analyst
<img width="2188" height="877" alt="Beyond-Theory-Data-Analysis-Landing-Page-graphic" src="https://github.com/user-attachments/assets/3805adcf-814f-4eb6-8761-ae5ea6cea4da" />


## Task🗒️: We need your expertise to develop a dashboard for “Hermes Bike Share” that displays our key performance metrics for informed decision-making.

-------------------------------------------------------------------------------------------------------------------------------------------------------

## Requirements:
### •	Hourly Revenue Analysis.
### •	Profit and Revenue Trends.
### •	Seasonal Revenue.
### •	Rider Demographics.
### Design and  Aesthetics: Use our company colours and ensure the dashboard is easy to navigate. 
### Data Source: Access to our databases will be provided. If no database, please create one.
### Deadline: We need a preliminary version ASAP.
### Please provide an estimated timeline for completion and recommendation on raising prices next year.
---------------------------------------------------------------------------------------------------
# Project Documentation📝:
### For the task assigned, I’ve been provided with three datasets in a CSV format :
### Bike_share_yr_0 : This contains records of transactions made by Hermes Bike Share for the year 2021.
### Bike_share_yr_1 : This contains records of transactions made by Hermes Bike Share for the year 2022.
### Cost_table : This consists of unique records of years, price and cost of goods(COG).

## Tools Used : SQL and Power BI 

------------------------------------------------------------------------------------------------------
 ## SQL <img width="75" height="70" alt="sql-server" src="https://github.com/user-attachments/assets/e6a859ab-2521-4bad-9f25-e534bd2e6453" />


 ### Using Microsoft SQL Server, I created a database named ‘Bike_Data ’ for the CSV datasets. 
 <img width="1359" height="720" alt="DB1" src="https://github.com/user-attachments/assets/052b5e51-c5a6-4e6f-895d-da89d21ef042" />

 -------------------------------------------------------------------------------------------------------
 ### Next, I imported the data using “Import flat file.”
 <img width="1363" height="717" alt="DB2" src="https://github.com/user-attachments/assets/86bae36d-9bb4-4366-97a3-df7cbf8efd37" />

 -------------------------------------------------------------------------------------------------------
 ### After importing the three datasets, I retrieved the tables.
 <img width="1365" height="694" alt="DB3" src="https://github.com/user-attachments/assets/29388c69-c54b-44e9-ae32-9f93f0ea0268" />

 --------------------------------------------------------------------------------------------------------
 ### Using the ‘Count’ aggregate function, I got the number of records on each table.
 <img width="1363" height="714" alt="DB4" src="https://github.com/user-attachments/assets/fce9ec06-3d7b-42b6-8818-57401cfb0ac8" />

 ----------------------------------------------------------------------------------------------------------
 ### Since  bike_share_year_0 table and bike_share_year_0 table are both transactional data with matching columns, but for different years I used UNION to append them as one.
 <img width="1362" height="716" alt="DB5" src="https://github.com/user-attachments/assets/8fd83e22-f2b5-4e70-8b11-2c0081797309" />

 ---------------------------------------------------------------------------------------------------------
 ### Using CTEs and LEFT JOIN I brought in the columns from cost table to my appended bike transactions table. 
 <img width="1352" height="660" alt="DB6" src="https://github.com/user-attachments/assets/1145d584-9248-42aa-8274-1115a10fcba4" />

------------------------------------------------------------------------------------------------------------
## Power BI <img width="70" height="70" alt="Power-BI" src="https://github.com/user-attachments/assets/007d81bd-730c-469c-a87f-eb76d323b0cf" />
### Next, I open Power BI and connect with the Database using “DirectQuery” for the purpose of a dynamic dashboard. Anytime the database is updated with new transactions, the Power BI dashboard will reflect them.
<img width="1362" height="711" alt="DB7" src="https://github.com/user-attachments/assets/fa050e52-2395-4e8e-93a0-ec63fcc9783a" />
 
