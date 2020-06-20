# Activity - Access 9 - ABC Tutors and Reservation
**Part 1:**<br>
You have been hired by ABC Tutors, Inc. as an information specialist. ABC Tutors is one of the fastest growing tutoring service agencies in New Jersey. The owner of the company has asked you to design a database management system to manage data on tutors and students.
1.	Create a new Access file called ABC Tutors and create the following two tables in it.
2.	Create the Tutors table. This table is a listing of all tutors hired by ABC Tutors. They provide tutoring lessons to students. This table includes the following fields:
	1.	Tutor ID: A unique field associated with each tutor
	2.	The tutor’s first name and last name
	3.	The tutor’s education (for this field, use a lookup data type; the values of the education field include bachelor’s degree, master’s degree, and doctorate)
	4.	Travel: A Yes/No field indicating whether the tutor is willing to travel to the student’s place
	5.	Create a form to enter data for all fields in this table and name the form as Tutors Form.
	6.	Make up and enter at least 2 records of data in this table.
3.	Create the Students table. This table is a listing of all students to whom the company provides tutoring services. It includes the following fields:
	1.	Student ID: A unique field associated with each student
	2.	The student’s first name, last name, street, city, state, and zip code
	3.	Start Date: The date when the student starts to take tutoring lessons from a tutor. For this field, you have to apply a validation rule that the value of this field should be later than March 31, 2015. The validation text should be “The start date should be later March 31, 2015.”
	4.	Tutor ID: The unique field of the agent who provides tutoring lessons to the student (this is the same as Tutor ID in the Tutors table above)
	5.	Create a form to enter data for all fields in this table and name the form Students Form.
	6.	Make up and enter at least 2 records of data in this table.
4.	Create the required relationship incorporating the following business rules: one student is tutored by only one tutor, and each tutor provides tutoring lessons to one or more students.

**Part 2:**<br>
Download and store the file “Reservation.mdb” on your laptop. Then open it in Access and create queries for the following. Ensure that your query lists only the fields asked for and nothing else. Name the queries with the word to the left of the query, that is, Query1, Query2, and so on.
1.	List the guest first name, guest last name, reservation start date, and reservation end date for all guests in the state of Illinois (IL). Order the list in ascending order of guest last name.
2.	List the property name, location, and country for all properties whose nightly rate is less than $2,000 and number of bedrooms is more than 5. Order the results in ascending order of property name. 
3.	List the property name, location, and country for all properties whose number of bedrooms is less than 4 or number of sleeps is between 4 and 7. Order the results in ascending order of property name. 
4.	What are the maximum, minimum and average nightly rates of all properties?
5.	Prompt the user to enter a guest ID. Then display a list of reservation ID, reservation start date, and reservation end date of all reservations for that guest ID. Order the results in ascending order of reservation ID.
6.	For each property, list the total number of reservations and the total number of days reserved. “Number of days reserved” is calculated as “reservation end date” minus “reservation start date” plus 1, that is, [End Date] - [Start Date] + 1. Order the list in ascending order of property name. 
7.	For each reservation, list the reservation ID, guest ID, property ID, and cost per person (cost per person = rental rate / people). Order the results in descending order of cost per person. The cost per person should be formatted with $ and two decimal places.
8.	For each property, list the property name, country, and percent of all reservations for the property out of all reservations in the respective country (Hint: you may have to use more than one query). The percent should be formatted with % and two decimal places. Order the results first in ascending order of country and then within each country in ascending order of property name. 

**Part 3:**<br>
In the database that you used for the above queries, create the following reports:
1.	Create a report showing all fields of the guest table in ascending order of guest ID. 
2.	Create a report showing the property name, location and country for all properties whose type is castle. 
3.	Create a report showing all the reservations grouped by property name. For each property, display the average rental rate. For each reservation, display only the property name, reservation ID, and rental rate. As you are grouping by the property name, the property name will automatically be displayed. Sort by reservation ID in ascending order.
