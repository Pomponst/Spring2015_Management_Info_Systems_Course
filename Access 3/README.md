# Activity - Access 3 - Ticket Agency and Concerts
**Part 1: Table Design**<br>
Consider a concert ticket agency. The agency maintains the following three tables in its database system: Bands, Venues, and Bookings.

Bands table contains the following fields: Band ID (unique, number), Band Name, and Genre (Country, Heavy metal, Jazz, Opera, Pop, Rap, Rock). 

Venue table contains the following fields: Venue ID (unique, number), Venue Name, Location, Seats (number of seats), Parking (Yes/No), and Public Transportation (Yes/No).

Bookings table contains the following fields: Booking ID (unique, number), Band ID, Venue ID, Date, and Nights (number of nights).

Each band can perform at many venues and each venue can be used by many bands at different times.
1.	Create Access file and name it as Ticket Agency.
2.	Create three tables necessary to manage the above scenario – use the proper data types and set the correct attributes/properties for each field as implied in the description. 
3.	Ensure that each table has a primary key field.
4.	Create the required relationship(s).
5.	Make up and enter at least 2 rows of data in each table – no field should be left blank in any row.
6.	Create a form to enter data on Venues and save the form as Form1.

**Part 2: Query Design**<br>
Download and store the file “Activity – Access 3 - Concerts” on your computer. Then open it in Access and create the following queries. Ensure that your queries list only the fields asked for and nothing else. Name the queries as “Query1”, “Query2”, etc. to match the query numbers given below.
1.	List Band ID, Band Name, Booking ID, Date, and Nights for all bands whose Genre is Pop. Show the results by the ascending order of Band ID and then Date.
2.	List Venue ID, Venue Name, Location, and Seats only for the venues where both parking and public transportation is available.
3.	List Booking ID, Band Name, Venue Name, Date, and Nights for the bookings before 6/30/2012 or with more than 2 nights.
4.	For each venue, list Venue ID, Venue Name, and the percent of the venue for all bookings (Hint: you may have to use more than one queries, that is, first, count the total number of bookings; second, count the number of bookings for each venue; and calculate the percent of each venue for all bookings). The percent should be formatted with % and two decimal places.
5.	List Booking ID, Band Name, Venue Name, and Discounted Ticket Price for all bookings. Discounted Ticket Price is calculated as Ticket Price minus Ticket Price times Discount Percent (20%), that is, [Ticket Price]–[Ticket Price]*0.2
6.	For genre, list the total number of bookings and the average ticket price within the genre. Order the list in ascending order of genre.
7.	What is the maximum, average, and minimum number of seats of all venues?
8.	Prompt the user to enter Band Name and Venue Name. List Band Name, Venue Name, Date, and Ticket Price.

**Part 3: Report Design**
1.	Create a report showing Band ID, Band Name, Venue ID, Venue Name, Date, and Nights. Show the results in ascending order of Band ID.
2.	Create a report showing Band Name, Venue Name, Date, Nights, and Ticket Price for the bands whose genre is Pop or Rock. Sort the results in ascending of Band Name.
3.	Create a report showing Booking ID, Band Name, Venue Name, Date, and Ticket Price. Group the results by venue and include a summary statistics (average, maximum, and minimum) of Ticket Price for each venue.
