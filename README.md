Inventory Management Backend

This project is the backend for an inventory management and shopping cart system built with Node.js, Express, and MongoDB.

Features:

Create, read, update, and delete inventory items

Connects to MongoDB using Mongoose

Uses environment variables for configuration

Organized project structure for easy maintenance

Setup instructions:

Clone the repository using
git clone https://github.com/roylin05/inventory_management_backend.git
Then change directory to the project folder:
cd inventory_management_backend

Install the required packages by running
npm install

Create a .env file by copying the example file:
cp .env.example .env
Then edit the .env file to add your MongoDB connection string and the port number like this:
MONGODB_URI=your_mongodb_connection_string
PORT=5000

Start the server by running
npm start

The server will run locally at http://localhost:5000

API endpoints overview:

GET /api/items — to get all inventory items

POST /api/items — to add a new item

PUT /api/items/:id — to update an existing item

DELETE /api/items/:id — to delete an item
