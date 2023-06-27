# SocKrit

This is a full-stack MERN (MongoDB, Express, React, Node.js) application.

- Deployement : https://enchanting-blini-cdc000.netlify.app/
  
- Use the following credentials to try :
  
  ```
  email : tempuser@gmail.com
  password : tempuser
  ```


## Table of Contents

- [Description](#description)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)

## Description

This project is a complete fullstack social media application built using the MERN stack (MongoDB, Express, React, Node.js). It provides a comprehensive foundation for developing a responsive web application with user authentication, like functionality, and a dark mode theme. The app leverages modern web development technologies and follows best practices to deliver a rich user experience.

## Features

- User authentication and authorization
- CRUD Operations
- User profiles and social connections
- Dark Mode
- Likes and Comments

## Technologies

- Frontend: React, HTML, CSS
- Backend: Node.js, Express
- Database: MongoDB
- State Management: Redux

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/shashank-kulkarni9/SocKrit.git
   ```
3. Change to the project directory:
    ```
   cd your-project-directory
    ```
5. Change to client and server directories to install dependencies using
   ```
   npm install
   ```
7. Set up the environment variables:
   - Create a `.env` file in the root directory
   - Define the required environment variables (e.g., database connection string, API keys, etc.) as
     ```
     MONGO_URL= 'url-to-your-mongodb-connection'
     JWT_SECRET='any-random-string'
     PORT= <PORT_NUMBER>
     ```

8. Start the Frontend development server: `npm start` in `root-directory\client`
9. Start the Backend server: `nodemon index.js` in `root-directory\server`
10. Open your web browser and navigate to `http://localhost:3000` to access the application.

## Usage

- Register a new user account or log in with existing credentials.
- Navigate through different pages or features of the application.
- Interact with the user interface to perform actions such as creating posts, liking posts, etc.


