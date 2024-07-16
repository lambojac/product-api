# Product API

This is a simple REST API for managing products using NestJS and PostgreSQL. The API supports basic CRUD operations and includes basic authentication and authorization.

## Table of Contents

- [Installation](#npm install)
- [Running the App](#npm run start)
- [Test](#test)
- [API Endpoints](#api-endpoints)
- [Database Schema](#postgresql)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Installation

To install and set up the project, follow these steps:

1. **Clone the repository:**
 https://github.com/lambojac/product-api.git
2 **install all packages**
npm install

3 **setup .env**
DATABASE_URL=postgresql://username:password@localhost:5432/productdb
JWT_SECRET=your_jwt_secret_key

4 **Set up the PostgreSQL database**

Make sure PostgreSQL is installed and running on your system. Then create the database
CREATE DATABASE productdb;

5 **Running the App**

To run the application, use the following command
npm start

6 **API Endpoints**
The API provides the following endpoints:
    **Retrieve all products**
GET /products: 
    **Retrieve a single product by ID**
GET /products/:id
    **Create a new product**
POST  /products 
    **Update an existing product by ID**
PUT /products/:id
    **Delete a product by ID**
DELETE /products/
    