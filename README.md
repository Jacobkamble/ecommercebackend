# eCommerce Backend

This repository contains the backend code for the eCommerce platform, built using Node.js, Express, and MongoDB. The backend handles user authentication, product management, order processing, and provides a robust API for the frontend.

## Features
User Authentication and Authorization: Secure login, registration, and firebase based authentication.

Product Management: APIs for adding, updating, deleting, and fetching products.

Order Management: APIs for creating and managing customer orders.

User Profiles: Manage user information and view order history.

Admin Capabilities: Admin-specific routes for managing users and products.

## Technologies Used

Node.js: JavaScript runtime for building fast and scalable server-side applications.

Express: Minimal and flexible Node.js web application framework.

MongoDB: NoSQL database for efficient data storage and retrieval.

Mongoose: ODM (Object Data Modeling) library for MongoDB.

## Install Dependencies

**For Backend** - `npm i && npm run build`


## Env Variables

Make Sure to Create a  .env file in root directory and add appropriate variables in order to use the app.

**Essential Variables**

PORT= `4000 or any`

MONGO_URI= `mongodb://localhost:27017 or cloud uri`

STRIPE_KEY=`stripe secret key`


PRODUCT_PER_PAGE=`8 or any`