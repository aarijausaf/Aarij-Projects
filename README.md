# Performance Metrics of a Superstore-Dashboard

### Dashboard Link : [https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection](https://app.powerbi.com/groups/me/reports/e76993d9-0eba-42e9-8cff-cf0a1de6cccf/ReportSection?experience=power-bi)

## Problem Statement

This dashboard helps the manager of a superstore understand the sales of the products in its store by analysing the profit and sales margin as per each product and its category, alongwith how is the discounting helping in the sales of any products. It also helps in analysing which product is being sold more and vice versa. The analysis also deals in understanding the regional behaviuor of the products as in which which states are consuming the more number of products and in which category. 

The interactive dashboard formed in the PowerBI will help the manager analyse which products he can focus more on in order to increase the profitability and which products or areas to let go off to reduce the cost of the store. In contrast, the manager could also start focusing on the low profitability areas and products to generate more revenues out of it.




### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : Using the "Use First Rows as Headers" button in the Home tab, promote the first row as the header of the dataset.
- Step 6 : New measure was created to find the Total Profit.

         Total Profit = sum(SampleSuperstore[Profit])
- Step 7 : New measure was created to find the Total Sales.
 
         Total Sales = sum(SampleSuperstore[Sales])
 
 Two seperate card visual were used to represent both these figures.
 
![Screenshot (8)abc](https://github.com/aarijausaf/Aarij-Projects/assets/169148343/acc00fa5-6713-4847-bf6b-0f015f2f5d2e)

 

 
 - Step 8 : The report was then published to Power BI Service.
 


# Snapshot of Dashboard (Power BI)

![Screenshot (9)](https://github.com/aarijausaf/Aarij-Projects/assets/169148343/9083d4df-9c59-42fb-8002-866906167dca)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Screenshot (9)nn](https://github.com/aarijausaf/Aarij-Projects/assets/169148343/64273055-afbd-4139-a55c-104e9e305ecc)


# Insights

A dual page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Contribution to Total Profit by Category

   50.79% of the total profit comes from Technologies

   42.77% of the total profit comes from Office Supplies

   6.44% of the total profit comes from Furniture



        Since, a significantly small number of contribution to the total profit
        is made by the Furniture Category, it could be advised to stop the furniture
        supply and put more emphasis on the rest two categories in order to get
        more efficeiency in the business.
           
### [2] Discount Distribution

    By the bar graph illustration, it is clearly evident that Technology which contributes highest to the 
    total profit gives out the least number of discount to the customers, hence, stating that technology goods 
    make their own demand. While on the other hand, furniture which doesn't have a significant contribution to
    the total profit takes a significant amount of discount's share.
