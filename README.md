NASA Mission Control Dashboard

This server-side application, written in JavaScript with Node.js and Express, provides the back-end functionality for the NASA Mission Control Dashboard, which is used to schedule missions targeting Kepler exoplanets.


Table of Contents
1. Features
2. Getting Started
3. Installation
4. Running the Application
5. API Endpoints
6. License


Features
Data loading and management of Kepler exoplanets information.
RESTful API for planets and launches data.
Integration with AWS DynamoDB for data storage.
Middleware configuration for CORS and logging.

Getting Started
To get started with this project, first ensure that you have a working client-side application.

Installation
Clone the repository to your local machine.

git clone https://github.com/Kuazk/NASA-project.git

Change into the project directory.

cd nasa-mission-control-dashboard

Install the required dependencies.

npm install


Running the Application

Start the server by running the following command:

npm start
The server will start running on http://localhost:8000. You can now access the API endpoints from your client-side application.
API Endpoints
This server provides the following API endpoints:

GET /planets: Retrieve the list of exoplanets.
GET /launches: Retrieve the list of launches.
POST /launches: Schedule a new launch.
DELETE /launches/:id: Abort a scheduled launch.


License
This project is licensed under the ISC License.




