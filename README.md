# Book Search Engine
This website is a book search engine that allows users to search for books and save them to their account. The website has the following acceptance criteria:

## Features
- Search for Books: The website presents a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button.
- Search for Books: Clicking on the Search for Books menu option presents an input field to search for books and a submit button.
- Login/Signup: Clicking on the Login/Signup menu option presents a modal on the screen with a toggle between the option to log in or sign up.
- Signup: Setting the toggle to Signup presents three inputs for a username, an email address, and a password, and a signup button.
- Login: Setting the toggle to Login presents two inputs for an email address and a password and login button.
- User Authentication: Entering a valid email address and creating a password and clicking on the signup button creates a user account and logs in the user to the site. Entering the user's email address and password and clicking on the login button logs in the user to the site. Clicking on the Logout button logs out the user from the site and presents a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button.
- User Account: When the user is logged in, the menu options change to Search for Books, an option to see my saved books, and Logout.
- Save Books: When the user is logged in and enters a search term in the input field and clicks the submit button, the website presents several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to the user's account.
- See Saved Books: Clicking on the option to see my saved books presents all the books the user has saved to their account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from the user's account.
- Remove Saved Books: Clicking on the Remove button on a book deletes that book from the user's saved books list.
## How to use
- Load the website
- If you're not logged in, use the Login/Signup menu option to create a new account or login to an existing one
- Use the Search for Books menu option to search for books using the input field and submit button
- If you're logged in, you can save books by clicking on the save button and view your saved books using the option to see my saved books.
- You can remove saved books by clicking on the remove button and log out using the Logout button.
## Technologies Used
- React.js
- Google Books API
- Node.js
- Express.js
- MongoDB
## Installation
To install and run this application on your local machine, you'll need to follow these steps:

- Clone the repository from GitHub
- Install the dependencies using the npm install command
- Set up the database by adding your MongoDB URI to a .env file in the root directory of the project
- Run the application using the npm start command
## Credits
This project was worked on in a group by <br/>
https://github.com/ogwalrus <br/>
https://github.com/NickJ13 <br/>
https://github.com/mekael18 <br/>
https://github.com/ekirbs <br/>
https://github.com/jcgom3 <br/> Feel free to contact me at tommymaddog@hotmail.com with any questions or feedback.