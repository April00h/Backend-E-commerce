# Backend-E-commerce
Object-Relational Mapping (ORM): E-commerce Back End


## Table of Contents
- [Summary](#summary)
- [Features ](#features)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [Questions](#questions)
- [License](#license)

### Summary 

The project aims to develop the backend infrastructure for an e-commerce website using Express.js API and Sequelize to interact with a MySQL database. Additionally, a walkthrough video will be created to showcase the functionality of the application, meeting specified acceptance criteria.


## User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies


## Acceptance Criteria

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


## Installation 
Put this code in the terminal, 

npm i

## Usage 

mysql -u root -p

source db/schema.sql

quit;

npm run seed

node server.js

use appropriate methods and approriate properties in insomnia




## Contributors
[April Hunt](https://github.com/April00h)

## Links 
* [GitHub Repository](https://)


## Questions
Please reach out with any questions or concerns: [E-mail](mailto:), [E-mail](mailto:aprilhunt00.ah@gmail.com)

## License 
This project is licensed under the MIT License.

