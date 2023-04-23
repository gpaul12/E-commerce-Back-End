# E-commerce-Back-End

The E-Commerce Backend is a REST API for an internet retail website. The API is built onto an Express.js server that uses [Sequelize](https://sequelize.org/master/) to interact with a MySQL database. Sequelize is a promise-based Node.js ORM(Object Relation Mapping) for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server.

This E-Commerce backend has the API routes that point to each of the standard [CRUD](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete) operations for each data group. The routes can be used to:

- Create categories, products, tags
- View categories, products, tags
- Establish associations between the different entities
- Update categories, products, & tags
- Delete entries from the database

---

## **Table of contents**

- [E-Commerce Backend](#e-commerce-backend)
  - [Table of contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Demo Video](#demonstration-video)
  - [Built With](#built-with)

---

Start with cloning this repo on your local machine:

```sh
$ git clone https://github.com/lukecp5/e-commerce-backend.git
$ cd e-commerce-backend
```

To install and set up the application, run:

```sh
$ npm install employee-tracker
```

You will also need to place a .env file in the root directory of the project, in order to connect to your MySQL database. Here's an example:

file: .env

```
DB_NAME=library_db
DB_PASSWORD=
DB_USER=root
```

---

## **Usage**

<sub><sup>This section assumes you have installed the application, and created the .env file in the root directory.</sub></sup>

To finish the set-up the application, complete the following steps:

1. Create a MySQL database on your local machine using the _schema.sql_ file located in the /db/ directory(From the MySQL CLI, source db/schema.sql)
2. Seed the database with sample data to be used for testing purposes(Run _npm run seed_ from inside the root directory of the project)

Now you're ready to start the application! You can start the server by running:

```
npm start
```

The server is running, now you can make requests to it through your desired method. 

---

## **Built With**

- [**Node.js**](https://nodejs.org/en/about/)
- - [Sequelize](https://www.npmjs.com/package/sequelize)
- - [Express.js](https://www.npmjs.com/package/express)
- [**Visual Studio Code**](https://code.visualstudio.com/)

---

## **Demonstration Video**

If you'd like to see a full demo of the application, please visit the following link: [Demo Video on Google Drive](https://drive.google.com/file/d/1uVv12RdgGpGfC13LZHh0F31BEiwK8auA/view)

## **Author**

**Gerry Paul**  
GitHub: [gpaul12](https://github.com/gpaul12)  
Email: [gpaul12@nc.rr.com](mailto:gpaul12@nc.rr.com)
