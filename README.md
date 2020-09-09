# Database-Processing-M5<br>
### Part 1<br>

Using the company.sql database (posted in with this assignment), write the following SQL queries. <br>

1. Find the names of all employees who are directly supervised by 'Franklin T Wong' (you cannot use Franklin’s SSN in the query).<br>

2. For each project, list the project name, project number, and the total hours per week (by all employees) spent on that project.<br>

3. For each department, retrieve the department name and the average salary of all employees working in that department.  Order the output by department number in ascending order.<br>
<br>
### Part 2<br>
Create the table and use python to automate loading of the following file into SQLite:<br>
You can use csvreader to automatically solve the problem for you:<br>
import csv<br>
fd = open('Public_Chauffeurs_Short_hw3.csv', 'r')<br>
reader = csv.reader(fd)<br>
for row in reader:<br>
    print(row)<br>
fd.close()<br>
<br>
### Part 3<br>

We are going to work with a small extract of tweets (about 200 of them)<br>
a.	Create a SQL table to contain the following attributes of a tweet:<br>
"created_at", "id_str", "text", "source", "in_reply_to_user_id", “in_reply_to_screen_name”, “in_reply_to_status_id”, "retweet_count", “contributors”. Please assign reasonable data types to each attribute and use SQLite for this assignment.<br>
b.	Write python code to read through the Assignment4.txt file and populate your table from part a.  Make sure your python code reads through the file and loads the data properly (including NULLs).
