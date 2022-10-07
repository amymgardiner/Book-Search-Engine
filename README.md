# Book Search Engine

## About Module 21 Challenge - MERN

I took a fully functioning Google Books API search engine built with a RESTful API, and refactored it to be a GraphQL API built with Apollo Server. The app was built using the MERN stack, with a React front end, MongoDB database, and Node.js/Express.js server and API.

I set up an Apollo Server to use GraphQL queries and mutations to fetch and modify data, replacing the existing RESTful API.

I modified the existing authentication middleware so that it works in the context of a GraphQL API.

I created an Apollo Provider so that requests can communicate with an Apollo Server.

And then I deployed the application to Heroku.

## Expected Behavior

GIVEN a book search engine, WHEN you load the search engine, THEN you are presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button.

WHEN you click on the Search for Books menu option, THEN you are presented with an input field to search for books and a submit button.

WHEN you are not logged in and enter a search term in the input field and click the submit button, THEN you are presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site.

WHEN you click on the Login/Signup menu option, THEN a modal appears on the screen with a toggle between the option to log in or sign up. WHEN the toggle is set to Signup, THEN you are presented with three inputs for a username, an email address, and a password, and a signup button. WHEN the toggle is set to Login, THEN you are presented with two inputs for an email address and a password and login button. WHEN you enter a valid email address and create a password and click on the signup button, THEN your user account is created and you are logged in to the site. WHEN you enter your account’s email address and password and click on the login button, THEN the modal closes and you are logged in to the site.

WHEN you are logged in to the site, THEN the menu options change to Search for Books, an option to see your saved books, and Logout.

WHEN you are logged in and enter a search term in the input field and click the submit button, THEN you are presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to your account.

WHEN you click on the Save button on a book, THEN that book’s information is saved to your account. WHEN you click on the option to see your saved books, THEN you are presented with all of the books you have saved to your account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from your account. WHEN you click on the Remove button on a book, THEN that book is deleted from your saved books list.

WHEN you click on the Logout button, THEN you are logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button.

![shielded-coast-80964 herokuapp com_](https://user-images.githubusercontent.com/99151426/194615566-52ace664-338a-432a-bd4a-65d39562d151.png)
