# E-commerce Backend

## Description

This project focuses on building the backend for an e-commerce site. It involves configuring a working Express.js API to use Sequelize as the interaction layer with a MySQL database. The backend is designed to support various operations for managing product categories, products, and tags.

## Features

- Configure an Express.js API to work with Sequelize and MySQL.
- Define database credentials and connection settings in an environment variable file.
- Create and seed a development database with test data using schema and seed commands.
- Start the application to initiate the server and sync Sequelize models with the MySQL database.
- Implement API endpoints for categories, products, and tags.
- Support CRUD (Create, Read, Update, Delete) operations for managing data in the database.

## Installation

To install and run this application, follow these steps:

1. Clone the repository

2. Install the required dependencies by running `npm install` in the project's root directory.

3. Create an environment variable file (e.g., `.env`) and add the following variables with your database credentials:

DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_HOST=localhost
DB_PORT=3306

4. Create the database and seed it with test data using the provided schema and seed commands.

5. Start the application by running:

npm start

## Usage

- Access the API endpoints using an application like Postman or any API testing tool.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Walkthrough Video

You can find the walkthrough video for this project https://drive.google.com/file/d/1ilOEz_VbjJyXeHD6wDwO-77hkwTgHzMF/view?usp=sharing.

# Screenshot
<img width="2554" alt="Screenshot 2023-10-12 at 10 51 27 PM" src="https://github.com/vikramadityad/E-commerce_Back_End/assets/28673859/c297db03-af10-4cb9-8493-cad1939773ac">


## Acknowledgement

https://github.com/coding-boot-camp/fantastic-umbrella 

