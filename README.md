# AITU Blog

## Prerequisites
- NodeJs
- MongoDB Free Cluster

## Setup
1. Create a .env file with MongoDB URI and JWT Secret.
2. Example:
MONGODB_URI=mongodb+srv://<username>:<password>@clusterName.xxxxxxx.mongodb.net/blog
JWT_SECRET=MySecretBlog

## Installation
npm install bcrypt connect-mongo cookie-parser dotenv ejs express express-ejs-layouts express-session jsonwebtoken method-override mongoose
npm install nodemon

## How to run website:
npm run dev