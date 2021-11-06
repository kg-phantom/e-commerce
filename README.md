# E-Commerce Back End
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![ExpressJS](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://choosealicense.com/licenses/mit/)

## Description
The back-end for an e-commerce site in order to get, post, update, and delete items from the company database.

## Table of Contents
* [Demo](#demo)
* [Installation](#installation)
* [Usage](#usage)
* [CRUD](#crud)
* [License](#license)
* [Questions](#questions)

## Demo
[Click here](https://drive.google.com/file/d/14z6HRPoWoNxQNTJVMgHnGCEFXSu2Ps8f/view) to watch a demo of the application.

## Installation
1. Install [Node.js](https://nodejs.org/en/) and [MySQL](https://dev.mysql.com/downloads/mysql) if you haven't already.
    - You can follow this [installation guide](https://coding-boot-camp.github.io/full-stack/mysql/mysql-installation-guide) to help you install MySQL.
2. Clone this repository onto your computer.
3. Navigate to the root of this repository on the command line.
4. Run `npm install` on the command line.
5. Run the following command to install the necessary packages:
```
npm install express mysql2 sequelize;
```
6. Run `mysql -u root -p` on the command line and enter your MySQL password to open the MySQL interface.
7. In MySQL, run `SOURCE ./db/schema.sql` to set up the `ecommerce_db` database.
8. In the root directory of the repository, run `touch .env` on the command line to create an environment variable file.
9. In the `.env` file, type the following:
```
DB_NAME='ecommerce_db'
DB_USER= [YOUR MYSQL USERNAME HERE]
DB_PW= [YOUR MYSQL PASSWORD HERE]
```
10. Run `npm run seed` on the command line to seed the `ecommerce_db` database.

## Usage
1. Navigate to the root directory of this repository.
2. Run `npm start` on the command line.
3. Open Insomnia Core and use the following endpoints to use the database:
    - To GET categories: `/api/categories`
    - To GET products: `/api/products`
    - To GET tags: `/api/tags`
    - To GET, POST, PUT, or DELETE a category by ID: `/api/categories/:id`
    - To GET, POST, PUT, or DELETE a product by ID: `/api/products/:id`
    - To GET, POST, PUT, or DELETE a tag by ID: `/api/tags/:id`

## CRUD
This application performs RESTful CRUD operations to interact with the database.

- GET all categories, products, and tags.
- CREATE a category, product, or tag.
- UPDATE a category, product, or tag by ID.
- DELETE a category, product, or tag by ID.

## License
Licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.

## Questions
- [GitHub](https://github.com/kg-phantom)