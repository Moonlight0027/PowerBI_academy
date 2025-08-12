## Lesson 2  

**Notes before doing the tasks:**
**Scoring is based on the correct output.**
**One correct solution is sufficient.**

**Topic:** Importing Data into Power BI  
**Prerequisites:** Download Sales_Data.csv file  

1. List three data sources Power BI can connect to.  
2. What is the first step to import data into Power BI Desktop?  
3. How do you refresh imported data in Power BI?  
4. What file formats can Power BI import directly? (Name two.)  
5. What does the "Navigator" window show after selecting a data source?
6. What is the difference between "Load" and "Transform Data" in the import dialog? 
7. What is Power Query Editor? How to open it and why we use it?
8. Import Sales_Data.csv and load only the "Product" and "Price" columns using Power Query Editor.
9. Why might you see an error when connecting to a SQL database? (Name one reason.)  
10. How would you change OrderDate to a date format during import?  
11. How do you replace a data source after importing it?
12. Why might you see an error when connecting to a SQL database? (Name one reason.)  
13. How do you replace a data source after importing it?  
14. What is the difference between "transpose table" and "pivot table"   
15. What is the purpose of the "Applied Steps" pane in Power Query?
16. What is the difference between duplicate query and reference query?
17. Remove all rows where Quantity is less than 2.
18. Split the OrderDate column into separate "Year," "Month," and "Day" columns.
19. Replace all "Mouse" entries in the Product column with "Computer Mouse."
20. Create a conditional column: Label orders as "High Value" if Price > 100.
21. Group the table by CustID to show total spending per customer.

```Sales_Data```
| OrderID | Product  | Quantity | Price | OrderDate |
|---------|----------|----------|-------|-----------|
| 1001    | Laptop   | 2        | 1200  | 1/5/2023  |
| 1002    | Mouse    | 5        | 25    | 2/5/2023  |
| 1003    | Keyboard | 1        | 80    | 2/5/2023  |
| 1004    | Monitor  | 1        | 300   | 3/5/2023  |
| 1005    | Laptop   | 1        | 1200  | 3/5/2023  |
