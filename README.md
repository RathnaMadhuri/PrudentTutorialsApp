# PrudentTutorialsApp
# PrudentTutorialsApp

Tutorial has id, title, description and published status. 

User can create, retrieve, update and delete tutorials,

There is a search box for finding tutorial by title.

Created folder for NodeJS app using the commands

$ mkdir nodejs-express-mongodb
$ cd nodejs-express-mongodb

Initialized the app with a package.json file

Installed Express, Mongoose and Cors.

Setting up the express server

Configuring the MongoDB and mongoose

Created models folder on server side for defining database

Created a database and collections in mongo shell the database is tutorials.

Encountered problems with api.Have to trouble shoot.

Created controller with CRUD functions.

const db = require("../models");
const Tutorial = db.tutorials;
// Create and Save a new Tutorial
exports.create = (req, res) => {
  
};
// Retrieve all Tutorials from the database.
exports.findAll = (req, res) => {
  
};
// Find a single Tutorial with an id
exports.findOne = (req, res) => {
  
};
// Update a Tutorial by the id in the request
exports.update = (req, res) => {
  
};
// Delete a Tutorial with the specified id in the request
exports.delete = (req, res) => {
  
};
// Delete all Tutorials from the database.
exports.deleteAll = (req, res) => {
  
};
// Find all published Tutorials
exports.findAllPublished = (req, res) => {


Implemented the CRUD functions. 

Defined Routes for the functions app/routes/tutorial.routes.js

Coming to frontend:

Created components folder. It has three components. Tutorialslist, TutorialDetails, AddTutorial (Added login component)

TutorialList gets and displays tutorials

TutorialDetails has for for editing tutorials using ID.

AddTutorial has form for submitting new tutorial.
The components call tutorial service methods which uses HttpClient to make Http requets and receive responses.

Added a login component

Future Improvements:

Adding user authentication. Developing api and db functionality.
Adding extra features to the application.
