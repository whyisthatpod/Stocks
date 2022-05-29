# Stocks
Project: Watching the Stock Market
This project will take you off-platform and get you started in your own developer environment! Never done that before? Not to worry - we’ve shared some resources to help you down below. This project can be completed entirely on your own - or, you can join the Codecademy Discord 117 and find someone to work with!

This project is broken down into key questions that your client or company is looking to answer. As a data scientist, you’ll often become a resource to help businesses answer the key questions about the efficacy of existing or potential strategies & projects.

Overview
Objective
You are asked by a company to help them make more informed decisions on investments. To start, you will be watching the stock market, collecting data, and identifying trends!

Pre-requisites
In order to complete this project, we suggest that you have familiarity with the content in the following courses or lessons on the Codecademy platform:

What is a Relational Database Management System? 786
Manipulation 402
Queries 254
Suggested Technologies
Depending on where you are on your Path, there may be multiple technology options you can use to complete this project - we suggest the following:

DB Browser for SQLite 2.8k
Project Tasks
Get started - hosting your project
DB Browser for SQLite 2.8k is a visual tool for working with SQLite databases. Follow the link to download the application for your computer.



SQLite can store an entire database in a single file, which usually has a .sqlite or .db extension. To open a database, select Open Database at the top of the window and browse for the file. Alternatively, you can choose to create a New Database by saving a file with the .sqlite or .db extension.
To import data from a CSV file into a table, select “File > Import > Table from CSV file…” and browse for the CSV file. (Note: All fields imported from the CSV file will have a data type of TEXT. Be sure to convert fields to numeric type as needed. See here 306 for how to do that.)


There are several tabs near the top of the window for working with the data:

Database Structure: View the tables in your database and the columns they contain.
Browse Data: Browse the data for each table.
Execute SQL: Write and execute SQL queries.
Basic Requirements
Let’s break this project down into a couple different parts.

Manipulation: Collect data on your pick of 5 stocks 1.3k.

Create a table called stocks, where you will be inserting your data.
Hint: See here 663 for a review of the CREATE TABLE syntax. What data type 597 should each field be?
The stocks table should have a column for symbol, name, datetime, and price.
Collect your data! Choose 3 times throughout the day to document the price of each stock and continue for at least 1 week. You can do this moving forward, or just take a retroactive look at the stock market ﻿﻿by taking data historically from regular intervals (e.g. the first of the month for the last six months).
Hint: See here 393 for a review of the INSERT INTO syntax. When inserting the datetime, use the standard format ‘yyyy-mm-dd hh:mm:ss’. Use the strftime() 378 function to help you get the datetime of ‘now’.
Queries: Perform basic analysis on the data and identify trends.

What are the distinct stocks in the table?
Query all data for a single stock. Do you notice any overall trends?
Which rows have a price above 100? between 40 to 50, etc?
Sort the table by price. What are the minimum and maximum prices?
Additional Challenges
Intermediate Challenge

Explore using aggregate functions to look at key statistics about the data (e.g., min, max, average).
Group the data by stock and repeat. How do the stocks compare to each other?
Group the data by day or hour of day. Does day of week or time of day impact prices?
Which of the rows have a price greater than the average of all prices in the dataset?
Advanced Challenge

In addition to the built-in aggregate functions, explore ways to calculate other key statistics about the data, such as the median or variance.
Hint: See here 138 and here 71 for possible solutions.
Let’s refactor the data into 2 tables - stock_info to store general info about the stock itself (ie. symbol, name) and stock_prices to store the collected data on price (ie. symbol, datetime, price).
Hint: You can use the SQL CREATE TABLE AS statement to create a table by copying the columns of an existing table. Don’t forget to also drop certain columns from the original table and rename it.
Now, we do not need to repeat both symbol and name for each row of price data. Instead, join the 2 tables in order to view more information on the stock with each row of price.
Add more variables to the stock_info table and update the data (e.g., sector, industry, etc).
Resources & Support
Project-specific resources
SQLite Data Types 597
SQLite Date and Time Functions 63
SQLite strftime() Function 378
SQLite Documentation 36
SQLite Tutorial 80
General Resources
How to get set-up for coding on your computer 241
What is a Relational Database Management System? 25
What you need to know about Git, GitHub & Coding in Teams
How developer teams work 19
First steps in tackling a group project 11
Resource on writing pseudocode 17 to get started with off-platform projects
Community Support
Looking for additional help or someone to work with (or somewhere to brag about your finished project)? Join our Discord 117 to meet other learners like yourself!

Collaborate with other learners on data collection! Then, join the datasets together for more interesting analysis.
Each learner can collect data on different stocks for a larger sample of stocks.
Each learner can collect data on same 5 stocks, but at different points throughout the day in order to spot potential daily trends.

https://discuss.codecademy.com/t/data-science-independent-project-1-watching-the-stock-market/419943
