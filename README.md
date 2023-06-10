<h1>Simple MERN Stack Todo List</h1>

This is a simple web application that allows users to create and manage their tasks. 
<br/>It is built using the MERN stack and allows users to perform basic CRUD operations.

<h3>Prerequisites</h3>

Before running this application, ensure that you have the following software installed on your machine:

Node.js (version 12 or higher)<br/>
MongoDB (Make sure it's running on your machine or provide a remote MongoDB URI)

<h3>Getting Started</h3>

Follow the steps below to get started with the application:

Clone the repository: 
<br/>git clone https://github.com/sinisaandrijevic/todo-list.git

Change into the project directory: 
<br/>cd todo-list

Install the dependencies:
<br/>npm install

Create a .env file in the server directory of the project and provide the necessary environment variables:
<br/>PORT=3001 
<br/>MONGODB_URI='your Mongo URI'

Start the development server: 
<br/>cd /server
<br/>npm start

Start the React Application Frontend:
<br/>cd /client
<br/>npm start

<h3>Folder Structure</h3>

The project follows a standard MERN stack folder structure:

client/: Contains the frontend code built with React.js.
<br/>server/: Contains the backend code built with Node.js and Express.js.
<br/>server/model/: Defines the MongoDB models.
<br/>server/routes/: Contains the API routes.
<br/>server/controller/: Implements the logic for handling API requests.
<br/>server/database/: Stores configuration files, such as database connection.

<h3>Dependencies</h3>
The application uses the following major dependencies:

<br/>Backend
<br/>express: A web application framework for Node.js.
<br/>mongoose: An Object Data Modeling (ODM) library for MongoDB and Node.js.
<br/>dotenv: Loads environment variables from a .env file.
<br/>cors: Enables Cross-Origin Resource Sharing (CORS) for the server.

Frontend
<br/>axios: A promise-based HTTP client for the browser.
<br/>react: A JavaScript library for building user interfaces.
<br/>react-router-dom: Provides routing capabilities for React applications.
<br/>react-redux: Official React bindings for Redux.
<br/>react-scripts: Configuration and scripts for Create React App.
<br/>redux: A predictable state container for JavaScript apps.

Please refer to the package.json file for the complete list of dependencies.

<h3>Contributing</h3>
If you would like to contribute to this project, feel free to fork the repository and submit a pull request.
<br/>Any contributions are welcome!

<h3>License</h3>
This project is licensed under the MIT License.

<h3>Acknowledgements</h3>
MongoDB for providing a powerful and flexible NoSQL database.
<br/>Express.js for the web application framework.
<br/>React.js for the frontend library.
<br/>Node.js for the JavaScript runtime environment.

<h3>Contact</h3>
If you have any questions, suggestions, or feedback, please feel free to contact me at andrijevicsinisa2006@gmail.com.
