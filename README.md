# Maven Market 

## Problem Statement

This dashboard helps the store understand their customers better. 
The goal of this dashboard is to provide sales tracker in dynamically growing market. Insights through this dashboard can help company to track the company's Revenue and Sales.



### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in various columns of different tables there are values missing, datatype was not correct,headers need to be promoted.
- Step 5 : Appended the return data of two year(1997,1998) directly from folder.

![Screenshot 2024-05-10 142454](https://github.com/kavyaBaliyan/Sales-Insight-Dashboard/assets/169433785/9cd95166-4f10-4989-b2c5-e2be92bf76d8)

- Step 6 : In the model view, relations were created by finding appropriate primary and foreign key.All the relationships follow one-to-many cardinality. Only inactive relation is used for 'date' to 'stock date' of calendar and transaction_data tables.
- Step 7 : All the foreign keys need to be hidden for better visualisatin.

![Screenshot 2024-05-10 142242](https://github.com/kavyaBaliyan/Sales-Insight-Dashboard/assets/169433785/d8624981-6f0a-4abf-864c-d3c0c6c77e8d)


- Step 8 : In table view, created calculated measure 'Quantity Sold','Quantity returned','Total transaction','Total returns','Return Rate' to know about how come products are affected.
- Step 9 : A few more calculated measure were created like 'Total Revenue','Total Cost','Total Profit','Profit Margin','Revenue Target' to know how many store products are selling and whether the store is able to meet it's target.



![Screenshot 2024-05-10 142323](https://github.com/kavyaBaliyan/Sales-Insight-Dashboard/assets/169433785/0f56cfa8-aca8-49ae-9c16-928c28daa945)

- Step 10 : A matrix visual is used to get hands on everything in one go.
- Step 11 : Visual filters (Slicers) were added for store country and map was added for store city
- Step 12 : Three card visuals were added to the canvas, one representing current month Transaction, second is representing current month profit and last one is representing returns in current month.
- Step 13 : A bar chart was also added to the report to get better understanding of revenue per week and a donut chart to report the whether the revenue target is achieved or not. 

 # Report Snapshot (Power BI DESKTOP)

![Screenshot 2024-05-10 142356](https://github.com/kavyaBaliyan/Sales-Insight-Dashboard/assets/169433785/7f4a8707-2da9-4b2e-9127-51234977b671)

# Insights

A single page report was created on Power BI DESKTOP.

Following inferences can be drawn from the dashboard;
- In Canada and USA, store is unable to achieve targeted profit(Achieved-Canada-$5798, USA-$36909) and targeted transaction(Canada-$1459, USA-$9516) in compare to last month
- On the other hand, in Mexico targeted profit and transaction ia achieved but return rate is very high compared to last month(198)
![Screenshot 2024-05-10 142410](https://github.com/kavyaBaliyan/Sales-Insight-Dashboard/assets/169433785/8736ba2d-b915-451d-8fad-ec4859c3eb9b)
 
