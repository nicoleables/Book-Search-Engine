# Book-Search-Engine

## Description
This project involves refactoring a fully functioning Google Books API search engine built with a RESTful API to use a GraphQL API with Apollo Server. The application is built using the MERN stack, featuring a React front end, MongoDB database, and Node.js/Express.js server and API. Users can search for books and save their searches to the back end.

## Table of Contents
Installation
Usage
User Story
Acceptance Criteria
License
Contributing
Questions
Installation
Clone the starter code repository.
Create your own repository with the starter code (do not fork the starter code repository).
Install the necessary dependencies by running:
npm install

## Usage
Set up an Apollo Server to use GraphQL queries and mutations to fetch and modify data, replacing the existing RESTful API.
Modify the existing authentication middleware to work in the context of a GraphQL API.
Create an Apollo Provider so that requests can communicate with an Apollo Server.
Deploy the application to Render.
User Story
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase

## Acceptance Criteria
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button

License
This project is licensed under the MIT License.

Contributing
Please feel free to contribute to this project by submitting a pull request.

Questions
If you have any questions about the repo, open an issue or contact me directly at [ablesnicole@icloud.com]. You can find more of my work at [https://github.com/nicoleables].
