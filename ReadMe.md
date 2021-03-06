# Lesson 4 Practice Hands-On

# Directions

Now that you have learned about routing in Express using a database, it's time to put that knowledge to work. This Hands-On will not be graded, but we encourage you to complete it. The best way to become a great programmer is to practice! Once you have submitted your project, you will be able to access the solution on the next page.

# Setup
Open up your terminal/command prompt.

Navigate to your desktop in your terminal:

cd Desktop
Then, navigate to the Express-Course directory in your terminal:

cd Express-Course
Requirements
In this Hands-On exercise, you will create an Express web application that returns data from the database based on the route provided in the URL.

# Step 1

To begin, generate a new project (within the Express-Course directory) using the Express/Handlebar generator.

Call this app L04HandsOn
Don't forget to run npm install
Install and run Nodemon
Install and require mysql

# Step 2

Add the connection information to the database in your routes/index.js file.

# Step 3

Create a route of /film to list out all film titles in the database onto the page.

You will need a SQL query for this
For this, create a new view named film.hbs
Step 4
Create another route of /film/:id that will list the corresponding film title and actor names associated with that film onto the page.

For this, create a new view named filmDetails.hbs
NOTE: Your SQL query will need to use JOIN statements between the film, film_actor, and actor tables. There is a many to many relationship between actors and films.
