# Backend Development Tutorial

This project was developed as part of my Web Programming coursework to understand the fundamentals of backend development using Node.js, Express.js, and MongoDB. It focuses on creating REST APIs, handling user requests, and storing information in a database.

## Technologies Used

**Node.js and Express.js:** Used to create the backend server, handle HTTP requests, and define API endpoints.

**MongoDB Atlas and Mongoose:** Used to store and manage data in a cloud database and perform database operations.

**bcrypt:** Used to hash user passwords and verify them during login.

**Postman:** Used to test API requests and check responses.

**Nodemon and dotenv:** Used to simplify development and manage environment variables.

## Features

The application supports user registration, login, and logout functionality. It includes basic input validation, password hashing, and error handling to manage user requests.

It also provides APIs for creating posts and retrieving stored posts from MongoDB.

## Project Structure

The project follows a modular backend structure. The models define how data is stored, controllers contain the logic for handling requests, and routes connect API endpoints to their respective controllers.

The configuration files manage the database connection, while the main application files initialize and start the Express server.

## API Endpoints

The backend includes POST endpoints for registering users, logging in, logging out, and creating posts. A GET endpoint is used to retrieve posts stored in the database.

## Running the Project

To run the project locally, the repository needs to be cloned and the required dependencies installed. A MongoDB Atlas connection string and port number must be configured in a `.env` file.

Once configured, the backend can be started through the development script provided in the project.

## Testing

The API endpoints were tested using Postman. Successful requests return appropriate HTTP status codes and JSON responses. MongoDB Atlas was used to verify that information was being stored and retrieved correctly.

## Learning Outcomes

Through this project, I learned how backend applications are structured, how REST APIs work, and how Express.js communicates with MongoDB using Mongoose. I also gained practical experience with asynchronous JavaScript, password hashing, API testing, and version control using Git and GitHub.

---

**Shivam Maurya**  
B.Tech Computer Science and Engineering  
BML Munjal University