# Activity - Access 8 - Physical Plant and DVD Rental
**Part 1:**<br>
A university has many buildings and the university’s physical plant department is planning to start computerizing some of its business processes. They do not yet know much about the potential of databases and want you to build a very simple system just to get a feel for how they can best use a database. 
The university has several buildings and each building has several rooms. For each building you will need to store a building id (primary key, number), building name (max 50 characters), total floor area, the region of campus where the building is located (the region should be one of North, South, East or West) and the date on which the building was inaugurated – all of these fields are required. 
For each room, you need to store, the room number, floor area of the room, the building id of the building to which the room belongs, number of light fixtures in the room, whether or not a fire inspection has been completed for the room, some comments on the room (textual description of the condition of the room when last inspected, max 200 characters) and the date of last inspection – other than the last two fields mentioned, all other fields are “required”.

Do the following based on the above description.
1.	Create an Access database called Physical Plant. 
2.	Create the two tables needed to hold the above information. Pay careful attention to the fields in the tables and the type of data for each field. Create a primary key for each table. Where the value for a field is restricted to a specific set of values, provide a drop-down list with only the allowed values for entering data. Pay attention to whether or not a field is a “required” field, and to the field lengths specified in the above description. Each table must have a primary key.
3.	Create the required relationship between the tables.
4.	Create forms for entering data into the tables.
5.	Enter at least two rows of data for each table. 

**Part 2:**<br>
Download and save the database “DVD Rental” from Blackboard. Use the database file to create the following queries. Please name your queries as “Query 1”, “Query 2”, etc.
1.	List the first name, last name and email address of every customer in NY or NJ.
2.	List the first name and last name of customers who are either in NJ and are active or in PA and are inactive.
3.	Find the total amount and average amount of all payments made so far.
4.	List the customer id, first name and last name of customers and the total dollar value of their rentals (the dollar value of each rental is the charge per day multiplied by the number of days).
5.	List the customer id and the total dollar amount of the payments made by the customer so far.
6.	Use the above two queries (Query 4 and Query 5) to show the customer first name, customer last name and the amount that they owe (total dollar value of their rentals minus the dollar value of the payments they have made so far – do not be concerned if you find that this figure is negative).
7.	Show the total dollar amount of the payments made by customers in a state based on the state code input by the user.
8.	List the film id and the total dollar value of all rentals for that film.

**Part 3:**<br>
Prepare the following reports. Name the reports as “Report 1”, etc.
1.	Prepare a report showing all customers arranged in ascending order of last name and among customers having the same last name, arranged in ascending order of first name. Group your report by state.
2.	Display each customer and show the total dollar amount that they have paid so far.
3.	Prepare a report showing each customer and the total number of times each has rented so far. Arrange the report in descending order of total number of rentals. Show only those customers who have rented more than a certain number of times – this will be input by the user when the report is run.
