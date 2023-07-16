# E-Commerce Backend

## Description
This application is a back-end for an E-Commerce site, allowing you to perform CRUD functions for each of the main tables. The server consist of 3 modes following through Insomia; Category, Product and Product Tags. These are the highlighted proficiences during development:

* MySQL
* Sequelize 
* ORM
* CRUD operations
* NODE.js
* Models

## User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria
```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

```



## Installation
User will need to do the following; install npm libaries, create a .env file including entires for the ecommerce_db. Set-Up CLI Commands from project root directory:
>npm i<br>
>cd db or right click intergrated terminal on schema.sql<br>
>mysql -u root -p, enter psswrd<br>
>SOURCE schema.sql<br>
>exit<br>
>cd ..<br>
>npm run seed<br>


## Usage
The application is now functional to POST,PUT,GET & DELETE for categories/products/tags.
[Video Demonstration Link Here](https://drive.google.com/file/d/1hbvpKv_SGG7hmDJhEMI9URdeiRy2PaQN/view)

## Review 
The URL of the GitHub repository (https://github.com/krsilveira/Challenge-13-)