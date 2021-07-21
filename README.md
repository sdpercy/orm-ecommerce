# Object-Relational Mapping (ORM): E-commerce

# Table of Contents
* [User Story](#user-story)
* [Acceptance Critiera](#acceptance-criteria)
* [Walk Through](#walk-through)
* [Installation](#installation)

## User Story
>AS A manager at an internet retail company
>I WANT a back end for my e-commerce website that uses the latest technologies
>SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
>GIVEN a functional Express.js API
>WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
>THEN I am able to connect to a database using Sequelize
>WHEN I enter schema and seed commands
>THEN a development database is created and is seeded with test data
>WHEN I enter the command to invoke the application
>THEN my server is started and the Sequelize models are synced to the MySQL database
>WHEN I open API GET routes in Insomnia Core for categories, products, or tags
>THEN the data for each of these routes is displayed in a formatted JSON
>WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
>THEN I am able to successfully create, update, and delete data in my database

## Installation

1. Clone this repository to your local machine. In the root directory of the project, type in the terminal command line **'npm i'** to download the dependencies. 
2. Initiate the database with **'mysql -u root -p'**, then 'source db/schema.sql' to create the tables. 
3. Exit the mysql terminal and from bash, type **'npm run seed'** to seed the data into your tables. 
4. Now you can run **'npm start'** to start the server!


## Walk Through
Click link or see video in video folder in repository.
https://drive.google.com/file/d/1CFSADcaKIejlkOdVtvkR8Bj2l5-7jPHi/view

