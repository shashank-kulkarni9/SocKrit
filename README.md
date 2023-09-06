# SocKrit

This is a full-stack MERN (MongoDB, Express, React, Node.js) application.

- Deployement :
    - https://sockrit.vercel.app/
    - (or)
    - https://sockrit-shashank-kulkarni9.vercel.app/
  
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
- User profiles with profile picture upload
- Post creation and management
- Like functionality for posts
- Dark mode support
- Responsive design for mobile and desktop
- CRUD Operations

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

## Contributing

There are many features to be implemented in this project and some bugs to fix. If you'd like to contribute to the project, please follow the guidelines outlined below:

1. Fork the repository and clone it to your local machine.
   ```shell
   git clone https://github.com/your-username/project-name.git
   ```
2. Create a new branch for your feature or bug fix.
   ```
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and test them thoroughly.
4. Commit your changes with descriptive commit messages.
   ```
   git commit -m "Add your commit message here"
   ```
5. Push your changes to your forked repository.
   ```
   git push origin feature/your-feature-name
   ```
6. Open a pull request against the main repository's main branch.
7. Provide a detailed description of your changes and why they should be merged.
8. Follow the feedback and discussion on your pull request.
   

