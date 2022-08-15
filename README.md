# E-Commerce Back End [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

  The project is designed to manipulate back-end data based on user input. 

## Table of Contents
  [Description](#description)<br/>
  [Installation Instructions](#installation)<br/>
  [Usage Information](#usage)<br/>
  [License](#license)<br/>
  [Video Link](#Video)<br/>


## Installation
To use the application, users would first have to login to mysql on their machina to create the database that the application will use. 
To do this, the process would be as follows:
1. Run (in terminal) 'mysql -u (username) -p (password)' with their username and password, 
2. 'SOURCE ./db/schema.sql'.
3. quit
4. rename .env.EXAMPLE to .env
5. open .env
6. enter the values of the database, their mysql username and password into the corresponding fields
7. save .env
The following step is used to seed the database with data and can be ignored if the user wishes to start from scratch
8. (run in terminal) node seeds/index.js
To start the application on localhost port 3001
9. (run in terminal) node server.js 

## Usage
Users are able to implement CRUD operations to create, read, update and delete data in the selected database. <br/>
  The following images show the CRUD operations in action.
  <br/><br/><br/>
  The user is able to get/read all the data in the categories table.
  ![get/read operation](/assets/images/all_cat.png)

  The user is able to create a new category to place inside the categories table.
  ![create table](/assets/images/create_cat.png)

  The user is able to update a category inside the categories table.
  ![update table](/assets/images/update_cat.png)

  The user is able to delete a category inside the categories table.
  ![delete table](/assets/images/delete_cat.png)

## License
This application is covered under the [MIT](https://opensource.org/licenses/MIT) license

## Video
To see the full walthrough of this application, please click [this link.](https://drive.google.com/file/d/1QQ-5e-AyeC7u2X0uRf-loV1ay5OK1s6m/view?usp=sharing)