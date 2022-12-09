# E-commerce Backend

## Preview

google drive link here

## Description




## User Story
```md
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
* After cloning the repo, run `npm i` to install the npm dependencies.
* Initiate the database using `mysql -u root -p` and login to MySQL terminal. 
* Enter `source db/schema.sql` to create the db tables. Run `show databases;` to test that's working. Then `quit` when you're done.
* Switch back to bash terminal, and run `npm run seed`.
* Finally, enter `npm start` to start the server.


## Technologies Used
* Express.js
* [MySQL2](https://www.npmjs.com/package/mysql2)
* [Sequelize](https://www.npmjs.com/package/sequelize)
* [dotenv](https://www.npmjs.com/package/dotenv)
* Insomnia


## License
MIT license

## Contact Info
Contact Susan if you have questions about the repo.
