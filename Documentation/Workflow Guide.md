## Business Insights detailed Worked Flow Guide (Step-by-Step)

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
   * AtliQ Hardware sells its product<br>
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


8. We have a Data catalog that looks like this.

   
    <img src="https://github.com/prashantsingh8962/Business_Insights360_PowerBI/blob/main/Resources/Doc%20Pics/Data%20Catalog.png" class="center">








    






 

                    




