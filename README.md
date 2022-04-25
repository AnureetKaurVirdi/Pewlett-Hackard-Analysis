# Pewlett-Hackard-Analysis

_An SQL HR-Department Analysis_
## Project Overview:

The purpose of this analysis is to help prepare, a company with several thousand employees, Pewlett-Hackard, for it upcoming "silver tsunami." a largr number of their employees will begin retiring at a rapid rate in the upcoming years. And the company wants to be prepared with retirement packages, hiring process for the open positions and training for those positions. This project focuses on the following:

1. Idetifying the retiring employees by their title.
2. Determining the sumn of retiring employees grouped by title. 
3. Identify the employees eligible for participation in the mentorship program. 

## Results

### Deliverable 1: The Number of Retiring Employees by Title 

#### The list of retiring employees

1. The table includes employee number, first name, last name, title, from-date and to-date. 
2. The query returned 10,229 rows.
3. The table displays a list of employees who is going to retire in the next few years.
4. The list is long and extensive, yet at-a-glance analysis gives us some insights about the query. Some employees appear more than once due to change of title during their career at Pewlett-Hackard.

#### The number of retiring employees grouped by title

1. The table includes employees’ titles and their sum.
2. The query returns a cohesive table with 7 rows.
3. We can quickly see how many employees with certain title will retire in the next few years.

#### The list of retiring employees without duplicates

1. The table includes employee number, first name, last name, title, from-date and to-date.
2. The query returns 10,333 rows.
3. The table displays a list of employees who are going to retire in the next few years.
4. In the table each employee is listed only once, by her or his most recent title.

### Deliverable 2: The Employees Eligible for the Mentorship Program

1. The table contains employee number, first name, last name, birth date, from date, to date and title.
2. The query returns 32,714 rows.
3. The table displays a list of employees who is eligible for the mentorship program.

## Summary

Reports above give a good insight about the number of the employees that are about to retire and hold specific title. However, I believe that additional break down per department will be beneficial for the company. In this case headquarters can see what to expect in each department separately. 

### How many roles will need to be filled as the "silver tsunami" begins to make an impact? 

The table retirement titles contains all the information about the employees that are about to retire in the next four years. To get the number of positions that will be open in next four years an additional query can be ran that breaks down how many staff will retire per department. 

### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett-Hackard employees?

To ensure that are enough qualified staff for training at Pewlett-Hackard a query with additional filter, that returns only employees on higher positions, assuming that those are qualified as mentors can be ran. With the command "WHERE ut.title IN ('Senior Engineer', 'Senior Staff', 'Technique Leader', 'Manager')" the results include only staff on higher positions. 
