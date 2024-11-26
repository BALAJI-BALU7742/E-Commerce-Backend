# E-Commerce Backend

This repository contains the backend for an e-commerce platform, built using the **MERN** stack (MongoDB, Express.js, React, Node.js).
It provides a RESTful API to manage products, user authentication, and order processing.


## Features

- User authentication and authorization (JWT-based)
- Product management (CRUD operations)
- Cart and Order functionality
- Admin dashboard for managing users and products
- Payment gateway integration (if applicable)
- Error handling and validation

## Technologies Used

- **Node.js**: JavaScript runtime for building scalable backend applications.
- **Express.js**: Web framework for Node.js.
- **MongoDB**: NoSQL database for storing product, user, and order data.
- **Mongoose**: MongoDB object modeling tool for Node.js.
- **JWT (JSON Web Tokens)**: For secure user authentication.


## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/BALAJI-BALU7742/E-Commerce-Backend.git
   cd E-Commerce-Backend
   
**Install the dependencies:**

npm install

**Usage**
To run the server locally in development mode:

npm run dev
To run the server in production mode:


npm start
You can now access the backend API at http://localhost:5000.

**API Documentation**
Authentication
POST /api/auth/register – Register a new user.
POST /api/auth/login – Login with credentials and receive a JWT token.
Products
GET /api/products – Get a list of all products.
GET /api/products/:id – Get product details by ID.
POST /api/products – Create a new product (Admin only).
PUT /api/products/:id – Update product details (Admin only).
DELETE /api/products/:id – Delete a product (Admin only).
Orders
GET /api/orders – Get all orders (Admin only).
GET /api/orders/:id – Get order details by ID.
POST /api/orders – Create a new order.
PUT /api/orders/:id – Update order status.
**Contributing**
Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request. Please ensure your changes are well-documented and follow the existing coding style.
