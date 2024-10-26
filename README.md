# Hoot
Hoot is a notes website thing!

## Setting up Hoot

Open up command prompt 
1. Windows key + R
2. Type 'cmd' and press Enter

Navigate to the folder where you want to clone hoot
```For only cloning a specific branch:
git clone -b <branch> <repo_url> 
```
```For cloning the main branch
git clone <repo_url> 
```
Navigate inside the repo folder
```
cd Group8Project
```
## Install Dependencies (Express, Express-Session Mongoose, Bcrypt, EJS,)
"Express is a popular, lightweight, and flexible Node.js web application framework that provides a robust set of features for building web applications and APIs. It is designed to be minimalistic, allowing developers to easily create robust and scalable applications."
"Express-session is a middleware for Express.js that enables you to manage user sessions in your web applications. It provides a way to store data associated with a specific user across multiple requests, typically using cookies."
"Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node.js. It provides a schema-based solution to model your application data, making it easier to interact with MongoDB databases."
"Bcrypt is a password-hashing algorithm that protects passwords in storage by turning them into a fixed-length string of characters"
"EJS, or Embedded JavaScript, is a templating language that allows users to generate HTML with JavaScript." 
source: google.com AI answers
```
npm install express
npm install express-session
npm install mongoose
npm install bcrypt
npm install ejs
```
You can now type in the terminal 
```
node server.js
```
and it should run the server.js. Go to
```
http://localhost:3000
```
