
# LAB - 9 - API Server

## Project Name
API Server

### Author: Brad Smialek

### Links and Resources
* [submission PR](https://github.com/brad-smialek-401-advanced-javascript/lab-class-9-API-Server/blob/master/README.md)
* [travis]([![Build Status](https://www.travis-ci.com/brad-smialek-401-advanced-javascript/lab-class-9-API-Server.svg?branch=master)](https://www.travis-ci.com/brad-smialek-401-advanced-javascript/lab-class-9-API-Server))
* [Heroku](https://git.heroku.com/lab9-docs.git) 


#### Documentation
* [jsdoc](https://git.heroku.com/lab9-docs.git/docs) 


### Modules
#### `v1.js`
#### `swagger.js`
#### `categories-model.js`
#### `categories-schema.js`
#### `people-model.js`
#### `products-model.js`
#### `products-schema.js`
#### `todo-model.js`
#### `todo-schema.js`
#### `memory.js`
#### `mongo.js`s
#### `app.js`


#### Exported Values and Methods
##### `mongo.js`
###### `jsonSchema -> Model`
###### `get -> _id`
###### `create -> record`
###### `update -> _id , record`
###### `delete -> _id`

##### `memory.js`
###### `get -> _id`
###### `create -> entry`
###### `update -> _id , entry`
###### `delete -> _id`
###### `sanitize-> entry`

### Setup
#### `.env` requirements
* `PORT` - 3000
* `MONGODB_URI=mongodb://localhost:27017/class09`  mongo instance/db

#### Running the app
* `node index.js`

  
#### Tests
* npm test
* supergoose.js
* can connect

#### UML
![UML](./assets/apiserveruml.JPG)
