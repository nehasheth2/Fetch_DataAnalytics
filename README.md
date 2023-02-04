# Fetch Rewards Coding Exercise - Data Analytics Internship
:space_invader: :robot: This github repository contains the data, ER diagram, SQL queries, Tableau workbook and an interactive Python notebook for the Data Analytics Assignment. The final deliverale to the non-technical stakeholder would be the Tableau dashboard, capturing insightful discoveries about the data, as well as the word document that shows all the correlations, trends and nuances of the data captured through the years using the Python program.

## Dataset
- Brands : consists of name of brand, marketing description, barcode information, unique ID and related brands.
- Receipt_items : consists of item-specific information including price of each item, brand information, date/time, rewards group  and so on.
- Receipts : consists of point-of-sale data for various items on a receipt including store information, quantity purchased, price of sale, the date/time of the sale, rewards receipt status and whether the transaction needs to be reviewed by Fetch.
- Users : consists of data of users such as gender, state, rewards login information and so on.

## Entity-Relationship Diagram -
![This is an image](/ERD.png)

This ER diagram shows how brands are related to the items present in receipts and how users only interact with the point-of-sale data. Each item has a fixed final price which is reflected on the point-of-sale receipt or bill. The reward points earned for each item is also in the receipt_items data and is reflected on the point of sale as per the quantity of items purchased.

## SQL Queries

The second part of the assignment requires SQL queries to answer the following questions. 
The docx file attached in this repo addresses each of these questions. The link below also has the same queries incase the docx file is not accessible.
Note that all 5 questions are answered using these queries.

[SQL Queries](https://docs.google.com/document/d/1wffSZmA4IuWUS7lP0Ca1vxQZ66rtqvkj/edit?usp=sharing&ouid=108480454610486985319&rtpof=true&sd=true)

- Which brand saw the most dollars spent in the month of June?
- Which user spent the most money in the month of August?
- What user bought the most expensive item?
- What is the name of the most expensive item purchased?
- How many users scanned in each month?

## Data Observations

Using this data, I have created an interesting Tableau dashboard to present to the stakeholder. The workbook can be found here -
[]

Along with that, some Python EDA and visual analysis is performed using the interactive Python notebook. 

