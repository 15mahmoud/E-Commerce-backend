# E-Commerce Backend

The E-Commerce Backend is a robust Node.js application utilizing Express.js and MongoDB. It enables seamless online shopping experiences with authentication, product management, order processing, and payment integration. Designed for scalability, it provides a structured foundation for an expansive e-commerce platform.

## Features

- **User Authentication**: Secure user registration and login using JWT tokens.
- **Product Management**: CRUD operations for products, including categorization and inventory tracking.
- **Order Processing**: Management of customer orders, payments, and order status updates.
- **Payment Integration**: Seamless integration with payment gateways to process transactions securely.

## Technologies Used

- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web framework for building RESTful APIs.
- **MongoDB**: NoSQL database for data storage.
- **Mongoose**: ODM library for MongoDB and Node.js.
- **JWT**: JSON Web Tokens for secure authentication.

## Folder Structure

- **config/**: Configuration files for database connections and environment variables.
- **middlewares/**: Custom middleware functions for request validation and authentication.
- **models/**: Mongoose schemas and models representing data structures.
- **routes/**: API endpoints and route definitions.
- **services/**: Business logic and service layer implementations.
- **uploads/**: Directory for storing uploaded files.
- **utils/**: Utility functions and helpers.

## Getting Started

### Prerequisites

- Node.js installed on your machine.
- MongoDB instance running locally or accessible remotely.

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/15mahmoud/ecommerce-api.git

2. **Navigate to the project directory**:

   ```bash
   cd graduation-project-backend
  
3. **Install dependencies**:

    ```bash
   npm install
    
4. **Start the server**:
 
   ```bash
   npm run dev
