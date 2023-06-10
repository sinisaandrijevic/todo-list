<h1>Simple MERN Stack Todo List</h1>

This is a simple web application that allows users to create and manage their tasks. 
It is built using the MERN stack and allows users to perform basic CRUD operations.

<h3>Prerequisites</h3>

Before running this application, ensure that you have the following software installed on your machine:

Node.js (version 12 or higher)
MongoDB (Make sure it's running on your machine or provide a remote MongoDB URI)

<h3>Getting Started</h3>

Follow the steps below to get started with the application:

Clone the repository:
git clone https://github.com/your-username/simple-mern-todo.git

Change into the project directory:
cd todo-list

Install the dependencies:
npm install

Create a .env file in the root directory of the project and provide the necessary environment variables:
PORT=3001
MONGODB_URI='your Mongo URI'

Start the development server:
cd /server
npm start

Start the React Application Frontend:
cd /client
npm start

<h3>Folder Structure</h3>

The project follows a standard MERN stack folder structure:

client/: Contains the frontend code built with React.js.
server/: Contains the backend code built with Node.js and Express.js.
server/model/: Defines the MongoDB models.
server/routes/: Contains the API routes.
server/controller/: Implements the logic for handling API requests.
server/database/: Stores configuration files, such as database connection.

<h3>Dependencies</h3>
The application uses the following major dependencies:

Backend
express: A web application framework for Node.js.
mongoose: An Object Data Modeling (ODM) library for MongoDB and Node.js.
dotenv: Loads environment variables from a .env file.
cors: Enables Cross-Origin Resource Sharing (CORS) for the server.
body-parser: Parses the request body data and makes it accessible in the req.body property.
nodemon: Automatically restarts the server whenever file changes.

Frontend
axios: A promise-based HTTP client for the browser.
font-awesome: A library of scalable vector icons.
react: A JavaScript library for building user interfaces.
react-dom: Provides DOM-specific methods for React components.
react-router-dom: Provides routing capabilities for React applications.
react-redux: Official React bindings for Redux.
react-scripts: Configuration and scripts for Create React App.
redux: A predictable state container for JavaScript apps.
redux-devtools-extension: Provides integration with Redux DevTools extension.
redux-mock-store: A mock store for testing Redux async action creators and middleware.
redux-thunk: Thunk middleware for Redux, allowing asynchronous logic in actions.

Please refer to the package.json file for the complete list of dependencies.

<h3>Contributing</h3>
If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Any contributions are welcome!

<h3>License</h3>
This project is licensed under the MIT License.

<h3>Acknowledgements</h3>
MongoDB for providing a powerful and flexible NoSQL database.
Express.js for the web application framework.
React.js for the frontend library.
Node.js for the JavaScript runtime environment.

<h3>Contact</h3>
If you have any questions, suggestions, or feedback, please feel free to contact me at andrijevicsinisa2006@gmail.com.