## Pewlett-Hackard-Analysis

Using SQL- Relational Databases

## Purpose of our project

The purpose of this project is to determine the number of retiring employees by title and identify which employees are eligible to participate in the mentorship program. The retiring employees by title information shows the titles of all employees born between January, 1 1952 and December, 31 1955. First and foremost, a query was created, and this query retrieved emp_no, first_name and last_name columns from the employees table and retrieved the title,from_date and to_date columns of the titles table in our pewlett-hackard query. We then joined both of these tables on the primary keys,filtered the data by birth_date and put the information into a new table. For the next two parts of deliverable 1 we created a unique_titles table to find the first occurence of the emp_no in our new table by using the DISTINCT ON function and for the last part of the deliverable we did ORDER BY COUNT to reveal the total number of each title from the unique_titles table we created earlier. In the second deliverable, we created a query that retrieved columns from our employees and dept_emp table, filtered data on current employees born in 1965 and then ordered the table by emp_no.

## The Results

- With the retirment_titles table reveals all employees eligible for retirement and how long they have worked at each position over the course of their careers.

- The unique_titles table we created shows the most recent title for employees who are of retirment age.

- The retiring_titles table shows that 64% (57,668/90,398 = 64%) of the employees of retirement age have senior titles.
<img width="523" alt="Screen Shot 2020-09-05 at 12 06 58 PM" src="https://user-images.githubusercontent.com/67278193/92309182-4bc89180-ef71-11ea-83f5-f35a59b280d8.png">

- The final part of the project shows mentorship eligibility, if we take a look at the head of the new csv file - We can see that most of these employees have senior titles.

<img width="636" alt="Screen Shot 2020-09-05 at 12 12 13 PM" src="https://user-images.githubusercontent.com/67278193/92309185-4e2aeb80-ef71-11ea-992e-759ce1b3971c.png">

# Conclusion

Knowing that 63 % of the workforce is either eligible for retirement or mentorship. Therefore, there is every likelihood that many vacant positions would be opened, and need to be filled by the new employeesthe in the next 5-10 years. If this is the case, there may not be enough people in the workforce to take care of the tasks or even come close to the amount of experience to fill these roles so quickly, however, what I think this company can do is to try and learn what these employees did to be so successful and having such long lasting careers in order to continue the tradition for future employees. I think, most likely, the future employees would be more computer savvy and efficent due to technologies and can catch on quickly helping this company continue to trend in the right direction by keeping up therevenues.
