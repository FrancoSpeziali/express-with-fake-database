# An Express.js server with a fake database

This project will allow you to practise writing handlers for requests in Express.js

## What you will be doing

This project will allow you to practise using:

> Express.js

This project assumes you've already had experience with:

> Express.js
> Array methods in JavaScript

## Tasks

### Task 1 - Getting ready

1. Initialise npm into your project
   `npm init -y`
2. Install the express.js npm package
   `npm i express`
3. Create a file for your server (`server.js`)

### Task 2 - Setting up your server

Use the snippet **starter code** to initialise your `server.js` file

### Task 3 - Import your database

We will use mock data for our database

Import the file `database.js` into your file `server.js`

### Task 4 - Add a handler for a GET request to '/checkUsernameExists'

Using the snippet **GET request with route parameter**, write a handler that will respond to the path `/checkUsernameExists`

> Hint: Parameters can be added to a path with a `:` symbol, for example, to add the parameter `name` we would write `/:name/`

This handler should receive one parameter `username`

The handler should check to see if the user exists in the database and return the id of the user.

> Hint: You will probably need to use the `Array.find()` method

- If the user exists, send a `response` with the message "User exists" along with the id of the user

- If the user does not exist, send a `response` with the message "User does not exist"

### Task 5 - Add a handler for a GET request to '/findById'

Using the snippet **GET request with route parameter**, write a handler that will respond to the path `/findById`

This handler should receive one parameter `id`

The handler should check to see if the user exists in the database, searching by the id
