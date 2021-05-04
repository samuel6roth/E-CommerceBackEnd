# E-Commerce Back End
![GitHub](https://img.shields.io/github/license/samuel6roth/ReadMeGenerator?color=blue)
## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [License](#license)
* [Contributers](#contributers)
## Description
This application allows the user to manage an e-commerce business.
## User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
## Acceptance Criteria
```md
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
In the terminal command line:
* If needed "source ~/.bashrc"
* Remove "EXAMPLE" from .env filename and add credentials for database connection inside file 
* Command “npm install”
* Run schema.sql information in MySQLWorkbench
* Command “npm run seeds"
* Command “npm start”
* Run tests via Insomnia
## License
![GitHub](https://img.shields.io/github/license/samuel6roth/ReadMeGenerator?color=blue)
- This program used the MIT license. 
## Contributers
Samuel Roth
## Questions & Contact
* GitHub Username: [samuel6roth](https://github.com/samuel6roth)
* Email: samuel6roth@gmail.com