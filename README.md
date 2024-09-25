# README for Supermarket Deliveries SQL and Analysis

**Summary**

The majority of this project was a university project where I had to create a database for some sort of purchase system, and then query it. I proposed a database a for medium-sized supermarket's delivery system. I then, in my own time after graduation, created a Power BI dashboard to express some finidngs and observations from the data.
Excel was used to generate parts of the database, which was accessed on PHP My Admin. All queries were in MySQL. 

**Business case**

A supermarket is a large business with huge amounts of customers ordering home deliveries every day. The company’s turnover will be significantly than that of a small convenience store or similar sized retail business. Despite the supermarket receiving 1000 orders for the past calendar year, it is expected that it will grow rapidly over the years, so using an order book to track orders would be inefficient, ineffective and time consuming. A database provides a structured and organized way to store, manage, and retrieve relevant records of data. Orders can be processed smoothly and seamlessly, meaning that there is accurate and up to date information on the availability of products and statuses of customer orders. Whilst it might be appropriate to manually record data within a smaller sized business, a larger sized business where customer demand is much higher means that data must be able to be accessed and retrieved instantly, and updated in real time. Storing data in a scalable database makes it easier to analyse trends and optimize company procedures in the future. An example of this could be that the number of orders received from a few postal codes on one delivery route have doubled. To respond to this, an additional van has been added to the route, resulting in decreased waiting time which improves customer service and relations with the business. 

**Methodology**

1) Create database schema. There were six entities- customers, orders for delivery, items, order items, item categories and delivery routes
2) Use excel to generate data samples. I used VLOOKUPs to generate information about a customer from a pre-defined table e.g. what delivery route they will be on. I also formatted the results into SQL queries so that I could simply copy and paste the queries into PHP My Admin to insert the data
3) Set primary keys and data types to the data
4) Query database to produce the relevant output. SQL technqiues that were used here include subqueries, aggregate functions, ordering/grouping by, joins, date/time functions, string manipulation and complex calculations such as percentages
5) Design stored procedures and triggers. Parameters were included here to optimise search results
6) Download the database and import into PowerBI. Create relationships between the six tables similar to the database schema.
7) Transform the data using PowerQuery. This included merging the customers first and last name, calculating their current age from their d.o.b., and then creating age brackets based off this
8) Develop a subsequent PowerBI dashboard to visualize results of the queries (and some other information). Visualisations include tables, bar charts, pie charts and stacked bar+line charts. Measures created include the total spent, avergae order value and average number of items per order (these were all often grouped with another variable such as age or item category)

**Skills demonstrated**

Excel (VLOOKUP, formatting), SQL(subqueries, aggregate functions, ordering/grouping by, joins, date/time functions, string manipulation), PowerBI, PowerQuery, DAX

**Results**

(university feedback) 
Overall very good work. There is evidence of some very clear thinking about the project and the SQL is well written and shows a good range of techniques. The database could be a little more complex to provide additional information but otherwise very good work.

The PowerBI dashboard visualized some of the SQL queries but not all. The more complex ones which include subqueries e.g. no. of orders with slower than average delivery time could have been implemented with a more advanced DAX expression.
A range of visualizations were depicted with the correct values.

**Further Improvements**

Used more complex DAX queries to visualise more data, including a subquery. 
Add more entities to the database e.g. staffing
