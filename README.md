To install dependencies

\$ npm install

Run mongodb

Double click the Start MongoDB.bat file

Open mongoDB Compass

- Click CONNECT
- make sure mongodb is running

- CREATE DATABASE
  - Database Name
    postMANAGERDB
  - Collection Name
    postMessages

Run nodemon
\$ nodemon index.js

--- File Structure ---

db.js

- has postManagerDB from mongoDB compass connected by mongoose

index.js

- has postMessageRoutes thru postMessageController

./models/postMessage.js

- model for postMessage

./controllers/postMessageController.js

- creates a method for get,post,put and delete to implement the correct operations
