# Activity - Access 2 - Travel Agency and World Travel
**Part 1: Table Design**<br>
Consider a travel agency. The travel agency has several travel consultants, and for each consultant, we have Consultant ID (unique, number, required), First Name (required, max 40 characters), Last Name (required, max 40 characters), Date of Birth, Status (whether the consultant is a part-time or full-time employee), Base Annual Pay, and State in which the consultant does business (2 characters and this has to be one of NJ, NY and PA). Furthermore, when entering data for State, we should be presented with a dropdown list that shows only these three states and any other input should be rejected. Also, Base Annual Pay of any consultant should exceed $10,000.

The travel agency also keeps information on its offices across the country. For each office the travel agency stores Office ID (unique, number, required), Street Address (required, max 50 characters), city (required, max 25 characters), State (required), Zip Code (required), whether the office is in a shopping mall or not, the date on which the office was set up, and the monthly lease fee (currency, required). Each office can hire many consultants, but each consultant has to work at only one office.
1. Create Access file and name it as Travel Agency.
2.	Create the tables necessary to manage the above scenario – use the proper data types and set the correct attributes/properties for each field as implied in the description. 
3.	Ensure that each table has a primary key field.
4.	Create the required relationship(s).
5.	Make up and enter at least 2 rows of data in each table – no field should be left blank in any row.
6.	Create a form to enter data on travel consultants. Save the form as Form1.

**Part 2: Query Design**<br>
Download and store the file “Activity – Access 2 - World Travel” on your computer. Then open it in Access and create the following queries. Ensure that your queries list only the fields asked for and nothing else. Name the queries as “Query1”, “Query2”, etc. to match the query numbers given below.
1.	List Trip ID, Start Date, End Date, Start Location, End Location, and Price for all trips starting at San Diego.
2.	List Trip ID, Start Date, and End Date for all trips that cost more than $10,000 or that do not offer any discount.
3.	List Trip ID, Start Location, and End Location for all trips that end before 11/30/2012 and cost between $5,000 and $10,000.
4.	For each Discount ID, list Discount ID and the percent of the Discount ID for all trips (Hint: you may have to use more than one queries, that is, first, count the total number of trips; second, count the number of trips for each Discount ID; and calculate the percent of each Discount ID for all trips). The percent should be formatted with % and two decimal places.
5.	List Trip ID, Price, and Discounted Price for all trips. Discounted Price is calculated as Price minus Price times Discount Percent, that is, [Price] – [Price] * [Discount Percent] / 100 (Please note that Discount Percent is given in percent).
6.	List Trip ID and Trip Duration (how many days) of international trips. Trip Duration is calculated as End Date minus Start Date plus 1, that is, [End Date] – [Start Date] + 1.
7.	What is the maximum, average, and minimum Price of all trips?
8.	Prompt the user to enter Start Location and End Location. List Trip ID, Start Date, End Date, and Price.

**Part 3: Report Design**
1.	Create a report showing Trip ID, Start Date, End Date, Start Location, and End Location. Show the results in ascending order of Trip ID.
2.	Create a report showing Discount ID, Discount Name, Discount Percent, Trip ID, and Price for all domestic trips. Sort the results in ascending of Discount ID.
3.	Create a report showing Discount ID, Discount Name, Discount Percent, Trip ID, and Price. Group the results by Discount ID and include a summary statistics (average, maximum, and minimum) of Price for each Discount ID.
