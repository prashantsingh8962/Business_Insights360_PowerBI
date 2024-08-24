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
   
21. Decision metrics: Power Query Vs DAX Measures Vs Created Calculate column

       <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Decision%20Metrics.png" class=" center">


22. we removed unwanted columns in the fact_sales_monthly table in the power query using the choose column options bcoz we can get that info from other tables. If we got to applied steps And see the Native query of doing this. you will a SQL syntax to extract desired columns.

          select `date` as `date`,
         `product_code` as `product_code`,
         `customer_code` as `customer_code`,
         `sold_quantity` as `Qty`
          from `gdb041`.`fact_sales_monthly` `$Table`

    After removing, these columns are not in Power BI but if you go and check the previous steps you will find those columns. these are only previews of 1000 rows.<br>

    we do the same with fact_forecast_monthly table.(This concept is called [query folding](https://learn.microsoft.com/en-us/power-query/query-folding-basics).)<br>

    Comparing DAX calculated columns with Power Query computed columns [Link](https://www.youtube.com/watch?v=-x2dLTtKiR8&t=679s)

    We use a dimension table for slicing like stuff bcoz it contains all the unique things like years.

    Doing query folding with fact_sales_monthly & fact_forecast_monthly, the FactActualsForecast table is also changed bcoz this was make transforming the source 
    table.<br>

    [Star schema](https://learn.microsoft.com/en-us/power-bi/guidance/star-schema)             [Snowflake Schema](https://learn.microsoft.com/en-us/power-bi/guidance/star-schema#snowflake-dimensions)

    Connect fact and dimension tables. This is also called data modelling.<br>

    We are connecting fiscal year but it shows many-to-many relationships. it shows many repetitions in both tables, it's hard to find a connection. so, we created a table of only the fiscal year using DAX. (Fiscal_year = ALLNOBLANKROW(dim_date[Fiscal Year])) we connect the post invoice deduction table, manufacturing cost table, and freight cost table.<br>
    

 <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Data%20Modelling.png" class=" center">


23. Create Calculated Columns Using DAX:<br>
     In the process of creating P&L Table, you have created Gross Price, Pre-invoice deduction amount and Net invoice sales till now using Power Query. So, from now on, you 
     will create the remaining columns required for P & L items using DAX (Data Analysis Expressions)<br>

     We created a post_invoice column with respect to Customer code, product code, and date.

          Post_Invoice_deductions = 
          CALCULATE(max(post_invoice_deductions[discounts_pct]),
          RELATEDTABLE(post_invoice_deductions))

     for finding amt we use var res.(joining two tables)<br>

           Post_Invoice_deductions = 
           var res = CALCULATE(max(post_invoice_deductions[discounts_pct]),
          RELATEDTABLE(post_invoice_deductions))
          return res*(FactActualsForecast[Net_invoice_sales_amt])

     then we did the same for the other_deductions column.(joining two tables)<br>

           Post_Invoice_other_deductions = 
           var res = CALCULATE(max(post_invoice_deductions[other_deductions_pct]),
           RELATEDTABLE(post_invoice_deductions))
           return res*(FactActualsForecast[Net_invoice_sales_amt])

     then we create net sales<br>

           Net_sales_amt = FactActualsForecast[Net_invoice_sales_amt]-FactActualsForecast[Post_Invoice_deductions]-FactActualsForecast[Post_Invoice_other_deductions]

     we find manufacturing cost, freight_

           Manufacturing_cost = 
           var res = CALCULATE(max(manufacturing_cost[manufacturing_cost]),
           RELATEDTABLE(manufacturing_cost))
           return res*FactActualsForecast[Qty]


           Freight_cost = 
           var res = CALCULATE(max(freight_cost[freight_pct]),
           RELATEDTABLE(freight_cost))
           return res*FactActualsForecast[Net_sales_amt]


           Other_cost = 
           var res = CALCULATE(max(freight_cost[other_cost_pct]),
           RELATEDTABLE(freight_cost))
           return res*FactActualsForecast[Net_sales_amt]

     we created Total_COGS_amt and Gross_margin_amt:<br>

           Total_COGS_amt = FactActualsForecast[Manufacturing_cost]+FactActualsForecast[Freight_cost]+FactActualsForecast[Other_cost]

           Gross_Margin_amt = FactActualsForecast[Net_sales_amt]-FactActualsForecast[Total_COGS_amt]


 24. P & L checks: Verify by doing calculation manually and create these type of visuals.

 <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/P%26L%20column%20verfiying.png" class=" center">


 <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Calculator.png" class=" center">



25. DAX Studio : Optimize Report and Reduce File Size by 25 %<br>

    In  power BI, our data first comes in power query then DAX.<br>

    In power query, If we remove gross_price and pre_invoice_deductions, it automatically fetch data of these columns and does calculations bcoz we are connected to SQL. 
    (cache memory).<br>

    In DAX, we removed total_COGS_amt and gross_margin_amount bcoz it is derived from an existing column by simple calculation(+,-,etc). we can derive it dynamically.<br>

    we go for 2 places of decimal digits.

    
 <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Data%20comes%20in%20powerBI.png" class=" center">

- Computed columns can be created either in Power Query or in DAX. Each option has its pros and cons, you need to use a sense of judgment based on a given situation
 
- Snowflake schema can be an extension of the star schema where dimension tables are further connected with other dimension tables
 
- Data modeling is a very important part of the data analytics pipeline. A sincere effort should be spent in building the correct data model
 
- CALCULATE is a frequently used, very important DAX function in Power BI. Mastering this function can make a lot of things easy for you
 
- External tools such as DAX studio can be plugged into power bi for instrumentation and optimization


### 26. Building Finance view: 

    ONLY FOR EXPLANATION :
    we have to compared all Net sales  with India's net sales. we make measures:<br>
    - NIS INR = SUM(FactActualsForecast[Net_invoice_sales_amt])
    - NIS india INR = CALCULATE([NIS INR],dim_market[market]="India")
    - Benchmark Var = [NIS INR]-[NIS india INR]
    - GS INR = SUM(FactActualsForecast[gross_sale_amt])

    we want to compared with last year (LY) also.
    - NIS LY = CALCULATE([NIS INR], SAMEPERIODLASTYEAR(dim_date[Date]))

All Required Measures: 

 <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/All%20Measures.png" class=" center">


 To make this:

  <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/P%26L%20Structure.png" class=" center">


27. we create a P & L rows table. create a measure named P & L values using switch

  <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/P%20%26%20L%20Rows.png" class=" center">


        P & L Values = 
        SWITCH(true(),
        max('P & L Rows'[Order]) = 1, [GS INR]/1000000,
        max('P & L Rows'[Order]) = 2, [Pre Invoice Deduction INR]/1000000,
        max('P & L Rows'[Order]) = 3, [NIS INR]/1000000,
        max('P & L Rows'[Order]) = 4, [Post Invoice Deduction INR]/1000000,
        max('P & L Rows'[Order]) = 5, [Post Invoice Other Deductions INR]/1000000,
        max('P & L Rows'[Order]) = 6, [Total Post Invoice Deduction INR]/1000000,
        max('P & L Rows'[Order]) = 7, [Net Sales]/1000000,
        max('P & L Rows'[Order]) = 8, [Manufacturing Cost INR]/1000000,
        max('P & L Rows'[Order]) = 9, [Freight Cost INR]/1000000,
        max('P & L Rows'[Order]) = 10, [Other Cost INR]/1000000,
        max('P & L Rows'[Order]) = 11, [Total COGS]/1000000,
        max('P & L Rows'[Order]) = 12, [Gross Margin INR]/1000000,
        max('P & L Rows'[Order]) = 13, [Gross Margin %]*100,
        max('P & L Rows'[Order]) = 14, [Gross Margin / unit]
        )


28. we created a Last year's Column (LY):

        P & L LY = CALCULATE([P & L Values], SAMEPERIODLASTYEAR(dim_date[Date]))

    We are also seeing the 2023 fiscal year for which we don't have data. We go to power query and filter to all fiscal years according to the availability of data and 
    remove 2023. In power Query, we can do this dynamically:

        = let
        MaxYear = List.Max(#"FY Changed Type to Text"[Fiscal Year]),
        FilteredTable = Table.SelectRows(#"FY Changed Type to Text", each [Fiscal Year] < MaxYear)
        in
        FilteredTable

 
 We created a column in the fiscal year table named fy-description. it will also add "EST" in the last year because of its forecast estimate values.

           fy_descrption = 
           var maxdate = CALCULATE(max(Fiscal_year[Fiscal Year]),all(Fiscal_year[Fiscal Year]))
           return
           IF(Fiscal_year[Fiscal Year] = maxdate, maxdate & " Est", Fiscal_year[Fiscal Year])

   <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Fy-description.png" class=" center">

### IMP 29. We created two new measures. 
According to the mock-up, we need to create the YoY and YoY % values in the P & L table.
    Hence we create the below two measures

         P & L YoY Chg = [P & L values]-[P & L LY] // this measure will always provide the value change between selected year and previous year

        P & L YoY Chg % = DIVIDE('Key Measures'[P & L YoY Chg], [P & L LY],0)*100 
        // this measure will always provide the % change between the selected year and the previous year


- After this,  Challenge – displaying the correct values in column header based on the selection in fy_desc


If you notice, when you select 2020 IN fy_desc it does display the correct values of 2020 in the table but in the column header it still says ‘P & L values’. This is not an ideal solution for business users who want to take screenshots of this table or who reads the table without selecting a year. So, we need to display 2020 instead of ‘P & L values’ which means you need to display the selected year instead of  ‘P & L values’ in the column header.

 
(You could simply rename the measure names – but the values won’t change dynamically. So, we are looking for a dynamic solution.)


- Creating custom column headers (04:43 – 10:30)

In our case, Power BI matrix uses the measure’s name as the column name. However, to provide the dynamic solution where the column header name will change based on the selection from Fy_desc, we need to create a custom column that will contain all the possible header names.


Steps:
⦁	Create a new column under a new table by using DAX which we can use as our column header.
⦁	The output of this DAX formula is a table that should contain all the possible column header values for the P & L table

⦁	You need to go to the modelling tab and select ‘New Table’

⦁	Create a table called P & L Columns by using the formula below. Check the comments for an explanation of why each formula is used and the same is explained in the lecture.
              
         P & L Columns = 
         var x = ALLNOBLANKROW(fiscal_year[fy_desc]) // this formula will fetch us all the values in fy_desc as the user can select any value from fy_desc 
         return
         UNION(                             // adding all the values from fy_desc with below values
         ROW("Col Header", "LY"),           // ‘LY’ is a requirement from mock up 
         ROW("Col Header", "YoY Chg"),     // ‘YoY Chg’ is a requirement from mock up
         ROW("Col Header", "YoY Chg %"),  // ‘YoY Chg %’ is a requirement from mock up
         x
         )

Now, as an output we will get a column called ‘Col Header’. This list is dynamic and will change if the fy_desc column changes in the future with new fiscal years.

 
- Using the ‘Col Header’ as column values 

Our next step is to convince the Power BI matrix to accept our ‘Col Header’ as the new column name and also make it react to the selections from ‘fy_desc’. Maybe it’s not that tough – let’s give it a try 
Let’s do a quick experiment before that -> you can remove all the measures from matrix values except ‘P & L values’ and add the ‘Col Header’ in Columns.

 

You can see that our hard-earned ‘P & L values’ measure is not working anymore and it is displaying the same values everywhere and also showing all the values of Col Header. 

So, we need a new measure that will 
1. Display the correct values for Line Item
2. Show the correct Col Headers based on selection. For example, if you select 2020 in fy_desc you need to see only 2020, LY, YoY and YoY %. We need a new

But don’t worry – we are not throwing ‘P & L values’ to the bin, it will become a part of our new formula -> “P & L Final Value” (trust me it’s final)


- Creating P & L final value 

Let’s recap our requirements once that this measure needs to fulfil

1. Display the correct values for Line Item
	- This can be done only when you map the [P & L values] to Col Header.
2. Display the correct col headers or in other words, hide the irrelevant values from ‘Col Headers’ based on selection

Let’s experiment to understand better -> 

Create the below measure and add it to the visual
   
    P & L Final Value= 
    SWITCH(TRUE(),
    SELECTEDVALUE(fiscal_year[fy_desc])=MAX('P & L Columns'[Col Header]), [P & L values])

 

You will see that we are able to achieve our goal partially as we can 
1. Display the correct line-item value as per the selection
2. Hide unwanted col headers – but we still need to show LY, YoY, and YoY %.

Now you might wonder, how this formula works. Let’s break it down. 



### IMP30. How P & L final value measure works (Part II)

Note: Understanding this section will help you a long way in your Power BI reporting. So, please plan to spend a considerable amount of time on this. 

Now, Consider an example – when you select 2020 in the fy_desc the following happens in the formula

1. SWITCH(TRUE()   acts as an IF statement where it returns the value if the condition is true. 

If the condition is false, it moves on to the next condition. 
So in this formula, if SELECTEDVALUE of (fiscal_year[fy_desc]) is equal to MAX of ('P & L Columns'[Col Header] then the formula returns [P & L values].

Note: Switch () is a good alternative to avoid multiple IF statements.

2. SELECTEDVALUE (fiscal_year[fy_desc]) returns a single value which is 2020.

This is quite straightforward – it simply returns whatever value you select in fy_desc.

3. MAX ('P & L Columns'[Col Header]) could return all the values in Col Header including 2020.

I hear you loud! You are shouting – Should it not return only one value which is the Max of ‘Col Header’?
 
The answer is Yes and No. It depends upon the ‘Filter Context’. Now, remember the Filter Context that we learned a few lectures ago -> Simplified: Calculate Function ?

Let’s do a quick recap anyway.

Every measure sticks to the natural filter context of the Power BI report which means a measure will respect all the external filters (slicers and page, visual, report filters) and internal filters (dimensions inside visual)

For example, create a measure Max col Header = MAX('P & L Columns'[Col Header]) and add it as a matrix visual on the report page. As you expected, this displays the single maximum value of the Col Header which is ‘YoY Chg %’.


Now what if you add the ‘Col Header’ column to this matrix as a row?

 
You can see that formula gets executed at each row. This means at the row level 2020 of Col Header there is only one value available which is 2020 and hence the MAX('P & L Columns'[Col Header]) will return 2020 for this row and the respective row value for each row. 

The result is the same if you place the ‘Col Header’ in columns. The formula gets executed at each column level.

 
Since you don’t want all the Col Header values and only the fy_desc value you select, you need to set the output of your measure based on condition. 

For example, I need to display the text “Get Job Ready” only for the year I select. This can be achieved by the following measure 

Max Col Header_Dynamic = 

IF(SELECTEDVALUE(fiscal_year[fy_desc])= 
MAX('P & L Columns'[Col Header]), "Get Job Ready" )

You can see that it displays the text ‘Get Job Ready’ only against ‘2022 Est’ in the Col Header as this was restricted to the selected year

 

So, how does it display only the year 2022 Est and ignore the rest?

This is possible because the output is based on a condition where the selected year should match with the Col Header value. Since we can select only one fiscal year, there will be only one match and the rest of the Col Header Years will disappear as they have no data / output.

To verify this, do the following -> 
Click on the drop-down arrow in the Col Header and select ‘Show items with no data’ -   this will show the other columns where there is no data. 

 
By default, this feature is disabled which enables us to hide the Col Header values without data.


Now, Let’s rebuild our P & L visual.

1. Add Line Item to the matrix
 
2. Replace ‘Get Job Ready’ with ‘P & L Values’ measure 

 You can already see that we have reconstructed the P & L final value measure that we built before.


We are few more steps away from completing this formula.

As per our requirement, we need three more columns irrespective of any selection in fy_desc which are LY, YoY Chg and YoY Chg %.


Col Header LY should display [P & L LY], YoY Chg should display [P & L YoY Chg], YoY Chg % should display [P & L YoY Chg %]. 

Since this is a multiple condition, it is recommended to use Switch and use the same technique to build the below formula.

     P & L Final Value = 
    SWITCH(TRUE(),
    SELECTEDVALUE(fiscal_year[fy_desc])=MAX('P & L Columns'[Col Header]), [P & L values],
    MAX('P & L Columns'[Col Header])="LY", [P & L LY],
    MAX('P & L Columns'[Col Header])="YoY Chg",[P & L YoY Chg],
    MAX('P & L Columns'[Col Header])="YoY Chg %",[P & L YoY Chg %]
     )


Note: Irrespective of any selection in the fy_desc we need these three column headers hence they are hard coded in the formula. However, [P & L LY], [P & L YoY Chg], [P & L YoY Chg %] will work based on the selection in fy_desc as they all are still based on SAMEPERIODLASTYEAR() which is dynamic.

And finally, you have our P & L final value measure working as we intended.





### 31.  Creating Quarters, fy_month_num, "YTD,YTG", months
- Filter data based on Quarters 
Any business would like to filter and compare their data by quarter. For a calendar year, Q1 will be from Jan to March… Q4 will be from Oct to December. Basically, a quarter is 1/4th which is 3 months since there are 12 months in a year. For Atliq, the fiscal year starts in September and the quarters are divided as follows:
                  	
Steps for getting the Quarters:
⦁	Go to the Data view and click on the dim_date table.
⦁	Now, here you need to know the difference between the calendar year and the fiscal year
⦁	 A calendar year is the one where January is the starting month.
⦁	The fiscal year depends from company to company and for Atliq it starts in September.
⦁	Now, you need to create a new column with the name fy_month_num which shows the fiscal month number for a given date.
⦁	What is a fy_month_num? Take an example - September can also be termed as month no. 9 as per the calendar year. However, as per fiscal year, it will be no. 1 as it is the start of fiscal year. 
⦁	As the values in the date column of the dim_date table are represented in calendar year form, you need to add an extra 4 months to the date to get the fiscal month.
                 i.e fiscal_month = calendar_month + 4

- Why add an extra 4 months to get the fiscal year month?
⦁	For Atliq, the financial year starts in September, and generally, the calendar year starts in January.
⦁	So, Atliq’s starting month is ahead of 4 months to the calendar year, and this changes from company to company based on their business needs.
⦁	So, the calendar month number for September is 9 and the fiscal month number is 1. In order to make this 9-month number to 1, we need to add an extra 4 to the extracted month and the DATE() function will convert it as the month ‘January’ and give month number 1. 
⦁	Same goes for the October month, where the calendar year month is 10, and when we add 4, it then becomes 14 and the DATE() function converts into the February month and gives the month number 2.
                            	 
                                                      
⦁	So, you will extract the year using YEAR() and month using MONTH() from the date column of dim_date and add an extra 4 to the extracted month, and finally create a new date using the DATE() function and from that, you will extract the fiscal month. The formula goes as follows:

           fy_month_num = MONTH(                                       //getting the month from newly created date
                                           DATE(                                            //creating the new date
                                           YEAR(dim_date[date],               //getting the year
                                           MONTH(dim_date[date])+4,    //getting the month and adding 4 to get fiscal_month
                                            1))                                                 //day of the month
 
⦁	Getting the Quarter from the new column fy_month_num:
                        
			quarters     =  “Q”                                                                              //Adding Prefix “Q”
                          &                                                                               // & is useful for concatenating
                         ROUNDUP(                                                               //rounding to the upper digit
                        dim_date[fy_month_num] / 3,                              //divide by 3 to get quarter number
                         0                                                                                //Number of decimal we want
                          )

- Why divide fy_month_num by 3 and do the roundup?
⦁	We can better understand this by taking examples and decoding them.
⦁	Suppose the fiscal month is 1[September], then 1 divided by 3 gives 0.33 and the roundup function rounds the result to the upper decimal number and gives the value as 1 which means Quarter1.
⦁	Let’s take another fiscal month 3[November], then 3 divided by 3 gives 1 and roundup returns the value 1 which is again the Quarter1.
⦁	For January, the fiscal month is 5, then 5 divided by 3 gives 1.66 and roundup returns value 2 which means Quarter2.

Complete Process:

⦁	Finally, you will see it in the reporting:

 
	
-  Adding Year to Date (YTD) and Year to Go (YTG) 

By general definition, YTD means the value accumulated from the beginning of the year until today and YTG means the rest of the year.

If you go with that definition, in the course, Sep 1st to the Current date will be YTD, and the rest of the days until 31st August should be YTG. 

Now, sit back for a second and ask the question:

Why would Atliq or any company need YTD and YTG?
   
Sales (also called Actuals) YTD will help Atliq understand how much they have sold until yesterday from the beginning of the fiscal year. Now they compare it with last year’s sales YTD or Target YTD to see if they are aligned with the vision.

While you cannot have something like Sales YTG (because sales data is something you have sold already and YTG is future) you can have Forecast YTG or Target YTG to understand how much we need to sell in the rest of the year to meet the target or meet our forecast plan.

In other words, Sep 1st to the last sales date will be YTD, and the rest of the days until 31st August should be YTG. 

Now, let’s back to the dataset

Atliq’s dataset for this course was created in Jan 2022. Hence, the last sales date would be in the month of December 2021. Therefore, September to December will be Year to Date, and the rest of the days till year-end [August] is Year to Go.



Steps for getting YTD and YTG:
⦁	You can check the last sale date from the sales table using MAX()
                i.e MAX(fact_sales_monthly[date])

Note: Even though Atliq’s dataset is not updating every day you need to think about creating a dynamic formula as if the last sales date gets updated every day.  By using Max() you will ensure that always the last sales date is captured.

Ytd_ytg measure below represents the last sales date.
 

⦁	Let’s go ahead and find if each of the values in the date column is YTD or YTG. 


Now, think like an analyst!

Use this thought process to build this column dynamically for all fiscal years. 
(Remember, this is just one way to do it – you can come up with an even better idea!)

As you could have realized already – the ‘last sales date’ is the boundary between YTD and YTG.

Hence, the logic for generating YTD and YTG is when a date in the date column is greater than the last sales then it is YTG. otherwise, it is YTD. 

 

However, if you compare the date column with the last sales date you will get the YTD and YTG only for the current fiscal year which is 2022. Since you need it for all fiscal years – a column that works for all fiscal years is needed i.e. a column that is not attributed to the year but just the months.

And we have the winner, it’s fy_month_num.

Why? -> You can see that it has the fiscal year month number which is the same for all fiscal years. i.e fy_month_num for Dec 21 and Dec 20 is the same as it takes the month into the account and not the year.

So, you will compare the fy_month_num of the date column vs fy_month_num of the last sales date to find if a given date is YTD or YTG.

We have the fy_month_num already, let’s find the fy_month_num of the last sales date now.

⦁	First, get the last sale date in fact_sales_monthly[date]) and store it in a variable LASTSALESDATE.
 

     var LASTSALESDATE = MAX(LastSalesMonth[LastSalesMonth]) //getting the last sale date

⦁	Find the fiscal year month number of ‘last sales date’ using the same formula we used in section 1. 

    var FYMONTHNUM = MONTH(                     //getting the month from newly created date
                 DATE(                                              //creating the new date
                 YEAR(LASTSALESDATE),              //getting the year
                 MONTH(LASTSALESDATE)+4,  1  //getting the month and adding 4 to get fiscal_year
	                        //day of the month
                )

	       
5.   Now you need to use the if condition to check whether the fy_month_num of a date is greater than FYMONTHNUM of last sales date in order to assign it as YTG or else YTD.

               IF(dim_date[fy_month_num] > FyMonthNUM,  //if fiscal month > last date fiscal month
                 "YTG",                                 //if the condition is True, Year to Go
                 "YTD")                                 //if the condition is False, Year to Date


6. Final Formula and Output:

	 


As you can see you have got YTD or YTG definition for each of the date values and this is another reason to have this created as a column than a measure. Since it is a stored column value now, it can be used as a page slicer.




### 32. Finance View: Create a Line chart to Show Performance Over Time
- We use p & L values on Y axis and date on X axis. 
- we check the box in file > setting & options > options > report settings > change default visual interactions.
- we change the date type to "mmm yy"
- in visual, we have set net sales as default value, we go to P & L measures and upgrade it.

	  P & L Values = 
      var res = SWITCH(true(),
      max('P & L Rows'[Order]) = 1, [GS INR]/1000000,
      max('P & L Rows'[Order]) = 2, [Pre Invoice Deduction INR]/1000000,
      max('P & L Rows'[Order]) = 3, [NIS INR]/1000000,
      max('P & L Rows'[Order]) = 4, [Post Invoice Deduction INR]/1000000,
      max('P & L Rows'[Order]) = 5, [Post Invoice Other Deductions INR]/1000000,
      max('P & L Rows'[Order]) = 6, [Total Post Invoice Deduction INR]/1000000,
      max('P & L Rows'[Order]) = 7, [Net Sales]/1000000,
      max('P & L Rows'[Order]) = 8, [Manufacturing Cost INR]/1000000,
      max('P & L Rows'[Order]) = 9, [Freight Cost INR]/1000000,
      max('P & L Rows'[Order]) = 10, [Other Cost INR]/1000000,
      max('P & L Rows'[Order]) = 11, [Total COGS]/1000000,
      max('P & L Rows'[Order]) = 12, [Gross Margin INR]/1000000,
      max('P & L Rows'[Order]) = 13, [Gross Margin %]*100,
      max('P & L Rows'[Order]) = 14, [Gross Margin / unit]
      )
      return
      if(HASONEVALUE('P & L Rows'[Description]), res, [Net Sales]/1000000)

  - For dynamic changing of title, we use a new measured

        Selected P&L rows = if(HASONEVALUE('P & L Rows'[Description]), SELECTEDVALUE('P & L Rows'[Description]), "Net sales")

    In power BI, have a feature to customize the title. we go to title > choose your measure, its done.

    we can do it professionally, we can make a performance visual title.

        Performance visual title = 'Key Measures'[Selected P&L rows] & " Performance over time"

- did normal things cell padding in a grid,  remove title on axis, change font etc.



### 33. Finance View: Build Top Products, Market & Region Visuals
  we created a two matrix, on rows (market, customer) and (segment,category)
  values =   P & L values, P& L YoY chg% 

34. Intermediate review with Nick Puri (product owner): he wants to add net profit rather than gross margin.

        gross margin = 5
        - ads & Promotion = 0.5
        - other operational expenses = 0.5 (account fees + rent + utilities)
        Net Profit: 4
        (Net Profit is the profit)

    Nick Puri shared an excel file of operational expenses.

    we upload it in power Bi and two new columns in our main table FactActualsForecast. (Ads_promotions & other_operational_expense)

        Ads_promotions = 
           var res = CALCULATE(max(Operational_expenses[ads_promotions_pct]),
           RELATEDTABLE('Operational_expenses'))
           return res*FactActualsForecast[Net_sales_amt]

        other_operational_expense = 
           var res = CALCULATE(max(Operational_expenses[other_operational_expense_pct]),
           RELATEDTABLE('Operational_expenses'))
           return res*FactActualsForecast[Net_sales_amt]

    then, create some measures on this,

          Ads & Promotions = SUM(FactActualsForecast[Ads_promotions])
         Other_operational-expenses = SUM(FactActualsForecast[other_operational_expense])
         operational expense INR = [Ads & Promotions]+[Other_operational_expenses]
         Net Profit INR = [Gross Margin INR]-[operational expense INR]
         Net Profit % = DIVIDE([Net Profit INR],[Net Sales],0)

we go power query to add 3 rows in P & L rows, 
        
	 Operational expense   15     Operational expense
           Net profit          16         Net profit
	   Net profit %         17        Net profit %


we edit this P & L values table also. to all these measures in table.


      P & L Values = 
      var res = SWITCH(true(),
     max('P & L Rows'[Order]) = 1, [GS INR]/1000000,
     max('P & L Rows'[Order]) = 2, [Pre Invoice Deduction INR]/1000000,
     max('P & L Rows'[Order]) = 3, [NIS INR]/1000000,
     max('P & L Rows'[Order]) = 4, [Post Invoice Deduction INR]/1000000,
     max('P & L Rows'[Order]) = 5, [Post Invoice Other Deductions INR]/1000000,
     max('P & L Rows'[Order]) = 6, [Total Post Invoice Deduction INR]/1000000,
     max('P & L Rows'[Order]) = 7, [Net Sales]/1000000,
     max('P & L Rows'[Order]) = 8, [Manufacturing Cost INR]/1000000,
     max('P & L Rows'[Order]) = 9, [Freight Cost INR]/1000000,
     max('P & L Rows'[Order]) = 10, [Other Cost INR]/1000000,
    max('P & L Rows'[Order]) = 11, [Total COGS]/1000000,
    max('P & L Rows'[Order]) = 12, [Gross Margin INR]/1000000,
    max('P & L Rows'[Order]) = 13, [Gross Margin %]*100,
    max('P & L Rows'[Order]) = 14, [Gross Margin / unit],
    max('P & L Rows'[Order]) = 15, [operational expense INR]/1000000,
    max('P & L Rows'[Order]) = 16, [Net Profit INR]/1000000,
    max('P & L Rows'[Order]) = 17, [Net Profit %]/100

    )
    return
    if(HASONEVALUE('P & L Rows'[Description]),res , [Net Sales]/1000000)


then, we see Operational expense, Net profit, and Net profit % in our P& L statement (magic happened).

Some point:
- Measure is a “Calculated Field” in Power BI DAX.
- Understanding filter context is very fundamental to the design of Power BI tool. Based on filter context you will be able to figure out how slicing and dicing works and how to change filter context using calculate function.
- A line chart is usually a wise choice to analyze trends over time. It is a useful practice to compare the current year's trend with last year's trend for a selected metric
- While the gross margin is a useful metric, for senior management, visualizing net profit is even more important to understand the real profit.<br>
  Net Profit = Gross Margin - Operational Expenses
-Building BI dashboards is an iterative process. Sometimes in the middle of the project, you may have to import new datasets and rethink the whole design. Having an agile and open mindset helps the data analyst as well as the organization.


## 35. Sales View : 

Any growth company were initially focus on ads and promotions but later on, their operational expenses were reduced when they acquired the market. this view is for sales team view. 

we created:
- one table containing customer, net sales, gross margin, gross margin %.
- One scattered plot on x axis net sales and on y axis gross margin inr, in values market, customer; legend region, size net sales, tooltip gross margin INR
- two donut chart: (net sales, pre_invoice_deduction, total post invoice_deductions), (Total COGS, gross margin) legend-description, values-P&Lvalues.
- One segment matrix rows segment, category, in values net sales, gross margin, gross margin %.

## 36. Marketing View :
- one matrix table containing the segment, category, product in rows and  net sales, gross margin, gross margin %, net profit, net profit % in values.
- One scattered plot on x axis net sales and on y axis gross margin inr, in values segment, category, product; legend division, size net sales, tooltip gross margin INR
- waterfall chart: category-description, Y axis-P&Lvalues.(for achieving colors green for increase, red for decrease, we (-1) in operational expenses, net profit formula Net Profit INR = [Gross Margin INR]+[operational expense INR], previous it was subtracted to get net profit.)
- one more matrix table containing the region, the market in rows and  net sales, gross margin, gross margin %, net profit, net profit % in values.


## 37. Supply Chain View.

We start by pulling back the lastsalesmonth from the Power BI query. We want to unload fact_sales_monthly from Power BI, but we remember we used this table in the dim_date(ytd_ytg) column.  we replace fact_sales_monthly[date] with Lastsalesmonth[Lastsalesmonth] bcoz it mean the same. by this, we removed load of fact_sales_monthly.

        ytd_ytg = 
        var LASTSALESDATE = max(Lastsalesmonth[Lastsalesmonth])
        var FYMONTHNUM = month(DATE(year(LASTSALESDATE), month(LASTSALESDATE)+4, 1))
        return 
        IF(dim_date[fy_month_num]>FYMONTHNUM, "YTG","YTD")

we create a measure name sales QTY 

        Sales QTY = CALCULATE([Quantity], FactActualsForecast[date] <= max(Lastsalesmonth[Lastsalesmonth]))

 To verify whether we got the value right, we went to the sales view with copy card visual of sales QTY. in sales table we add quantity measure from key measures, when we tab YTD in 2022 EST year it showing 40 M sales = 40 M sales QTY. without YTD tab, it showing total 90 M Qantity(sales +forecast) and sales QTY = 40 M.

 we create anothers measures

       Forecast QTY = sum(fact_forecast_monthly[forecast_quantity]) # This is showing whole year forecast quantity but we want after lastsalesdate
       we use this:
        Forecast QTY = 
	   var lsalesDate = max(lastsalesMonth[lastsalesmonth])
           return
	   calculate(sum(fact_forecast_monthly[forecast_quantity]), factActualsforecast[date]<= lsalesDate
       
       
       Net error = [Forecast QTY]-[Sales QTY] 
      
       Net error % = DIVIDE([Net error],[Forecast QTY],0)
     
       ABS Error = sumx(DISTINCT(dim_product[product_code]), ABS([Net error]))
      
       ABS Error % = DIVIDE ('Key Measures'[ABS Error], [Forecast Qty],0)
      
       Forecast Accuracy % = IF(      # By this logic, if the [ABS Error %] is blank the formula will also return blank and hence it won’t be displayed in the table. 
       'Key Measures'[ABS Error %]<>BLANK(),
        1-'Key Measures'[ABS Error %],
        BLANK())

     Forecast acciracy % LY = CALCULATE([Forecast Accuracy %], SAMEPERIODLASTYEAR(dim_date[Date]))

     Risk = IF([Net error]>0, "Excess Inventory", IF([Net error]<0,"Out of stock", BLANK()))

We start building visual:
- 3 card visuals of forecast accuracy %, net error, ABS error.
- one table of customer, forecast accuracy %, net error, ABS error, net error %, forecast accuracy % LY, Risk.
- one table of segment, category, product, forecast accuracy %, net error, ABS error, net error %, forecast accuracy % LY, Risk.
- one line and clustered column chart on x axis date, column y axis net error, line y axis forecast accuracy %, forecast accuracy % LY.


  <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Supply%20Chain%20measures.png" class=" center">


Some points: 
1. Reusability helps in getting things done faster. It is a good idea to copy a visual from one page to another and customize it as per new needs
 
2. For the sales team, Gross Margin and Net Sales (Revenue) are more important than the Net Profit as typically they have least or no control over operating expenses.
 
3. For the marketing team, it would be important to understand the marketing spend change over a time period and subsequent Revenue / Gross Margin change.
 
4. For the supply chain team, important metrics are,
   - Forecast Accuracy & Risk (Out of stock or excess inventory)
   - Net error and Absolute error
  


### 38. Dashboard Vs Report: 

**Dashboard vs. Report: Key Differences**

- **Dashboard:**
  - **Purpose:** Provides a real-time, interactive view of key metrics and data points.
  - **Interactivity:** Highly interactive, allowing users to filter and drill down into data.
  - **Audience:** Typically for management and executives who need a quick overview.
  - **Frequency:** Continuously updated with the latest data.

- **Report:**
  - **Purpose:** Delivers a detailed and static analysis of data, often for specific time periods.
  - **Interactivity:** Limited or no interactivity; usually a static document.
  - **Audience:** Used by analysts or stakeholders needing in-depth analysis.
  - **Frequency:** Generated periodically (e.g., daily, weekly, monthly). 

In essence, dashboards are dynamic and used for monitoring, while reports are static and used for in-depth analysis.


39. 15 rules of effective dashboard:

      <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/15%20rules%20of%20dasboard.png" class=" center">

      [Freepik](https://www.freepik.com/) : This site is used for our project design.

    **its better to make rough dashboard mockup.

    [flaticon](https://www.flaticon.com/) : this is used for getting free icons.


40. we started creating our home page and other 4 visuals(finance, Sales, Marketing, Supply chain) and also make necessary KPI

     <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Home%20page.png" class=" center">

41. Before the stakeholder meeting, they sent a file with UAT(User Acceptance Test) and filled the excel sheet. the idea is to catch the obvious things. Our team already tested from our end before UAT.

    <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Business%20Insights%20UAT.png" class=" center">

- User acceptance testing (a.k.a. UAT) is used for the first round of testing by end-users so that obvious issues can be identified before the solution is released to a broad range of users.
- Power BI service is a cloud solution to host Power BI dashboards. This is the place from where end users can consume the dashboard.
- After a report is published to Power BI service, a good practice is to use export the data from the report to excel (Using Analyze in Excel option) and perform data validation in excel (using pivot table etc)


### 42. Stakeholder Analysis and its Significance :
   It would help if you did your homework. You can do stakeholder mapping analysis. it's just a game of ego managers.

<img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Stakholder%20Mapping%20Analysis.png" class=" center">


I have invited all of you to the stakeholder meeting.

After the meeting, we do the following changes as per the stake holder:

<img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/stakeholder%20Feedback.png" class=" center">



 A. Quick Fixes - 2022 EST chart does not look correct ( bcoz we put factactualForecast(date) instead of fact_forecast monthly date)
                - Fix labels supply Chain SC label ( corrected net profit to ABS Error)
		- Showing Gross margin %, not Gross margin in sales and Marketing view.
                - show footer last refresh date, values in inr, sales load till date.(we create a measure for last load data and for last refreshed date we create a query 
                   in power query using M language)
		        
	                Measures :
		        Last sales Month Footer = 
                        "Sales Data load till : " & FORMAT(max(Lastsalesmonth[Lastsalesmonth]), "MMM YY")

                         M Language :
			 = #table(type table[Report Last Refreshed=datetime], {{DateTime.LocalNow()}})

B. Implementing dynamic Benchmark
   - Add Targets(we provided target.xlsx file we it in power BI)<br>
       we do data modelling by connect month column with dim_date(date) and  market column with dim_market(market).

         create some measures :
	NS Target = SUM(Targets[ns_target])
        NP Target = SUM(Targets[np_target])
        GM Target = SUM(Targets[gm_target])
	
	(for eg 30 % of Gm ~ 30% of each customer (most of the cases) but 30 % of net sales <> 30 % of each net sales) that is why, it remains the same in BM.
 
	GM % Target = DIVIDE([GM Target],[NS Target],0)
        NP % Target = divide([NP Target],[NS Target],0)

 
   - Create a dynamic switch between Targets and LY<br>
         add switch, start with create a table Set BM in which data is like<br>
	      Benchmark        ID<br>
               Vs LY             1
               Vs Target         2
         drag and drop, make it a slicers with one selection on in slicer settings > selection > on
      Create a measure NS BM INR

         NS BM INR = 
         SWITCH(true(),
         SELECTEDVALUE('Set BM'[ID]) = 1, [Net sales INR LY],
         SELECTEDVALUE('Set BM'[ID]) = 2, [NS Target])

     drag nad drop it in Net sales KPI's.<br.

     we created a measure for product/customer filter check:<br>

                product/customer filter check: isfiltered(dim_products(product)
                isfiltered means it will return true when u filter to direct products.otherwise false
                iscrossfiltered means it will return true when u filter to direct or indirect products.

                Customer / Product filter Check = ISFILTERED(dim_customer[customer]) || ISCROSSFILTERED(dim_product[product])

	        we re-edit this :
                NS Target = 
                var tgt = SUM(Targets[ns_target])
                return if([Customer / Product filter Check],BLANK(),tgt)

                correct this
                GM % Target = DIVIDE([GM Target], SUM(Targets[ns_target]),0)
                NP % Target = divide([NP Target],SUM(Targets[ns_target]),0)


               2 more measures :
               GM BM INR = 
               SWITCH(true(),
               SELECTEDVALUE('Set BM'[ID]) = 1, [Gross margin % LY],
               SELECTEDVALUE('Set BM'[ID]) = 2, [GM % Target])




               NP BM INR = 
               SWITCH(true(),
               SELECTEDVALUE('Set BM'[ID]) = 1, [Net Profit % LY],
               SELECTEDVALUE('Set BM'[ID]) = 2, [NP % Target])


     we get the switch between Vs LY and Vs targets.

               BM Message = if( [GM % BM]= BLANK() || [NS BM_INR]= BLANK() || [NP % BM] = BLANK(), "BM target(s) is not available for the selected filters.","")
     
     

- P & L visuals to compare Target or LY based on Selection
   we did this for all visuals. start with creating new measures of P & L target value

               P & L Targets = 
               var res = SWITCH(true(),
              max('P & L Rows'[Order]) = 7, [NS Target]/1000000,
              max('P & L Rows'[Order]) = 12, [GM Target]/1000000,
              max('P & L Rows'[Order]) = 13, [GM % Target]*100,
             max('P & L Rows'[Order]) = 17, [NP % Target]*100
             )
             return
             if(HASONEVALUE('P & L Rows'[Description]),res, [NS Target]/1000000)


              P & L BM = 
          SWITCH(true(),
          SELECTEDVALUE('Set BM'[ID]) = 1, [P & L LY],
         SELECTEDVALUE('Set BM'[ID]) = 2, [P & L Targets])


do some changing in 
             
	       P & L Final Value = 
    SWITCH(TRUE(),
    SELECTEDVALUE(Fiscal_year[fy_descrption])=MAX('P & L Columns'[Col Header]), [P & L values],
    MAX('P & L Columns'[Col Header])="BM", [P & L BM],
    MAX('P & L Columns'[Col Header])="Chg",[P & L CHG],
    MAX('P & L Columns'[Col Header])="Chg %",[P & L chg %]
     )



     P & L Columns = 
    var x = ALLNOBLANKROW(Fiscal_year[fy_descrption])
    return
     UNION(
    ROW("Col header","BM"),
    ROW("Col header","Chg"),
    ROW("Col header","Chg %"),
    x
    )


     P & L CHG = 
    var res = [P & L Values]-[P & L BM]
    return if(ISBLANK([P & L BM]) || ISBLANK([P & L Values]), BLANK(),res)
 
 
    P & L  chg % = 
    var res = DIVIDE([P & L CHG],[P & L BM],0)*100
    return if(ISBLANK([P & L BM]) || ISBLANK([P & L Values]), BLANK(),res) 


we got the result.!! for graph put this, you get the result.


C. Adding Dynamic Slicer to Filter Visual 

    Target Gap tolerance = GENERATESERIES(0, 0.2, 0.01)           ~~~ create a table Target Gap tolerance using modelling > what if parameters

    GM % Variance = [GM % BM]-[Gross Margin %]       
	   
    GM % filter = if([GM % Variance] >= SELECTEDVALUE('Target Gap tolerance'[Target Gap tolerance]),1,0)

    use  GM % filter in filter sections, apply only to that visual, condition is equal to 1.


D. Create a Toggle Button to Switch between Two Visuals:
    start with creating a button show NP %, copy it and mark another button Show GM %. make same graph with respect net profit %.


     - got to selection, group them as NP % visual( gm % button, NP % visual) and GM % visual(show NP % button, GM % visual)
     - then create bookmark with uncheck data option, show NP % when GM % visual is hide and then update and show GM % when NP % visual is hide and then update
     - in visualization go to action choose bookmark navigation to show NP % and show GM% bookmarks.


E. Create a Tool Tip to Show Trend:
       in tooltip, overing is equal to selecting. creating tooltip on GM% and Net sales with respect to month.


### 43. Executive view : 

 open market share file in power query, select all manufacturers unpivot it. then extract before delimiter. close & apply !!

 we create some table sub_zone and category for connection in data modelling. we created a ribbon chart.

 
 now, we had mock-up of the executive view, we started. 
 - copy the finance view, we have 3 kpi's(net sales, gross margin %, Net profit%) , fourth one we add from supply chain view forecast accuracy %.
 - we two donut chart of division and channel with respect to Net sales(both).
 - Key insights per sub_zone

    A.we create a table with sub_zone, Net sales, Gross margin %, revenue contribution (RC %), Net profit %, Market share % (for atliq, we have to filter with manfacturer in the filter option), net error %, Risk.
   we used conditional formatting in gross margin % section. click on gross margin % column in visualization section go to condition formatting > icons> choose gm % variance> make the formatting.  

       RC% = DIVIDE([Net Sales], CALCULATE([Net Sales], ALL(Sub_zone[sub_zone])))

 - we make a line and cluster chart with fr_description on x axis, column y axis net sales, line y axis Gross Margin %, Net profit %, Market Share %. but for seeing at atliq, we do same thing for atliq, we have to filter with manfacturer in the filter option and remove interaction: we click on year slicer go to format > edit interaction> off interaction with our graph. at last, it show the right curve. Sort the axis in fy-description and ascending order.

- we make ribbon chart and top 5 customer &  5 product with RC % & Gross Margin %(also used condition formating> icons> choose gm % variance> make the formatting.  

      AtliQ MS % = CALCULATE([Market Share %],'Market Share'[Manufacturer]="atliq")
      RC% = DIVIDE([Net Sales], CALCULATE([Net Sales], ALL(dim_customer), all(dim_market), all(dim_product)))


44. Learn: Performance Optimization(go to performance analyzer in view)
    start recording> refresh visuals> click on which want  to see ~~ copy query> open DAX studio(paste it there) --- you will a big dax query... if run it it will give you the same result. >click query plan.. server setting --- breakdown into small step, it will show how it perform the query and this help in debugging the query. if query take too long time you can check if it is im balance, formula engine and storage engine. doing this, you can find out why steps are slower in power BI.

    If you want to go technical Refer this [DAX Best Practices 101 for Optimization & Performance with Alberto Ferrari](https://www.youtube.com/live/DSiRHOcI-es?si=9uHbpSo4CDh1IslS)

    Do basic data cleaning amazon_ , AtliQ exclusive and talk to data engineer to resolve this.

45. Some points : 
- Stakeholder expectation management is one of the most useful skills you can develop in order to become successful in your career.
- When you are in a stakeholder meeting, it helps if you have a clear understanding of stake holder’s personalities and expectations and drive the discussion accordingly. - Stakeholder mapping is an effective way to gain this understanding.
- The secret to become “Job Ready”, is to practice job scenarios as much as possible. Try things out on your own and build visualizations that can answer questions related to data analytics.
-Learning how to create the following features in Power BI are very useful as they can be reused in multiple occasions
- Using bookmarks & buttons to change visuals / navigate page
- Using slicers to filter / highlight visuals
- Switch measures using a toggle button


46. Power BI service overview, report sharing and apps:
     we published a report and extracted the analyzed report in excel. this excel report and power bi , we used to make to apps . microsoft excel , power BI service, teams can easily connected to each other.

    Automate setup data refresh from SQL: we used personal gateway or organisation gateway
          - establish a personal gateway with SQL.
          - fill credentials for connection using gateway.
    


    Automate setup data refresh from Excel :
    SharePoint(drive) moves all local files to SharePoint* Any file you see on the mMSteam is automatically stored on SharePoint(copy URL). Go to the PowerQuery Editor.
    - new source> SharePoint Folder(paste that URL), you get a query renamed " Excel data Source" .
    - create a blank() rename " MarketShare Excel Source", click binary in front marketshare, then choose table in front of marketshare. do same for all excel files.
   

     Simplified: Collaboration, Bookmarks, and Insights in Power BI Service:
     - we can share on teams and email while filtering things through collaboration.(networking, EPAC)
     - we also make bookmarks for the same thing.
     - we also create subscription on a particular view to update you on email.
     - there is an insight option to generate inside from you.
   

    Driving the Extra Mile: Documentation and Maintenance:
           Building info & support pages.


    Some point :
    - Once a dashboard is built, it is important it gets refreshed at regular intervals and includes the latest data points
    - An automatic refresh can be set for databases such as MySQL using a personal or organizational gateway
    - An automatic refresh for files (e.g. excel file) can be set up using Microsoft SharePoint
    - Power BI service as rich support for effective collaboration. One can share exact data points via email or teams chat with other users.


          
    

    









      
