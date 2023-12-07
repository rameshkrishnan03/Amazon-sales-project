# Amazon Sales Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/e97da212-901b-49a6-aecf-ed549e839917/ReportSection?experience=power-bi

## Problem Statement

This dashboard helps the Amazon understand their customers and products better. It helps the amazon know if their customers are satisfied with their services. Through differnt rating, they get to know their improvement area, & thus they can improve their services by identifying these area. It also lets them know the profit and loss in Products, thus since by using this dashboard they have Identified this problem, they can further work on factors responsible for these Losses.





### Steps followed 

- Step 1  : Load data into Power BI Desktop,2 Dataset is a excel file.
First Dataset - order.
Second Dataset - return.

- Step 2  : Open in  power query editor & understand the data.

- Step 3  : Also Analyse the data throughly.

- Step 4  : It was observed that in none of the columns errors & empty values were present in data.

- Step 5  : For calculating sales and profit by years and name of the month put in separated column and done the expected Calculation. 

- Step 6  : In second dataset has returned product details and make tha calculation for count of returned products.
            second Dataset have return product id and customerid
            so use the conditional column  for calculate the total returned product
  # Total Returned = if [Column1] = "Yes" then 1 else 0).                                                    

- Step 7  : #Data Modelling 
                Connect the 2 Dataset in PowerBi
                Order dataset have orderid and Return Dataset have orderid make cardinality one to many.
                

- Step 8  : In PowerBi report view start the visualization for the Amazon Sales Dashboard.

- Step 7  : Since the data contains various profit for countries thus in order to represent data use a new visual was added using the map visualizations pane in report view and put Market column in Legend.


- Step 9  : Slicers were added in visualization put years in slicers it sliced "2012", "2013", "2014" & "2015".

- Step 10  : Four card visuals were added to the visuals, one representing Total sales , Total customers, Return Products and product Quantity.


- Step 10 : Using Pie chart and Donut chart for profit by category and profit by segment. 
#PIE CHART
       It is Used for showing the profit by category.
       It has 3 Category 1.Technolgy 2.Office supplies 3.Furniture
#DONUT CHART
       It is used for showing the profit by segment.
       It has 3 Segment 1.Consumer  2.Corporate 3.Home Office
       
          
- Step 11 : A bar chart was also added to the report design area representing the profit in sub-category in dashboard. While creating this visual, showing the bar in conditional formatting more profit it shows the bar in green colour medium it show in mixing of green and red it was loss bar colour is Red. 


- Step 12 : Using the line chart for showing the profits in monthwise.
#LINE CHART
In this chart X-axis contain Months and Y-axis contain Profit


- Step 13 : The report was then published to Power BI Service.
 
![Screenshot (32)](https://github.com/rameshkrishnan03/Amazon-sales-project/assets/70803627/6b3d537d-7a11-4005-816b-e396b738e991) 


# Snapshot of Dashboard (Power BI Service)

![amason-sales](https://github.com/rameshkrishnan03/Amazon-sales-project/assets/70803627/e28efdc6-c632-4e22-96b0-f8cfd4b1e718)

 

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

