# Data_Engineering
All the codes,Articles and resources about Data Engineering


Roadmap to Data Engineering.

Hey fellow Devs,

I recently posted in this sub for some advice about a job switch, but got a lot of queries and DMs about how I got into Data Engineering, how to get better and go from entry level to senior position or from Data Analyst to Data Engineer [DE].

I'm working as a Senior Data Engineer in a Unicorn Startup in India.

Trying to give back to the community from my experience in Data Engineering since 2019. Still surprised that not many are aware about what actually are the roles, the expectations from Data Engineers are. Most of the stuff is available online, videos from many youtubers, still posted it for people who might not be aware! :)

Will answer FAQs about Data Engineering. Feel free to correct or improvise.

Warning: This is going to be a long post.

> DE means Data Engineering


I. As a fresher, I'm interested in Data Engineering, but how to get a job in this domain?

A. Getting a job directly as a full-time DE is pretty tough. Try to apply for DE internships and maybe it will get converted to full-time or with that experience try to apply for Associate / Junior DE positions. Build a network on Linkedin with many Data Engineers and connect with them about their experience.


2. What are the required skill-sets to become a DE?

A. From my experience companies expect you to be good at any one language

Python, Java or Scala

Strong SQL skills

Data warehousing

Spark

Cloud experience - AWS/Azure/GCP [good to atleast have an idea on how to spin up a cluster in any cloud vendor, setting up Network rules, firewall, etc.]


3. Is DE in demand, is it better than Data Science?

A. Even though all the hype on the internet is for Data Scientists, the role of Data Engineer is equally crucial and critical for companies to enable Data Scientists.

Even the pay is lucrative!

Salaries may vary, but mostly ranges look like this

Entry level DE - 4 to 10 LPA

2 - 4 years - 12 to 30 LPA

4 - 7 years - 25 - 60+ LPA

How do the roles differ, Data Engineer vs Data Scientist vs Data Analyst

A. My understanding - In the Data ecosystem

Data Engineer - Process starts here, collecting, cleaning and transforming, ingesting data into Data warehouses or datalakes.

Data Scientist - With the collected data in DW/DL, understand business logic and build useful data science techniques / ML models to identify key patterns, insights that can drive revenue.

3. Data Analyst - Final part in process, Visualize the insights from Data Scientists using BI tools like Tableau, Looker, etc.


3. How to prepare for DE interviews, Most commonly asked interview questions?


NOTE: In most companies, even Data Engineers are expected to be strong in DSA, since first rounds can be OA tests like Hackerrank and F2F Coding rounds before you can enter technical rounds about topics mentioned below. So, still need to Grind Leetcode to some extent!

That being said, there are still companies that focus mostly on SQL, Spark for interviews and pay lesser attention to coding skills.


After attending close to 40 interviews in last 4 years, the most asked interview questions for 0-3 years of experience were mostly on the following.

Must have knowledge on these concepts to crack any DE interview:

I. SQL

Aggregate functions - AVG, MIN, MAX, etc.

Joins - important! types of joins and their output.

Window functions - Ranking functions, LAG, LEAD

what is <following> how do they work, how to create this and why is it used, pros and cons for the following:

CTEs

Views, Materialized views

Index - also types of indexes, index behind the scenes.

Partitioning - types of partitioning

Normalization / Denormalization - rarely asked but important


2. Data Warehousing (DW) and ETL

Star vs Snowflake Schema

DB vs DW vs Data lake, when to use appropriately

Choosing Columnar vs row oriented Databases

Facts, Dimensions - understanding, examples

Steps to implement a Data warehouse (for example in Bigquery)

Best practices for DW, reporting

Slowly changing dimensions

Handling duplicate records, inconsistencies in data.

Understanding ETL vs ELT process, data cleaning, ingestion techniques.


3. Spark

Understading Architecture

YARN basics

Sparkcontext, session, worker, task, job, stage, etc

Spark dataframes, actions, transformations, reading and writing data, specifying schema options

Repartioning vs Coalesce

Partioning

Handling OOM error in spark

Broadcast variables, broadcast joins

Best practices of Spark, best tuning practices

Different persisting strategies in spark


Cloud experience

Not much questions but it is vital to have an idea on different big data tools and services available in any one Cloud platform and their use cases.

Most commonly used services in Cloud for Data systems

AWS - S3, Redshift, Glue, RDS

GCP - Cloud Storage, Bigquery, CloudSQL, Dataflow [for streaming]

Linux skills - I think this is also a very important skill and a basic requirement

Other skills to learn to become a better a niche Data Engineer, if have the above mentioned topics covered, check these out:

Orchestration tool - Airflow [slowly becoming a must have skill]

Streaming data - Spark Streaming / Flink

Pubsub systems like Kafka

NoSQL databases - MongoDB, Elasticsearch, Cassandra, etc.

System Design for Big Data



Resources:

Datacamp is one of my most favorite platforms. It has skill tracks for Data Engineering, Python, SQL, Shell, Spark, etc.

https://www.datacamp.com/tracks/data-engineer-with-python

https://www.datacamp.com/tracks/big-data-with-pyspark


I would highly recommend this but this is a paid platform though :(

Feel free to explore Youtube, Coursera, Udemy for specific concepts / courses based on the topics mentioned!


if you are a student, use your college ID and activate Github Student developer program, get free access to datacamp for 3 months!

Other resources I used to prep:

https://dataengineering.wiki/


Orielly books - for any topic, check reviews, most of them are available as PDFs in github.

SQL - pgexercises.com, data Lemur, Ankit Bansal on Youtube, hackerrank, Leetcode

Spark - Spark by examples, Datacamp, ChatGPT recently :P, to understand concepts with amazing analogies.

DWH - Ralph Kimball book

Notable YT channels: Ankit Bansal for SQL

Big data folks on Linkedin : Shashank Mishra, Seattle Data Guy, Zach Wilson


Data Engineering is gaining more importance everyday. Upskill yourselves and join the ride!

Feel free to correct / add on, ping me for any queries.

Cheers!
