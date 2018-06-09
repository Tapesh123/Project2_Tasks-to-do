# Project2_Tasks-to-do

Having a great to-do list app can help you get organized and get more done, whether you're managing only your own tasks or those for a family or small team.

A Node, Express, Handlebars, and MySQL Task to do app that lets users input their daily tasks that they need to complete and complete (check off) as they go along. 

# Live
[https://safe-anchorage-26840.herokuapp.com/]

![Image of Tasks-To-Do-List APP](https://github.com/Tapesh123/Project2_Tasks-to-do/blob/master/TaskTodo.gif)


## Functionality

Using an home-grown ORM, the app has 3 basic CRUD functions...

READ all entries from the MySQL database and display them to the DOM using Handlebars.
UPDATE a selected task by clicking It, which...

re-routes the webpage back to the index, where the Tasks are now in the done column (via Handlebars)
CREATE a new task using the "Add and Remove" form, which...
hits a /task/create route in Express to insert a new task into the MySQL database
re-routes the webpage back to the index, where the task is now ready to be completed or to-do column (via Handlebars)


## TECHNOLOGY
• Bootstrap
• express.js
• node.js
• handlebars.js
• MySql

