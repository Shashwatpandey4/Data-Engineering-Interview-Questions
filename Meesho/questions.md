Credits : [Nishchay Agrawal](https://medium.com/@03nishchayagarwal)


Meesho is a social commerce platform that undertakes retail distribution, enabling small retail merchants to connect and sell their products effectively via social media channels. Meesho comes under the Top 100 Influential Companies. It is the fast-growing E-commerce company of India

If you want to crack Top Product based companies & want mentor who will assist you in developing your personal strategy and setting goals based on your target company from day 1 on Preplaced. I’m always here to help

You can connect with me for a free trial for Data Engineering Roadmap on Preplaced — https://visit.preplaced.in/8dl

I gave an interview in Meesho after I worked at Morgan Stanley as a Data Engineer

I graduated in 2021 Batch of computer science and engineering. I worked in previously worked at Morgan Stanley. I have around 1 year of experience (including an internship). I took a referral on LinkedIn for the Data Engineer position at SDE-2 Data Engineer at Bengaluru Division. Consists of five rounds for the SDE-2 Data Engineer role before final decisions are made.

Interview Result of Meesho: I got selected as SDE-2 Data Engineer at Meesho

The recruitment process was as follows:

Round 1: Preliminary Round (Coding Assessment Round):

This is the SDE-2 Data Engineering Recruiting Test conducted on the Hackerrank platform. The total duration of the test was 1hours and consisted of 4 sections, each of which was individually timed. The sections were:

SQL Coding Questions:
One Coding Question Based on Data Structure:
One Coding Question Based on Algorithm
I did my all SQL questions & all Data Structure Questions and passed all test cases of the coding question. I completed my test in 55 mins. The level of coding questions is medium to hard for Data Structure & Algorithm

Tips:

Focus on medium level data structure topics such as Array, String, Stack, Queue, Linked List, and Tree (only Binary Search Tree).
Focus on Tree & Graph concepts clear
Focus on Window functions of SQL that is commonly asked in Test
Concentrate focus on Python Data Structures such as List, Tuple, Set, and dictionaries (hard-level). You can also deep dive into Pandas (python library) and file handling.
Round 2: Technical Interview 1 (Coding & DSA Round): 1:30 minutes

I got a call from HR that my online test for Data Engineering is cleared and I was shortlisted for the coding round. This round lasted for about 1 hour 30 minutes and is taken by the Bar Raiser Interview Platform for the Coding & DSA based round
This interview involves two complete medium to hard-level DSA questions
Given an array of N non-negative integers arr[] representing an elevation map where the width of each bar is 1, compute how much water it is able to trap after rain.
Examples:
Input: arr[] = {2, 0, 2}
Output: 2
Explanation: The structure is like below.
We can trap 2 units of water in the middle gap.

Trapping Rain Water - GeeksforGeeks
A Computer Science portal for geeks. It contains well written, well thought and well explained computer science and…
www.geeksforgeeks.org

2.
Table: Activity

— — — — — — — -+ — — — — -+
| Column Name | Type |
+ — — — — — — — -+ — — — — -+
| user_id | int |
| session_id | int |
| activity_date | date |
| activity_type | enum |
+ — — — — — — — -+ — — — — -+
There is no primary key for this table, it may have duplicate rows.
The activity_type column is an ENUM of type (‘open_session’, ‘end_session’, ‘scroll_down’, ‘send_message’).
The table shows the user activities for a social media website.
Note that each session belongs to exactly one user.
Write an SQL query to find the average number of sessions per user for a period of 30 days ending 2019–07–27 inclusively, rounded to 2 decimal places. The sessions we want to count for a user are those with at least one activity in that time period.

Next question on Data Structure Tree

Write a function to print the ZigZag order traversal of a binary tree. For the below binary tree, the zigzag order traversal will be 1 3 2 7 6 5 4.

Tips: Focus on Leetcode SQL Questions or Hard Hackerank or Medium Level geeksforgeeks questions

Round 3: Technical Interview 1 (SQL Coding/DSA Round & Big Data Concepts): 1:30 minutes

I got the call that my coding round was cleared. Now I have a second coding round basically focussed on SQL questions (Window Functions or Joins Hard Level SQL Questions) and one Data Structure Stack Question with Big Data Concepts

I was asked one leetcode SQL question
+ — — — — — — -+ — — — — -+
| Column Name | Type |
+ — — — — — — -+ — — — — -+
| id | int |
| num | varchar |
+ — — — — — — -+ — — — — -+
id is the primary key for this table.
Write an SQL query to find all numbers that appear at least three times consecutively.

Return the result table in any order.

The query result format is in the following example:

Logs table:
+ — — + — — -+
| Id | Num |
+ — — + — — -+
| 1 | 1 |
| 2 | 1 |
| 3 | 1 |
| 4 | 2 |
| 5 | 1 |
| 6 | 2 |
| 7 | 2 |
+ — — + — — -+

Result table:
+ — — — — — — — — -+
| ConsecutiveNums |
+ — — — — — — — — -+
| 1 |
+ — — — — — — — — -+
1 is the only number that appears consecutively for at least three times.

. Next question, he gives Stack Questions to solve on a notepad The Stock Span Problem. This is the question of geeksforgeeks https://www.geeksforgeeks.org/the-stock-span-problem/

Now, he moves to Big data concept questions.

How do you handle the skewness in the data? What is the salting mechanism and broadcast join? I explained by taking practical examples on the notepad by having one large dataset & small dataset stored in CSV format
He asked me whether the below function or logic is action or transformation
df=spark.read.format(“delta”).load(“/parquet/snapp.parquet”)

3. Explain the workings of parquet & how parquet stored data in the columnar format. How it differs from the delta table format

4. Lot of questions on Mappers & Combiner from Map Reduce. How to make the mapper to one by using which property.

5. He asked me the difference between managed vs unmanaged tables. He started on Databricks. He asked me how Databricks creates clusters. Are databricks cluster standalone or Yarn mode cluster?

6. Suppose I have 10 workers' machines & total of 100 GB RAM with 25 Cores.

i) How many executors will be there?

ii) What is the size of each executors in terms of CPU or memory

iii) When OOM occurs in Spark Driver

I have to give the answer to this question based on the Databricks Lakehouse cluster.

7. He asked me to write the code in Java using File Input Stream Reader Class to read the data from the local file & print the output of the file on the console. Then he asked me some questions on OOPS

8. Finally, he asked me question on the Sqoop. How you will import 5 tables in sqoop from the external database? I wrote the command for the same

Round 4: Technical Interview 2(System Design Coding & ETL Design Round): 1:45 minutes

This round was also taken by the Bar Raiser Interview Platform. The interview will start with the System Design question. He asked me to share the screen asked me to create a system design for the E-commerce company Flipkart. How is Flipkart working? What are the database we have to use to support streaming data? I explained each component that are being used to create HLD of E-commerce such as load balancer, caching, proxy server, database, Kafka, Event-driven platform, Sprintgboot, Custom API, Web service, JPA service, AWS cloud I used to take example & explain the components with the use case.

Then he gives one problem statement to write the spark code. Suppose I have streaming data coming from Kafka continuously & loaded into the Delta Lake actual data will be stored in the S3 bucket but metdata will be stored in the Hive Metastore or thrift server. He asked me to build the complete ETL pipeline by writing Kafka code to fetch the data from the event-drive platform which consumes the event every 1 minute of size 100 KB each time & dumps the data into Delta Lake in parquet or JSON format. Then write the data frame code to clean the event whose event id has null user_id & dump the final result into a different zone of the delta lake like the bronze zone.

Finally he asked me to explain the architecture of Kafka and Spark Streaming.

This round basically focussed on System Design, deep knowledge of Networking/database/operating system & ETL Design using Spark & Kafka Streaming Platform

Round 5: Technical Interview 3(Techno-Managerial Round): 1 hour 10 minutes

This interview was taken by the Data Engineering Manager of Meesho. This round lasted for about 1 hour and 10 minutes. I was asked to introduce myself. Then, there is a discussion on the ZS projects that I had worked on my roles & responsibilities in the project. Also, he asked me what are the tech stacks & responsibilities I had when I was working at Morgan Stanley. I explained all the tools that I worked on in Data Engineering such as Databricks, and Snowflake. How I set the ETL pipeline on Databricks by migrating from on-premise service to cloud service Databricks, Azure Cloud with Snowflake Data Warehouse

Now question on ETL Designing & Big Data Concepts (Delta Lake/Data Lakehouse)

What is the difference between Datalakehouse & Delta lake vs data warehouse?
Have you done data compaction? What is delta log vs log files in delta lake
How Delta Lake stores the transaction history in the S3 Bucket
Explain the architecture of Hive Metastore
Write the complete steps to design the Data governance policies how you will implement as if you want to build the data catalog system from scratch?
Write the Custom API to hit the request to the backend server running on Kubernetes or Docker from the frontent application to get customer data example how many orders are placed by the user based on user ID. Database is PostgreSQL or can be a Delta Lake table
Do you know how Presto fetches the data from the data catalog? How does Presto work faster for complex queries?
He asked me to share a screen to create the data model on the ETL Pipeline which takes data from the database & dumps data into the data warehouse Snowflake. Define the schema for sample tables that are used in Morgan Stanley.
He asked about some concepts of Normalisation. He asked me to write an SQL query on SCD-1 or SCD-3 Slowly Changing Dimension
Then he asked questions related to team management & leadership qualities. I was mainly asked questions that were situation-based such as ” How you can overcome challenges faced in the team if your team is not able to cop up with you in solving issues?
He asked me some questions on Pagerduty or the tools for the alerting mechanism
Some questions on the Job Scheduler or SLA you set for the Job. What you will do if the SLA misses the job?
At last, He asked about my achievements. I told him that I was a University topper of the B.tech course. He was very happy with my answers. he asked how soon you could join the Meesho.
Round 6: HR Interview: 45 minutes

This round lasted for about 45 minutes. I was asked about my Big Data project experience, my hobbies, my strengths & weaknesses. He asked about my family background, previous interview experiences that I gave in Amazon, Mastercard, Deutsche Bank, Paytm & other companies, and my ultimate goal in life. At last, He asked me “What is your salary expectation- Most Awaited Question 😀 ” & “What inspires you to join Meesho”.
On the next day, I got positive feedback from HR. Fortunately, I got selected for the SDE-2 Data Engineer position at Meesho.
