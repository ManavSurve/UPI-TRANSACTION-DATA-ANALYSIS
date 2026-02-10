# UPI-TRANSACTION-DATA-ANALYSIS

### Dashboard Link : https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection

## Problem Statement

Despite the rapid growth of digital payments, businesses often struggle to monitor real-time transaction health and customer behavior across diverse regions. This project addresses the lack of a centralized system to track monthly balance fluctuations and transaction volumes across different cities (like Mumbai and Bangalore). By analyzing variables such as Merchant Name, Purpose, and Device Type, the dashboard aims to identify high-performing regions and under-utilized payment methods to drive better financial decision-making for the year 2024.


### Steps followed 

- Step 1 : Loading Data into Power BI Desktop
- Step 2 : Data Profiling.
- Step 3 : Size & Position of slicers.
- Step 4 : Formatting the Slicers.

  ![Image](https://github.com/user-attachments/assets/1bf44c56-dc59-4851-ae2d-351927b1c2ab)

  
- Step 5 : Adding a Page & Age Group Column

  for creating new column following DAX expression was written;

      Age Group = IF('UPI Transactios'[CustomerAge]<=25,"A1",IF('UPI Transactios'[CustomerAge]<=35,"A2","A3"))

  
- Step 6 : Adding a Bar Chart to Represent Balance by Month ( year 2024).

  ![Image](https://github.com/user-attachments/assets/c9b662e4-5d67-4bb1-82b7-81abc3c69cd9)

  
- Step 7 : Adding a Matrix Visual.

  ![Image](https://github.com/user-attachments/assets/ea7b57c2-33a7-4e1a-9b18-ae50ecfa8a6d)

   
- Step 8 : Syncing Slicers & Applying Conditional Formatting.

  ![Image](https://github.com/user-attachments/assets/bf2ef43d-a458-4916-a5f7-871f5dfbd734)

  
- Step 9 :Adding Bookmarks for Transactions.
           
           
- Step 10 : Adding Bookmarks for Remaining Balance. 

 
 # Report Snapshot (Power BI DESKTOP)

![Image](https://github.com/user-attachments/assets/469da71b-bf34-472a-8846-c3badac6ab48) 

 # Report Snapshot (Power BI DESKTOP)

![Image](https://github.com/user-attachments/assets/ca8a1cd3-d8c8-42d8-9899-c14dd3751adf)


 
