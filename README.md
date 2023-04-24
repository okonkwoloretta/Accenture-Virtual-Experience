# Accenture Virtual Experience Program on Forage

## Project Client: Social Buzz

## Task 1: Project Understanding
Understanding the problem of the client is key and your role as a data analyst.
I gained the following skills after completing task 1
teamwork, strategy, project planning

## Task 2: Data Cleaning & Modeling
To make sure I am using the right data to answer the business questions I followed these steps:
1.	Requirements gathering
2.	Data cleaning
3.	Data modeling

Reasons for my selection:
•	The brief carefully states that the client wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”.
•	As explained in the data model, popularity is quantified by the “Score” given to each reaction type.
•	I need data showing the content ID, category, content type, reaction type, and reaction score.
•	So, to figure out popularity, I have to add up which content categories have the largest score.

## Data Cleaning
Data cleaning is a common and very important task when working with data.

First: import the 3 data sets into Excel

![reactiontype](https://user-images.githubusercontent.com/116097143/234044017-b7bf9ec2-40c4-4a9b-a5ff-2ed5f1335f32.png)
![reaction](https://user-images.githubusercontent.com/116097143/234044080-77f116d8-f21e-4bc6-9a52-bcbbcabb528c.png)
![content](https://user-images.githubusercontent.com/116097143/234044139-5858bfe9-915c-46e9-a4b5-e2293a794195.png)

Second: Clean the data by:
•	removing rows that have values which are missing,
•	changing the data type of some values within a column, and
•	removing columns which are not relevant to this task.

![cleaned reaction ](https://user-images.githubusercontent.com/116097143/234046325-b5ad2421-a435-4b57-8c8d-dba06fbf64d1.png)
![cleaned content](https://user-images.githubusercontent.com/116097143/234046365-012fc985-929a-4357-b79b-1c1361957e43.png)

## Data Modeling
Now I want to figure out the top 5 categories. To complete my data modelling
I created a final data set by merging my 3 tables together.
I used the Reaction table as my base table, join the relevant columns from my Content data set, and then the Reaction Types data set, with the help of  “VLookUp” formula.

![reaction merged](https://user-images.githubusercontent.com/116097143/234047690-ecfe96d9-a8b7-44e3-a1c5-f0104d670864.png)
 
To Figure out the Top 5 performing categories
I added up the total scores for each category, using the “Sum If” formula

![Top cat](https://user-images.githubusercontent.com/116097143/234048662-f7486a72-65ed-4018-9b11-c7bbb7513810.png)

## The top 5 categories

![top 5 cat](https://user-images.githubusercontent.com/116097143/234048737-8ee73076-f92d-4ed5-b6cb-43c52c154b46.png)

By completing this task, I gained the following skills: Data understanding, Data modeling

## Task 3: Data Visualization & Storytelling

•	How many unique categories are there?
•	How many reactions are there to the most popular category?
•	What was the month with the most posts?

[Data Analytics template - Task 3_final.pptx](https://github.com/okonkwoloretta/Accenture-Virtual-Experience/files/11312229/Data.Analytics.template.-.Task.3_final.pptx)

created a powerpoint presentation to answer business questions and give recommendations 

By completing this task, I gained the following skills: Data analysis, storytelling, data visualization

## Task 4: Present to the Client
I did a video presentation to share my insight and recommendations to clients.

By completing this task, I gained the following skills:
Presentations
Communication
Public Speaking

Thank you.
