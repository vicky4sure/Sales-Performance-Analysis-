# Sales-Performance-Analysis-
Project work
Sales Performance Analysis for a Retail Store
#

[Project overview](#project-overview)

Data sources

Tools used

Data cleaning and preparation

Exploratory data analysis

[Data analysis](#data-analysis)

Data visualization

### Project overview
The aim of this project is to analyze the sales performance of a retail store by exploring key metrics such as top-selling products,
regional sales performance and monthly sales trends. Through this analysis, insight will be provided that will support business decisions.

The project wills shows the revenue generated between the year 2023 and 2024 and compares the quantity of items sold between the said years. At the end of the analysis, the plotted charts coupled with illustrated tables shows that  the highest revenue was gotten in the year 2023 with the sum of 1,105,330 as compare to the year 2024 with the sum 995,760 on pivot table. The quantity sold in the year 2023 generated the highest revenue with the highest quantity of 38,681 as compare to 29,780 quantity sold in 2024 which might be as a result lesser trading period in the year 2024.  


### Data sources
The dataset used for this analysis was provided by incubator Hub, an educational technology organization. The data includes sales records from a retail store for a learning purpose.
---
### Tools used
1. Microsoft Excel [Download Here](https://microsoft.com)
-  for data cleaning and preparation.
- utilized excel formulars to calculate keys metrics such as Average (AVG) and total sales, total revenue by region.
-   Created data visualizations using pivot table and charts to identify trends and insights.
  
 2. SQL -Structured Query Language of data
   - for quering the dataset to retrieve the total sales for each product category.
   - to calculate the highest selling product by total sales value.
   - To calculate the top 5 customers by total purchase amount.
   - 
  3. POWERBI -Power Business Intelligence
     - to create a dashboard that will visualizes the insight to all the work done on excel and sql.
     - to visualizes the sales overview, top performing product and sum of revenue by regional breakdown.
       
4.   Github for portfolio building
---
### Data cleaning and preparation
In the initial phase of the data cleaning and preparation,we perform the following action;
1.  Microsoft Excel:
- data loading and inspection of the entire dataset
- Highlight the entire table to remove duplicates
- Cleaned data is ready to perform key metrics, prepare pivot tables and charts like pie chart, bars, column charts that will aids decision making.
  
2.  SQL; Stuctured Query Language:
     - imported data from excel by creating a new database in SQL Server under LITA_DB
     - Used SQL Commands to remove excess columns and rows directly
     - Write queries on the data set provided to determine the total revenue per product and to determine the percentage of total sales contributed by
       each region that will help the retail store in their business decison making.
       
3.  POWERBI ;Power Business Intelligence:
    - Loaded a cleaned data via Get data option on Home Menu and entered Power Query Editor; to transform the data
    - Examined the data column quality, column profile and column distibution to check for error, empty, uniqueness and distinct of the data
    - Visual the data by creating dashboard to make use of tables, cards, matrix, slicers/filter and column, bar and pie chart etc. to determine the total revenue by region,
      sum of quantity sold by product, sum of revenue by product to help in providing insight on how the retail store has made progress over the years, through DAX Function using report view.
      To beautify the dashboard/report through the use of format tool (pencil icon) to make use of different size and style, padding, call out value, title, font size, colour, slicer etc. 
      
   ### Exploratory data analysis
   EDA involved the exploring of the data to answer some questions about the data such as;
   - what is the overall sales trend
   - which product are top sellers
   - To determine the regional breakdown for the total revenue, quantity sold, average revenue and product
    ```
     ### Data analysis
     ---
     This is where we include some basic lines of code or queries or even some of DAX expressions used during your analysis;

     ```SQL
     SELECT*FROM TABLE 1
     WHERE CONDITION =TRUE
     ```
    ### Data visualization
![SALESAVERAGE](https://github.com/user-attachments/assets/f841f237-e0a6-4737-8b01-22b7cad79980)


![SALESDASHBOARD1](https://github.com/user-attachments/assets/44684e32-df25-4c3c-b37a-5a94fc0c0df7)

![SALESDASHBOARD2](https://github.com/user-attachments/assets/36ac2996-7fa8-4fd2-a601-5b9d05701fd3)

![SALESDASHBOARD2](https://github.com/user-attachments/assets/00c96124-b39a-4361-a855-dc0c5e7296e1)

![SALESDATATRANS](https://github.com/user-attachments/assets/2d62a6e2-a8ff-4234-8c53-4d96085063e9)

![SALESDATAVISUAL](https://github.com/user-attachments/assets/526c520f-4d82-4928-832e-6ea9f1628782)

![SALESPIVOT1](https://github.com/user-attachments/assets/11bc69f4-78f1-4288-921f-3c4f9f6856a3)

![SALESPIVOT2](https://github.com/user-attachments/assets/88986183-e337-42d9-b78c-cd9436af2a54)

![SALESPIVOT3](https://github.com/user-attachments/assets/f93ff775-70da-4cd5-bfb7-80687aff97c4)

![SALESREVENUEREGION](https://github.com/user-attachments/assets/93fc784a-583c-4932-bb4f-be1bcf94cd13)

   
   |heading1|heading2|heading3|
   |-------|---------|--------|
   |Table1|Table2|Table3|
