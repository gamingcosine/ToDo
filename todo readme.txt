Assumptions

The user has to login and then he/she can create or delete the todo tuples.

Approach

We will create 4 forms in java and link them with the database.

First will be Login form(for existing user), second will be registration form (for new user)
third will display the records fetched from the database in a tabular form where the user 
can click on the column name to prioritize the tasks and the fourth will be the main form 
through which we will access other forms.

We will implement this in Netbeans which provides drag and drop support for buttons,textboxes etc. 
for creating, viewing, deleting and altering frames/forms and will create a button that allows 
searching a task based on its title/date/priority/state(using group/order by function).

After importing the connection files, we will link the front-end form with the database.

Simultaneously, we will work on DB also.

When DB is ready and connected with the form, build the project.

DB Schema
we will create a database named TODO which will have 2 tables
1. The user table - it will contain the data of registered users
	the columns would be employee id, username, password
2. The tasks table will contain the to-do data of the user	
	the columns would be index, title, date, priorty(low/medium/high), state(complete/incomplete/ongoing)

Steps to run
1. start the database server
2. start the application
3. login/register(we will check the authentication and also ifthere are blank text fields)
4. use the application.
