# Product-Store

Welcome to **Product-Store**, a full-stack web application that allows users to manage and display products. This project utilizes HTML, CSS, ReactJS, NodeJS, ExpressJS, MongoDB, Postman, and REST APIs to provide a seamless product management experience.

## Table of Contents
- [Getting Started](#getting-started)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with Product-Store, follow the steps below:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Product-Store.git
   
   Install the required dependencies for both the frontend and backend by navigating to the project's root directory and running the following commands:
   
    cd Product-Store
    npm install
    cd client
    npm install

     Set up your MongoDB database and update the database configuration information in server/config/db.js.

    Create a .env file in the server directory to store your environment variables (e.g., database connection string, JWT secret):
   
    DATABASE_URL=your-mongodb-connection-string
    JWT_SECRET=your-jwt-secret

    Start the backend server:
    cd server
    npm start
   
    Start the frontend:
     cd client
     npm start


 ## Features
- User-friendly web interface for adding, updating, and deleting products.
- Real-time updates using React and EJS to display product information.
- Secure authentication and authorization for protected routes.
- RESTful API endpoints for product management.
- MongoDB database for data storage.
- Tested and documented REST API endpoints using Postman.

## Technologies Used
- HTML, CSS for frontend design.
- ReactJS for building the frontend.
- NodeJS and ExpressJS for the backend server.
- MongoDB for database storage.
- Postman for API testing and documentation.
- REST APIs for seamless communication between the frontend and backend.

## Usage
1. Register or log in to your account to access the product management dashboard.
2. Use the intuitive forms to add new products, specifying details like name, description, price, and image.
3. Edit or delete existing products as needed.
4. View the updated product list in real-time on the frontend.

## API Documentation
For detailed documentation on the RESTful API endpoints provided by Product-Store, please refer to the [API Documentation](/server/API_DOCUMENTATION.md).

## Contributing
We welcome contributions to enhance the functionality and features of Product-Store. To contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Implement your changes and test them thoroughly.
4. Create a pull request describing your changes and their purpose.

