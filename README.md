# Database-of-findapet

<h2>Project Summary:</h2>

This is a database for the web application that I am trying to build to promote pet adoption. You can find the code of the web app is in the other repository of my profile. The database has 6 tables: registered-user, credentials, offer, pet, demand, search. The file ERD.png shows the attributes of the tables and the relations between them as well as many details.
<h2>Motivation:</h2>
Through this project, i am trying to put in practice knowledge that i acquired in database modeling and design. Moreover,I am trying to make use of the best practices in database design and push further my knowledge and skills in database design.

<h2>Technology Stack:</h2>

PostgreSQL &
PL/PgSQL

<h2>Installation:</h2>
You can skip step 1 if you already have pgadmin4 installed in your computer, and step 2 if you already created a user.
<ul>
  <li>1- Download PostgreSQL DBMS from: https://www.postgresql.org/download/</li>
  <li>2- Open psql shell type enter for server, databse and port. For user, type postgres and same for password. After, type the following command to create a user on your              name: create user yourname with password yourpassword createdb;</li>
  <li>3- Close the psql shell and reopen it. Type enter for server, database and port. Enter the name of the user that you have created and the password. </li>
  <li>4- Enter the following command: create database findapet;</li>
  <li>5- Close the psql shell and reopen it. Type enter for server and port. Type the name of the database, user name, and password.</li>
  <li>6- Download the sql file. Enter the following command to run it: \i 'path of the file'. Do not forget to double slashes!</li>
</ul>

<h2> Contribute: </h2>
  Pull Requests are always welcome.
