# Book Search Engine: Built Using MERN

## Description

Most modern websites are driven by two things: data and user demands. This shouldn't come as a surprise, as the ability to personalize user data is the cornerstone of real-world web development today. And as user demands evolve, applications need to be more performant.

This Book Search Engine utilized starting code with a fully functioning Google Books API search engine built with a RESTful API, and it has been refactored to be a GraphQL API built with Apollo Server. The app was built using the MERN stack with a React front end, MongoDB database, and Node.js/Express.js server and API. The code being refactored had already been set up to allow users to save book searches to the back end. 


## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [Animations](#animations)
  * [Credits](#credits)
  * [License](#license)

## Deployed Application
* [Book Search Engine]()


## Installation
1. Set up an Apollo Server to use GraphQL queries and mutations to fetch and modify data, replacing the existing RESTful API.

2. Modify the existing authentication middleware so that it works in the context of a GraphQL API.

3. Create an Apollo Provider so that requests can communicate with an Apollo Server.

4. Deploy your application to Heroku with a MongoDB database using MongoDB Atlas. Use the [Deploy with Heroku and MongoDB Atlas](https://coding-boot-camp.github.io/full-stack/mongodb/deploy-with-heroku-and-mongodb-atlas) walkthrough for instructions.


## Usage
- As a book search engine, when the user loads the search engine, then they're presented with a menu with the following options: 
- Search for Books, Login/Signup, an input field to search for books and a submit button
- When the Search for Books menu option button is clicked,
then the user is presented with an input field to search for books and a submit button
- When the user is not logged in and a search term is entered in the input field, clicking the submit button presents the user with several search results
- Each search result features a book’s title, author, description, image, and a link to that book on the Google Books site
- When the user clicks on the Login/Signup menu option,
then a modal appears on the screen with a toggle between the option to log in or sign up
- When the toggle is set to Signup, then the user is presented with three inputs: for a username, an email address, and a password, and a SIGNUP button
- When the toggle is set to Login, then the user is presented with two inputs: an email address and a password with a LOGIN button
- When the user enters a valid email address, creates a password and clicks on the SIGNUP button, then the user account is created and they are logged in to the site
- When a user enter's their account’s email address and password and click on the LOGIN button, then the modal closes and the user is logged in to the site
- When the user is logged in to the site, then the menu options change: this includes Search for Books, Saved Books, and Logout options
- When the user is logged in and enter's a search term in the input field and clicks the submit button, they are then presented with several search results
- Each search result features a book’s title, author, description, image, and a link to that book on the Google Books site; along with a button to save a book to their account
- When the user clicks the Save button attached to a book, then that book’s information is saved to their account
- When the user clicks on the option to see their saved books, then they are presented with all of the books that have been saved to their account
- When the REMOVE button is clicked on a book, then that book is deleted from the user's Saved Books List
- When the Logout button is clicked, then the user is logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button  

## Animations
![Home Screen](client/public/images/book-search-home-signup.gif)



## Credits

This app uses the following libraries and modules: 

* Express
* Mongoose
* Express.Router
* Compass for viewing the database
* MongoDB

## License
Copyright 2021 Diana L. Daghlas