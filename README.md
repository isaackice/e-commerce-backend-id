# e-commerce-backend-id

## Description

This application is the back-end side of an e-commerce website using Express.js. It contains a MySQL database which is connected using Sequelize, with a development database created and seeded with test data. The server is started and Sequelize models are synced to the MySQL database. The API routes for GET, POST, PUT, and DELETE are tested and successfully able to display, create, update, and delete data in the database.

## Installation

The user will need to install the MySQL2 and Sequelize packages to connect your Express.js to a MySQL database and the dotenv package to use environment variables to store sensitive data.

* Run the commands `npm i` and `npm dotenv` to install the necessary dependencies

Use the `schema.sql` file in the `db` folder to create your database with MySQL shell commands. Use environment variables to store sensitive data like your MySQL username, password, and database name.

* Run the command `source db/schema.sql` once logged into your MySQL database.

* Run `npm run seed` to seed data to your database so that you can test your routes.

## Credits

Rutgers Bootcamp, W3 Schools, Professor Joe Han, TA Paul Cwik, Classmates Nick Stallard, Eric Kirberger, Jonathan Plaras and Marc Nicolas.

## License

MIT License ,, refer to GitHub repo.