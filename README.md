# Ecommerce Backend
  ![Github licence](http://https://img.shields.io/badge/license-MIT-License-blue.svg)
  ## Description 
  This project is the back end for an e-commerce site. This application uses Express.js and Sequelize to interact with a MySQL database. This application creates a database using MySQL models and associations. API Routes are created to perform RESTful CRUD operations using sequelized models.
  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Tests](#tests)
  * [Questions](#questions)
  
  ## Installation 
 * Dependencies/Packages
    - Node.js
    - Express.js
    - MySQL2
    - Sequelize
    - dotenv

* Git clone the repo from Github

* Navigate to the folder and run `npm install` in your terminal.

* Be sure to include your MySQL user/password information in .env file.

* Database Connection
    - `mysql -u root -p`
    - `source schema.sql`
    - `npm run seed` [To seed the file]

* Run the app
     - `npm start` [To start the server] and navigate to <http://localhost:3001/> in your browser OR Use Insomnia Core
  ## Usage 
  1. Walkthrough video covers MySQL shell [Click here]()<br>
    * Source the schema <br>
    * Seed the database <br>
    * Start the npm Server
       
2. Walkthrough video covers API routes being tested in Insomnia Core. [Click here](https://d)<br>
    *  GET routes for all categories, all products, and all tags <br>
    *  GET routes for a single category, a single product, and a single tag by Id<br>
    *  POST, PUT, and DELETE routes for categories, products, and tags

3. Walkthrough video showing all the technical acceptance criteria met. [Click here](https://)<br>
    * Uses the MySQL2 and Sequelize packages to connect to a MySQL database
    * Uses the dotenv package to use environment variables to store sensitive data, like a user’s MySQL username, password, and database name.
    * Syncs Sequelize models to a MySQL database on the server start.
    * Column definitions for all four models
    * Model associations
  
  ## License
  MIT-License
  ## Tests
 There are no tests
  ## Questions
  If you have any questions about this projects, please contact me directly at cwpardue@gmail.com. You can view more of my projects at https://github.com/pardue95.
