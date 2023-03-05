E-commerce Backend
==================

Table of Contents
-----------------
-   [Description](#description)
-   [Installation](#installation)
-   [Usage](#usage)
-   [Technologies](#technologies)
-   [Screenshots](#screenshots)
-   [Video Walkthrough](#video-walkthrough)
-   [Contributing](#contributing)
-   [License](#license)

Description
-----------

This is the backend for an e-commerce site that uses Sequelize and MySQL to interact with a database containing information about products, categories, and tags. It has several API endpoints that allow users to retrieve, create, update, and delete data.

Installation
------------

To install the necessary dependencies, run the following command:


`npm install`

To create the database, run the following command:


`npm run seed`

To start the server, run the following command:



`npm start`

Usage
-----

The API endpoints are as follows:

### Products

-   `GET /api/products` - Returns all products, including their associated categories and tags.
-   `GET /api/products/:id` - Returns a single product by ID, including its associated category and tags.
-   `POST /api/products` - Creates a new product in the database.
-   `PUT /api/products/:id` - Updates a product in the database by ID.
-   `DELETE /api/products/:id` - Deletes a product from the database by ID.

### Categories

-   `GET /api/categories` - Returns all categories, including their associated products.
-   `GET /api/categories/:id` - Returns a single category by ID, including its associated products.
-   `POST /api/categories` - Creates a new category in the database.
-   `PUT /api/categories/:id` - Updates a category in the database by ID.
-   `DELETE /api/categories/:id` - Deletes a category from the database by ID.

### Tags

-   `GET /api/tags` - Returns all tags, including their associated products.
-   `GET /api/tags/:id` - Returns a single tag by ID, including its associated products.
-   `POST /api/tags` - Creates a new tag in the database.
-   `PUT /api/tags/:id` - Updates a tag in the database by ID.
-   `DELETE /api/tags/:id` - Deletes a tag from the database by ID.

Technologies
------------

This project was built using:

-   Node.js
-   Express.js
-   Sequelize
-   MySQL

Screenshots
------------

Example of the diagram used for the models

![Diagram](https://user-images.githubusercontent.com/108836644/222974243-5744b02d-c89c-439c-84ed-320828a378ad.png)

GET routes used

![GET example](https://user-images.githubusercontent.com/108836644/222974251-b9376a7f-2486-4012-ad32-17b6d92a897a.png)

POST routes used

![POST example](https://user-images.githubusercontent.com/108836644/222974255-30e65ace-c7af-4c8b-9135-8b7634306a94.png)

UPDATE route used to create

![UPDATE example](https://user-images.githubusercontent.com/108836644/222974262-8f3b2ccd-ede6-4b0a-98e1-2303bd7bc5e2.png)

DELTE route used

![DELETE example](https://user-images.githubusercontent.com/108836644/222974267-cb632c61-6b24-4a3a-8a40-5f8c858d4028.png)


Video Walkthrough
------------

https://youtu.be/Jigo3qVPKhU

Contributions
-------------

Contributions to this project are welcome. If you would like to contribute, please create a pull request and I will review it as soon as possible.

License
-------

This project is licensed under the MIT license.
