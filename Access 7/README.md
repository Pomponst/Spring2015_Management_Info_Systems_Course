# Activity - Access 7 - ABC Staffing and Jewelry
**Part 1:**<br>
You have been hired by ABC Staffing, Inc. as an information specialist. ABC Staffing is one of the fastest growing employment agencies in the New York Metropolitan area. The owner of the company has asked you to design a database management system to manage data on job applicants and staffing agents.
1.	Create a new Access file called ABC Staffing and create the following two tables in it.
2.	Create the Agents table. This table is a listing of all agents hired by ABC Staffing. They provide job search services to applicants. This table includes the following fields:
	1.	Agent ID: A unique ID number associated with each agent.
	2.	The agent’s first name and last name.
	3.	Create a form to enter data for all fields in this table and name the form as Agents Form.
	4.	Make up and enter at least 2 records of data in this table.
3.	Create the Applicants table. This table is a listing of all job applicants to whom the company provides job search services. It includes the following fields:
	1.	Applicant ID: A unique ID number associated with each applicant.
	2.	The applicant’s first name, last name, street, city, state (for the field of state, use a lookup data type; the values of the state field include NY, NJ and CT), and zip code
	3.	Relocation: A Yes/No field indicating whether the applicant is willing to relocate out of the New York Metropolitan area (Yes) or not (No)
	4.	Availability Date: The date when the applicant is available for the new job. For this field, you have to apply a validation rule that the value of this field should be later than March 31, 2015. The validation text should be “The availability date should be later March 31, 2015.”
	5.	Agent ID: The ID number of the agent who serves the applicant (this is the same as Agent ID in the Agents table above)
	6.	Create a form to enter data for all fields in this table and name the form Applicants Form.
	7.	Make up and enter at least 2 records of data in this table.
4.	Create the required relationship incorporating the following business rules: one applicant is served by only one agent, and each agent serves one or more applicants.

**Part 2:**<br>
Download and store the file “Jewelry.mdb” on your laptop. Then open it in Access and create queries for the following. Ensure that your query lists only the fields asked for and nothing else.
1.	List the supplier name, the product name and the product quantity for all suppliers in the state of New York (NY). Order the list in ascending order of supplier name.
2.	List the product name for all products whose quantity is greater than or equal to 7 or whose reorder level is greater than or equal to 4. Order the results in ascending order of product name.
3.	List the product name for all products whose quantity is between 2 and 4 and the reorder level is less than 4. Order the results in ascending order of product name.
4.	What are the maximum, minimum and average reorder levels of all products?
5.	Prompt the user to enter a Supplier ID. Then display a list of product names, descriptions and quantities of all products provided by that supplier. Order the results in ascending order of product name.
6.	For each category, list the total number of products and the total quantity of all products. Order the list in ascending order of category name.
7.	For each product, list the product name, quantity, unit price, and sales amount (sales amount = quantity * unit price). Order the results in descending order of sales amount.
8.	For each product, list the category name, product name, and the percent of the product’s quantity in the total quantity of all products in the product’s category (Hint: you may have to use two queries). The percent should be formatted with % and two decimal places. Order the results in ascending order of category name.

**Part 3:**<br>
In the database that you used for the above queries, create the following reports:
1.	Create a report showing all fields of the Suppliers table in ascending order of Supplier ID.
2.	Create a report showing the supplier name, street, city, state and zip code for all suppliers in the state of New York (NY).
3.	Create a report showing all the products grouped by category name. For each group, display the average Unit Price. For each product, display only the product ID, product name, unit price, and category name. As you are grouping by Category Name, the Category Name will automatically be displayed. Sort by Product ID in ascending order.
