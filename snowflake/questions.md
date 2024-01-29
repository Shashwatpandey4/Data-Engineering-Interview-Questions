Credits : [Nishchay Agrawal](https://medium.com/@03nishchayagarwal)



Snowflake enables organizations to learn, build, and connect with their data-driven peers. Collaborate, build data apps & power diverse workloads.

I took a referral on LinkedIn for the Data Engineer position at Snowflake.

Snowflake consists of three rounds for the Data Engineer role before final decisions are made. My recruitment process was as follows:

The recruitment process was as follows:

Round 1: Preliminary Round (Screening Round)- 30 mins

This round is taken by the hiring manager for the data engineer role. He asked me related to the previous project that I worked on. So I explained how I use databricks & API and worked on Snowflake pipe to integrate with databricks. He give some scenario based question. How you will capture the data lineage for the spark code. I explained him by taking the example of data lineage build on datahub. He asked some questions on Spark optimisation. He asked me questions on snowflake related on snowflake change data capture, snowflake internal staging use cases. how we can integrate snowflake with external data sources such as S3, GCS or Blob storage in different cloud services. Then he mentioned that there will technical round happend after this call based on SQL, Python, Big Data concepts, Databases, datawarehousing & spark optimisation.

Round 2: Technical Interview (SQL/Python/Big Data Concepts/Database)- 1 hour 30 minutes

This round is taken by senior or staff data engineer. This consists of SQL, Python, Coding, Big Data Concepts, Database concepts.

SQL

The Employee table holds all employees including their managers. Every employee has an Id, and there is also a column for the manager Id.

+ — — + — — — -+ — — — — + — — — — — -+
| Id | Name | Salary | ManagerId |
+ — — + — — — -+ — — — — + — — — — — -+
| 1 | Joe | 70000 | 3 |
| 2 | Henry | 80000 | 4 |
| 3 | Sam | 60000 | NULL |
| 4 | Max | 90000 | NULL |
+ — — + — — — -+ — — — — + — — — — — -+
Given the Employee table, write a SQL query that finds out employees who earn more than their managers. For the above table, Joe is the only employee who earns more than his manager.

— — — — — +
| Employee |
+ — — — — — +
| Joe |
+ — — — — — +
. Table: Employees

— — — — — — -+ — — — +
| Column Name | Type |
+ — — — — — — -+ — — — +
| emp_id | int |
| event_day | date |
| in_time | int |
| out_time | int |
+ — — — — — — -+ — — — +
(emp_id, event_day, in_time) is the primary key of this table.
The table shows the employees’ entries and exits in an office.
event_day is the day at which this event happened and in_time is the minute at which the employee entered the office and out_time is the time at which he got outnumbered from 1 to 1440.
It’s guaranteed that no two events on the same day intersect in time.
Write an SQL query to calculate the total time in minutes spent by each employee on each day at the office. Note that within one day, an employee can enter and leave more than once.
Tips: This question consists leetcode you can refer

Python

Retain records with N occurrences of K
Given a string of balanced expressions, find if it contains a redundant parenthesis or not. A set of parenthesis is redundant if the same sub-expression is surrounded by unnecessary or multiple brackets. Print ‘Yes‘ if redundant, else ‘No‘.
Some questions on Spark optimisation

i) Questions on Spark shuffling & spark hash join

ii) Spark adaptive query execution

iii) Spark broadcast join & shuffle merge join

iv) how Logical plan works when you submit spark query

v) How the rack awareness works

Some questions on API calling with airflow.

How you can build ETL pipeline in snowflake

How to capture the changes if new records insert into source tables, how snowflake will capture the records, then run the ETL job using airflow.

How API works & asked me to design the photon engine backend architecture used in SQL warehouse because I worked

Some questions on airflow operators, hooks, airflow scheduler working

Round 3: Techno Managerial Round- 45 minutes

This round is taken by hiring manager of the snowflake. This round consists of behavioural questions with some technical based.There is discussion on databricks springboot jpa hibernete project.

How to manage multiple tasks if you have to complete within sprint
What are the steps you will taken if you have connect with other lead in the team but he is busy on other task
what is the aspiration to join snowflake
How soon I can join the company
how I design the ETL pipeline using stream kafka or flink if you get new usecases by creating high level design
what are the challenges you have faced while converting the requirement into the solution.
which tech stack I have worked on snowflake. How you deploy snowflake on azure. What are the differnet cluster size you have considered while designing the datawarehouse. What is the things you have taken care to integrate snowflake with databricks
Why we need change data capture using snowflake
On the next day, I got positive feedback from HR. Fortunately, I got selected for the Data Engineer position at Snowflake.