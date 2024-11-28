# E-Commerce Backend

This is the backend for an E-commerce platform built with the **MERN stack** (MongoDB, Express, React, Node.js). The backend is designed to handle various functionalities like user authentication, product management, and order processing.

## Features

- User authentication (sign up, login, JWT token management)
- Product catalog management (CRUD operations)
- Order management (place, update, delete orders)
- Payment integration (example for integrating a payment gateway)
- Error handling and validation for incoming requests
- MongoDB database integration for storing data

## Technologies Used

- **Node.js**: JavaScript runtime for building scalable server-side applications
- **Express.js**: Web framework for Node.js to handle routing and requests
- **MongoDB**: NoSQL database for storing product, user, and order data
- **JWT (JSON Web Tokens)**: Used for secure user authentication and session management
- **Mongoose**: MongoDB object modeling tool to interact with MongoDB in a more structured way

## Installation

To get started with the project, follow the steps below:

### 1. Clone the repository

```bash
git clone https://github.com/BALAJI-BALU7742/E-Commerce-Backend.git
cd E-Commerce-Backend
npm install


**3. Set up environment variables**
You will need to set up a .env file for your environment variables. Here are the basic variables needed:
MONGO_URI=mongodb://localhost:27017/ecommerce_db
JWT_SECRET=your-secret-key
PORT=5000

npm start

