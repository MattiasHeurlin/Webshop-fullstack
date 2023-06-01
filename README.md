Full Stack Web Shop - README

This project is a full-stack web application for an eCommerce platform. It uses Vue 3 (with Composition API) for the frontend and Node.js with Express.js and MongoDB for the backend. This application provides a user-friendly interface for both administrators and customers. Administrators can manage products, view and handle orders, while customers can browse products, add them to a cart, and place orders. The stock count is updated in real-time following purchases.
Features
Admin Features

    Authentication and authorization for secure access
    Ability to add, edit, or remove products
    Ability to view all orders
    Ability to update order status

Customer Features

    Ability to browse all available products
    Ability to add products to the shopping cart
    Ability to place an order
    Ability to view order history

Common Features

    Real-time stock management: The product availability and count are updated upon purchase

Installation

You need Node.js, npm and MongoDB installed on your system.
Frontend:

bash

# Install dependencies
npm install

# Serve with hot reload at localhost:8080
npm run dev

Backend:

bash

# Install dependencies
npm install

# Start the server
npx nodemon

Note: The database needs to be set up separately and connected to the backend server.
