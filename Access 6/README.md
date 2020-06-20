# Activity - Access 6 - ABC Cormpany and Library
**Part 1:**<br>
You have been hired by ABC Company to design a database that manages data on its employees.  Each employee has a unique **employee ID** (number), an **employee name** (maximum of 30 characters), **Department number** (number), the date they were hired, and their salary. For the salary, be sure that it is greater than 0. If not, display an appropriate error message. They also want to know if the employee has a college degree.

For each Department, there is a **unique Department number** (number), **Department Name** and **city where the department is located**.  For the city, limit the choices to Newark, Chicago, Dallas and Detroit.
1. Create a database named ABC Company. In this database, create the tables necessary to manage the above scenario – use the proper data types and also set the correct attributes for each field as implied in the description. Fields in bold are required. If the data for a field comes from a list of possible values, allow the user to select from a list when entering the data. For each table, be sure to specify a key field.
2.	Create the required relationship(s).
3.	Enter at least 2 rows of data in each table.
4.	Create forms to enter data for items in each table.

**Part 2:**<br>
Download and store the file “library.accdb” on your laptop. Then open it in Access and create queries for the following. Ensure that your query lists only the fields asked for and nothing else. Name the queries the word to the left of the query. That is Query 1, Query 2,….
1.	For each book whose CostPerCopy is greater than $45.00, display the book’s ISBN, Category and CostPerCopy. Sort by CostPerCopy in descending order.
2.	Display books whose purchasing cost is greater than $300.00. Purchasing cost is defined as CostPerCopy times Copies of the book. For books that meet the criteria, display the Title, CostPerCopy, PagesPerBook and the purchasing cost. Be sure that purchasing cost has a suitable heading when the query is displayed.
3.	For all the books in the library, display the total number of Copies and the maximum CostPerCopy (round to 1 decimal place).
4.	For each category, display the category, the minimum number of PagesPerBook (zero decimal places) of books in that category and the average CostPerCopy of books in that category. For example, Reference books have a minimum number of pages of 100 and the average cost in this category is $22.50.
5.	Prompt the user for a Category. For each book in that Category display the book’s Category, ISBN, Title, and Publisher for that Category.
6.	Display the Title, Budget and the ISBN for all books that have the letters ball in its title.
7.	Display any book whose Category is Non-Fiction and number of Copies is greater than 7 or whose Category is Mystery and PagesPerBook is greater than 500. For each book that meet the criteria, display the Title, Copies, PagesPerBook , Category and the total number of pages. The total number of pages is defined as Copies times PagesPerBook.  Sort in descending order by total pages.
8.	For each book, display the Title, CostperCopy, Copies, Category and the percent of the total cost for all books in the book’s category. Total cost is equal to the CostPerCopy times Copies. For example, if the total cost of a Non-Fiction book is $25 and the total cost of all the other Non-Fiction books is $75, then the percent of total cost should show 25%. The percent of the total cost should be formatted as a percentage (2 decimals) with a suitable heading. 

**Part 3:**<br>
Create Reports from the library database that does the following:
1.	Create a report showing the Copies and Title for each book. Display the report in ascending order of Copies.
2.	Create a report showing all the books whose CostPerCopy is greater than $21. Display the Category, Title and Budget.  Sort by CostPerCopy in descending order.
3.	Create a report showing all the books grouped by Category. For each group, display the total PagesPerBook. For each book, display only the ISBN, PagesPerBook and Category. As you are grouping by Category, the Category name will automatically be displayed. Sort by ISBN in ascending order.
