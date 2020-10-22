# Burger Tracker

[Link to Functional Application](https://radiant-wildwood-61677.herokuapp.com/)

This is an application that tracks burgers the user would like to eat and ones they have already eaten.

![img-of-website](https://github.com/evanmackay/burger-app/blob/main/public/assets/img/Screen%20Shot%202020-10-21%20at%207.21.30%20PM.png?raw=true)

## How it Works

This app uses a MCV to create connections to a database using MySQL, Node.js, and Handlebars.js. The items that are entered into the input form are sent as a PUT request to the server and are then added to a MySQL database. If the user has already used the application, The back-end server code will use the ORM that is coded to display all of the burgers that are in the database. Once a burger has been devoured, its boolean value will be changed and it will be added to the new list for burgers that have been eaten!

## What was Used

This application uses JavaScript on the front-end and Node.js, MySQL, and Handlebars.js on the backend.
