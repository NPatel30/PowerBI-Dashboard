# PowerBI Dashboard-AdventureWorks
Microsoft AdventureWorks Database Analysis and Visualization with PowerBI. It's sample database, I chose 'AdventureWorksLT2019.bak' and 'AdventureWorksLT2017.bak' data for analysis &amp; visualization. The query editing was done in 'Microsoft SQL Server Management Studio' and visualization part was using 'Microsoft Power BI'. Also for analysis I used MS Excel and PowerBI's query tool.
## Business Request
Sales Manager wants you to:
- Move static reports to visual dashboards.
- Wants to know the number of different products sold to the different clients over the period of time.
- Improve internet sales report.
- Also needs Filters for the Sales Force.
- Measure numbers against Budget. Provided SalesBudget spreadsheet to compare value against performance.
- FYI Budget is for 2021, we usually look 2 years back in time when we perform analysis.

### Business Demand Overview and User Stories(Using Agile Framework)
Business Demand Overview:
- Reporter: xyz -Sales Manager
- Value of Change: Visual Dashboards and Sales reporting.
- Necessary Systems: PowerBI, CRM System
- Other relevant information?: Budgets have been delivered in Excel for 2021.

### User Stories
![image](https://user-images.githubusercontent.com/109983335/234036553-d116c3c0-af6f-4c4a-b213-af67b31d54d3.png)

### Database Link: https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms

From the link above, *"AdventureWorksLT2019.bak"* and *"AdventureWorksLT2017.bak"* data were chosen for restoration.
From *"AdventureWorksDW2019"* Database, the following tables were chosen for analysis:
1. Dim_Customer.sql
2. Dim_Products.sql
3. Dim_Date.sql
4. FactInternetSales.sql

#### Query Editing Tool: "Microsoft SQL Server Management Studio"
#### Visualization Tool: "Microsoft Power BI"



## DATA VISUALIZATION
##### i. Entity Relationship Diagram Model
![1  Model Relations](https://user-images.githubusercontent.com/45898995/119708373-e8bfb780-be7d-11eb-90b2-5da0afdedcce.PNG)

#### ii. Sales Overview DASHBOARD
![2  Sales Overview](https://user-images.githubusercontent.com/45898995/119709090-a64aaa80-be7e-11eb-91bc-4870483b1401.png)

#### iii. Customer Details DASHBOARD
![3  Customer Details](https://user-images.githubusercontent.com/45898995/119709961-a4351b80-be7f-11eb-87b8-13c6315b6eba.png)

#### iv. Product Details DASHBOARD
![4  Product Details](https://user-images.githubusercontent.com/45898995/119710084-c464da80-be7f-11eb-90b3-8e50a0f4ae20.png)



##### Note: *The PowerBI online publishing link isn't available right now because of subscription issues. I'll add that online link soon, so anyone can open it and interact with it as the whole thing is very dynamic.*
