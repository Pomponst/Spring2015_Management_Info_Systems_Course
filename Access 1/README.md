# Activity - Access 1 - Print Shop
**Case:** A print shop that specializes in graphic arts and large print jobs needs to maintain information on its jobs and customers. The database it will use consists of two tables. The Jobs table contains data on jobs for which the print shop has either contracted or has completed for each customer. The Customer table contains pertinent data about the print shop’s customers.

**Instructions:** The data and structure for the Jobs table are shown in tables 1 and 2. The data and structure for the Customer table are shown in tables 3 and 4. Save your works in an Access file called “Access – Print Shop”.

**Part 1: Creating the Print Shop Database**
1.	Create a new database to store all the tables related to the print shop data. Call the database Access Homework Case.
2.	Create the Jobs table using the structure shown in Table 1. Make the Job ID the primary key, no duplicates. Use the name Jobs for the table.
3.	Add the data shown in Table 2 to the Jobs table.
4.	Create the Customer table using the structure shown in Table 3. Make the Customer ID the primary key, no duplicates. Use the name Customer for the table.
5.	Add the data shown in Table 4.

*Table 1. Structure of Jobs table*
|Field Name|Data Type|Field Size|Primary Key?|Description|
|----------|---------|----------|------------|-----------|
|Job ID|Text|4|Yes|Job number (primary key)|
|Customer ID|Text|3||Customer ID number|
|Job Description|Text|25||General job description|
|Job Status|Text|1||Status of complete (C) or incomplete (I)|
|Due Date|Date/Time|||Date job is to be completed|
|Quote|Currency|||Customer’s cost for job|

*Table 2. Data for Jobs table*
|Job ID|Customer ID|Job Description|Job Status|Due Date|Quote|
|------|-----------|---------------|----------|--------|-----|
|P234|COM|Brochure Print|I|41455|1200|
|P435|SPO|Coupons|C|41406|1685|
|A342|SPO|Ad Layout|I|41538|300|
|A564|PET|Ad Layout|C|41379|600|
|P125|TRA|Special Flyer|I|41440|1400|
|P854|MEL|Ad Layout|C|41334|957|
|A585|PET|Brochure Design|C|41360|200|
|A448|COM|Brochure Design|I|41400|360|
|A687|MEL|Ad Layout|I|41477|300|
|P658|OTH|Place Mats|I|41547|1500|
|A369|OTH|Place Mat Design|I|41451|150|
|A227|COM|Ad Layout|C|41381|410|
|P593|SPO|Mailer|C|41476|560|
|A309|MEL|Coupons|I|41502|320|
|A661|PET|Ad Design|C|41521|980|
|P293|MEL|Ad Design|C|41498|890|
|A419|COM|Ad Design|I|41538|790|
|P871|OTH|Coupons|I|41559|480|
|P411|MEL|Mailer|C|41394|390|
|A821|COM|Mailer|I|41563|285|

*Table 3. Structure of Customer table*
|Field Name|Data Type|Field Size|Primary Key?|Description|
|----------|---------|----------|------------|-----------|
|Customer ID|Text|3|Yes|Customer number (primary key)|
|Customer Name|Text|20||Customer company name|
|Contact Person|Text|20||Contact person at company|
|Phone|Text|8||Contact phone number|

*Table 4. Data for Customer table*
|Customer ID|Customer_Name|Contact Person|Phone|
|-----------|-------------|--------------|-----|
|COM|Computers R Us|Diane Lawrence|455-3451|
|SPO|Sports Emporium|Marion Shellhouse|455-6639|
|PET|Pet Shop Boys|Bonnie York|456-7877|
|TRA|Tracks Tapes & CDs|Carrie Rogers|415-2258|
|MEL|Mel’s Pharmacy|Mel Radbell|785-9111|
|OTH|Othello’s Restaurant|Ranjan Said|555-8890|

**Part 2: Querying the Print Shop Database**<br>
Using the Jobs table,
1.	Display all the records in the table. Save the query result as Query01. 
2.	Display the Job ID, Customer ID, and Job Status for all records in the table. Save the result as Query02.
3.	Display the Job ID, Customer ID, Job Description, and Quote for all orders with a Job Status of C (type C as the criterion for the Job Status field). Save the result as Query03.
4.	Display the Job ID, Customer ID, Job Status, and Due Date for all orders with a Due Date after June 1, 1996 (type >06/01/13 as the criterion for the Due Date field. Save the result as Query04. 
5.	Display the Job ID, Customer ID, Job Status, and Quote for all orders with a Job Status of I (type I as the criterion for the Job Status field) and a Quote of more than $1000 (type >1000 as the criterion for the Quote field. Save the result as Query05.
6.	Display the Job ID, Customer ID, Job Status, and Due Date for all orders with a Job ID that begins with P (type P* as the criterion for the Job ID field). Save the result as Query06.
7.	Display the Job ID, Customer ID, Due Date, and Quote for all orders with a Due Date before March 30, 1996 or a Quote of less than $500. Save the result as Query07.
8.	Display the Job ID, Customer ID, Job Description, and Quote for all orders with a Job Description of Ad Layout or a Quote greater than $500. Save the result as Query08.
9.	Display the Job ID, Customer ID, Job Status, and Due Date from the Jobs table sorted (ascending) by Customer ID. Save the result as Query09.
10.	Display all the fields in the Jobs table sorted by Job ID within Customer ID. Save the result as Query10. Make sure that the Customer ID field (the first key on which to sort data) comes first and then the Job ID field.
11.	Using both the Jobs and Customer tables, include the fields Job ID, Customer ID, Job Status, Customer Name, and Phone in the QBE grid. Display the result and save as Query11.
12.	Restrict the records retrieved in task 11 to only jobs with a Job Status of I. Display the result and save as Query12.

**Part 3: Maintaining the Print Shop Database**<br>
Using the Jobs table,
1.	Display the Design window for Jobs table, and change the field width of Job Description to 20.
2.	Add a field called Quote Date between the Due Date and Quote fields. Define the field as Date/Time. This field will contain the date the quote is due. (Click the left mouse button to select the record selector for the Quote field and then press the INSERT key to insert a blank row.)
3.	Save these changes, and display the Jobs table in Datasheet view.
4.	Change the Job Description for Job ID A564 from Ad Layout to Ad Design.
5.	Order/sort the records by the Job ID.
6.	Save the table.
7.	Create a form for the Jobs table. Use the name Jobs Form.
8.	Using Form view, add the following record to the Jobs table:
	1. P654, TRA, Brochure Print, I, 12/1/13, 10/15/13, 1750
9.	Using this form, locate the jobs with Job IDs of A342 and P658. Change the I to C in the Job Status fields for both records.
10.	Change to Datasheet view, and save the table.
11.	Create a new query for the Jobs table. Using the query, delete the records whose Job Status is C and Due Date is before April 1, 1996. Save the query as Query13. Close the query without saving it.
12.	Save the Jobs table.
13.	Close the database, and exit Access.
