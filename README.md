# connectDB.js - MongoDB Connection with Mongoose

## Overview
The `connectDB.js` file simplifies the process of connecting to MongoDB in Node.js applications using Mongoose. It handles the connection setup and error handling, making it easy to integrate into any project that requires a MongoDB database connection.

## Usage
1. **Install Mongoose**  
   To use `connectDB.js`, ensure you have Mongoose installed:
   ```bash
   npm install mongoose

## Add MongoDB URI
Make sure you have a MongoDB URI in your environment file (.env):
Create a .env file within your Next.js project

DATABASE_URL=mongodb+srv://your-username:your-password@cluster.mongodb.net/your-database
