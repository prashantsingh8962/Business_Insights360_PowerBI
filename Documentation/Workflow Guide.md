## Business Insights detailed WorkFlow Guide (Step-by-Step)

1. Nick Puri (Product Owner) sent an email to Stephen Singh(Analytics Director) showing more details of the "Business Insights 360 Dashboard" project.

   <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Nick%20puri%20email.png" class="center">
   
   And attached Excel file outlines the features.

   <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/attached%20features.png" class="center">


2. In response, Stephen Singh(Analytics Director) emailed Tony Sharma(Senior Data Analyst) to share project details and ask for a call with the PO.
 
   <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Stephen%20email.png" class="center">


4. After That Tony Sharma sent an email to Nick Puri(Product Owner) for a Project Kickoff Meeting.

    <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Tony%20email%20to%20Nick.png" class="center">


5. During the time Tony Sharma does some homework, assign a team(me, Prashant) and also create a Project Charter for the kick-off meeting.

   <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Project%20Charter.png" class="center">


### Project Charter: 
A project charter is a short document describing the entire project. We will use a tool called Mural for this and cover a few important dimensions of the project such as,<br>
-> Project goals<br>
-> Key stakeholders<br>
-> Hopes and fears<br>
-> Risks<br>
-> Timeline<br>


5. Basics Understanding:
   * Atliq Hardware sells its products to customers(Croma, Flipkart, Best Buy) and this customer of AtliQ Hardware sells further to consumers.
   * AtliQ hardware uses two platforms brick & mortar(Croma, Best Buy) and e-commerce(Amazon, Flipkart).
   * AtliQ Hardware sells its product through channel<br>
                    1. directly also in its own AtliQ store, AtliQ exclusive, etc.<br>
                    2. Retailer in Croma, Amazon, etc.<br>
                    3. distribution in Neptune then they further distributed to their sub mall like Babu, kim-cho, etc then consumer.<br>
   * Profit & loss statement:<br>
                    1. Gross Price: Initial price of the Product(AtliQ)<br>
                    2. Pre-invoice Deduction: Discount given by the company(AtliQ)<br>
                    3. Net Invoice Sales: Gross Price - Pre-invoice Deduction<br>
                    4. Post-invoice sales : Promotional offers + Placement fees + Performance rebate<br>
                    5. Net sales: Net sales are the revenue of a company(AtliQ)<br>
                    6. Cost of Good Sold(COGS) : Manufacturing cost + Freight(Transporation) + Other cost<br>
                    7. Gross Margin<br>

     The profit and loss statement is the most important piece of analysis any company will need.

 <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/P%26L%20Concepts.png" class="center">


 6. Kickoff Meeting: We Had some questions to ask and At Last, we asked for benchmark no and a mockup dashboard layout from Nick Puri(Product Owner)

    <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/KIckoff%20meeting.png" class="center">

 
7. Some data-related terms:<br>
   ### * OLTP Vs OLAP : <br>
     ### OLAP (Online Analytical Processing):<br>
     1. Purpose: Primarily used for data analysis and decision-making. It enables complex queries and reports that involve large volumes of historical data.<br>
     2. Data: Stores aggregated, historical data from various sources, often organized in a multidimensional schema (e.g., star or snowflake schema).<br>
     3. Operations: Focuses on read-heavy operations such as data mining, trend analysis, and complex queries.<br>
     4. Users: Typically used by business analysts, data scientists, and decision-makers for strategic planning.<br>
     5. Performance: Optimized for query performance over large datasets, with response times suitable for complex analyses.<br>
     Examples: Data warehousing systems, business intelligence tools like Tableau or Power BI.<br>

     ### OLTP (Online Transaction Processing):<br>
     1. Purpose: Designed to manage day-to-day transactional operations. It supports a large number of short, quick transactions.<br>
     2. Data: Stores current, real-time data in a normalized schema, ensuring data integrity and consistency.<br>
     3. Operations: Focuses on insert, update, delete, and simple queries, such as processing customer orders or banking transactions.<br>
     4. Users: Typically used by front-line workers, such as cashiers, bank tellers, and customer service representatives.<br>
     5. Performance: Optimized for fast query processing and maintaining data integrity in high-concurrency environments.<br>
     Examples: Retail transaction systems, banking systems, CRM systems.<br>

     ### Key Difference:
     1. OLAP is for analysis and decision-making, involving complex queries on large datasets.<br>
     2. OLTP is for everyday transactions, focusing on fast, efficient processing of small, quick queries.

     
    <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/OLTP%20Vs%20OLAP.png" class="center">


   ### * Data analyst Vs Data engineer Vs Software engineer : <br>
        
      ### Data Analyst:<br>
      1. Role: Focuses on interpreting data to provide actionable insights. They analyze large datasets to find trends, patterns, and correlations that help inform business 
         decisions.<br>
      2. Skills: Proficient in data visualization tools (e.g., Tableau, Power BI), statistical analysis, SQL, and Excel. Strong understanding of business intelligence.<br>
      3. Tasks: Cleaning and organizing raw data, creating reports, and communicating findings to stakeholders.<br>

      ### Data Engineer:<br>
      1. Role: Designs, builds, and maintains the infrastructure and systems that enable data collection, storage, and access. They ensure that data is accessible, 
         reliable, and well-structured for analysis.<br>
      2. Skills: Expertise in data pipelines, ETL (Extract, Transform, Load) processes, databases, cloud platforms (e.g., AWS, Azure), and programming languages like 
         Python, Java, or Scala.<br>
      3. Tasks: Building data warehouses, developing data pipelines, and optimizing data storage for performance and scalability.<br>

      ### Software Engineer:
      1. Role: Develops, tests, and maintains software applications. They are responsible for building the software systems that users interact with, ranging from web 
         applications to mobile apps and backend services.<br>
      2. Skills: Proficient in programming languages (e.g., Python, Java, C++), software development frameworks, version control (e.g., Git), and problem-solving.<br>
      3. Tasks: Writing and reviewing code, debugging software, collaborating with other engineers to design and implement new features, and ensuring the software meets 
         quality standards.<br>

      ### Key Differences:<br>
            Focus:<br>
                  Data Analysts focus on extracting insights from data.<br>
                  Data Engineers focus on building systems to collect and manage data.<br>
                  Software Engineers focus on creating software applications.<br>
             End Goal:<br>
                  Data Analysts provide business insights.<br>
                  Data Engineers ensure data is accessible and reliable.<br>
                  Software Engineers deliver functional software products.<br>

   
    <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Difference%20DA%2CSE%2CDE.png" class="center">


8. We have a Data catalog that looks like this.(We need these DB Servers gdb056 & gdb041 as per our requirements)

   
    <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Data%20Catalog.png" class="center">


9. We installed MySQL and opened both files gdb056 & gdb041 in MySQL <br>
     [Link](https://dev.mysql.com/downloads/installer/)
    
10. Exploring Data: <br>
     gdb041:<br>
           1. dim_customer<br>
           2. dim_market<br>
           3. dim_product<br>
           4. fact_forecast_monthly<br>
           5. fact_sales_monthly<br>

    gdb056:<br>
           1. freight_cost<br>
           2. manufacturing_cost<br>
           3. pre_invoice_deductions<br>
           4. post_invoice_deductions<br>
           5. gross_price<br>

11. We connect our MySql database server with Power BI. While doing so, it needs an outside connector to download. we did it.
     [Connector](https://dev.mysql.com/downloads/connector/net/)

12. Power Bi automatically makes a relation between tables. to stop this feature, we go to options > Data load > uncheck the "Autodetect relation after data is loaded." 
    feature.

13. In the transform data option, it is the power query editor in Power BI. If you want a quick insight into dimension tables you can go to the view option, enable column 
    distribution, and column profile. it only allows 1000 rows  therefore mostly used for dimensions tables.
     * column profiling can also be done for the entire dataset but it will impact the query load time.

14. ### Create a date table in power query:
    We make groups: all dim tables in the "dimensions" group and all fact tables in the "Facts" group
    We are adding a new query in the power query editor from a new source -> blank query.

    We using [M language](https://learn.microsoft.com/en-us/powerquery-m/) to do this. <br>
     
    Rename it as dim_date. use this formula in the advanced editor of dim_date to find the date as per fiscal year. It is a list, we can convert to table   <br>
    Date ={Number.From(#date(2017,9,1))..Number.From(#date(2022,12,31))}   <br>

    Add another column month from the add column section, in the option, the start of the month bcoz we want to extract the fiscal year later from it. <br>
    Add a custom column "Fiscal Year", using this formula =Date.Year([month]) -> This will fetch the same year but we want the fiscal year then we use this formula
    =Date.Year(date.AddMonths([month],4))

15. ### Benchmark Validation:
    We have to verify All these benchmarks with our numbers.

    <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Benchmark%20Nos.png" class=" center">

Our Number fully matches with benchmark number means:<br>

   <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Our%20Nos.png" class=" center">

@ Suppose our number does not match with the benchmark number, we find out the difference and reach out to the data engineer to find a resolution to this.

16. Star schema contains fact and dimension tables. Facts are transaction tables whereas dimensions are entity tables. When we connect them to build a data model, it creates something called a STAR schema.

17. Product owners share the same mockup dashboard.<br>
     Year-to-day: sum of all available actuals estimate.<br>
     year-to-go: sum of all remaining forecast estimates.<br>
    If we sum them two we get a landing estimate.<br>

    <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Finance%20View.png" class=" center">

   <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Sales%20View.png" class=" center">

   <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Marketing%20View.png" class=" center">

   <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Supply%20Chain%20view.png" class=" center">


18. We start in power query finding the current month. we create a reference of fact_sales_monthly table and use the formula: = List.Max(#"gdb041 fact_sales_monthly"[date])
    then, we get the last sales month which is this "01-12-2021 00:00:00". we do reference if fact_sales_monthly update, it is also updated.<br>

    We create the "remaining forecast" table with reference to fact_forecast_monthly by filtering on dates greater than "lastsalesmonth". we used M language :<br>
      = Table.SelectRows(Source, each ([date] > Lastsalesmonth))<br>

    We use the append(rowise joining) option to append two tables fact_sales_monthly & remaining forecast and call it "FactActualsForecast" table. doing this, we find separate columns of sales_quantity and forecast_quantity and so many null values in these columns but we want them in one column. we changed this sales_quantity column and forecast_quantity column as qty in both the tables separately.

19. We add a Fiscal year column in "FactActualsForecast" using the custom column: Date.Year(Date.AddMonths([date],4)) <br>
    we merge(left join) two tables "FactActualsForecast" and "gross_price". we got a table with an added gross_price column.<br>
    we create a custom column for gross_price_amt= [Qty] * [gross_price]<br>

    We merge(left join) two tables "FactActualsForecast" and "pre_invoice_deductions". we got a table with an added pre_invoice_discount_pct column.<br>
    we create a custom column for pre_invoice_discount_amt= [gross_price_amt] * [pre_invoice_discount_pct]<br>
    we create a custom column for net_invoice_sales_amt= [gross_price_amt] - [pre_invoice_discount_amt]<br>


    Power Query Best Practices<br>
    -> Naming query steps<br>
    -> grouping tables<br>
    -> Disable load for some tables to improve performance<br>
    -> Table naming convention<br>

20. - DAX Behaviour is like filter context in power BI.<br>
    - Filter context is changed using CALCULATE Functions. It is changed to create measures that require a new filter context.<br>
    - ALL is a filter function used together with the calculate.
    - ALL removes the given column or table from the filter context.
    - ALL removes all the columns or tables from the filter context except the specified ones.
    - One can specify filters directly in the filter argument section of calculated functions.
    - we can specify the column from another table in the filter argument as long as that table is connected using the data model.
    - In case where you are using DAX measures in the filter argument section, you have to use filter() functions.
    - DAX can be used to create both measures and calculated columns.
    - Utilizing a var function in DAX offers added flexibility for writing complex functions.
    - cross-verifying values manually is a valuable practice.
    - Filter Context: Filter context is the set of values allowed in each column, based on filter constraints that were applied to the row or that are defined by filter 
      expressions within the formula.(<> means "not equal to")
    - The “Calculate “ function helps change the filter context. This function allows you to change the context in which an expression is evaluated.
    - The filter function “ ALL ” returns all the rows in a table, or all the values in a column, ignoring any filters that might have been applied. This function is useful 
      for clearing filters and creating calculations on all the rows in a table.
    - The filter function “ ALLEXCEPT “ removes all context filters in the table except filters that have been applied to the specified columns.
    - The filter function “ FILTER “ returns a table that represents a subset of another table or expression.
    - Sometimes the data we're analyzing does not contain a particular field necessary to achieve the desired results. In such situations, calculated columns are useful. 
      These columns use Data Analysis Expressions (DAX) formulas to define their values.
    - Check out [Documentation](https://learn.microsoft.com/en-us/dax/filter-functions-dax)
   
21. Decision metrics:

       <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Decision%20Metrics.png" class=" center">


22. 
    
    






    






 

                    




