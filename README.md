# delos-inventory

Title: delos-inventory</br>
Student: Dylan Trecker</br>
Description: A E-commerce back end MYSQL database with routes that can be tested through Insomnia.</br>
Full Repository: https://github.com/d-trecker/delos-inventory.git</br>
Get the repository by: $ git clone git@github.com:d-trecker/delos-inventory.git </br>
Video Link: https://drive.google.com/file/d/1PS1UG8-7MpxPxByRh8NWmiz3142HxfWF/view?usp=sharing </br>


How to Set Up / Use</br>
- Clone repo by using $ git clone git@github.com:d-trecker/delos-inventory.git
- Install respected proper NPM packages by using the command 'npm install' in root directory. 
- Create a '.env' in the root directory.
- Update database name, MySQL username, and MySQL password to the .env file and save. 
- Start server by using 'npm start' command in root terminal. 
- Test represented routes in Insomnia. 

User Story</br>
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

Acceptance Criteria</br>
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize

- When you add database name, MySQL username, and MySQL password to an environment variable file, you are able to connect to database. 

WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data

- When you run 'npm run seed' command, database is created and seeded with test data. 

WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database

- When you run 'npm start' server is started and models are synced to the MYSQL database. 

WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON

- When you open GET routes in Insomnia for categories, products, or tags, the data for each of these routes is displayed in a formatted JSON

WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

- When you test API POST, PUT, and DELETE routes, you can create, update, and delete data in the database.