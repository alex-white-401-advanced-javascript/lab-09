![CF](http://i.imgur.com/7v5ASc8.png) LAB 9 - API Server
=================================================

## API SERVER

### Author: Alexander White

### Links and Resources
* [PR](https://github.com/alex-white-401-advanced-javascript/lab-09/pull/1)
* [![Build Status](https://travis-ci.com/alex-white-401-advanced-javascript/lab-09.svg?branch=master)](https://travis-ci.com/alex-white-401-advanced-javascript/lab-09)

#### Documentation
* [swagger](/docs/config/swagger.json)
* [jsdoc](/docs/index.html)

### app.js
####

## Api Directory
#### v1.js
* `router.get('/api/v1/:model', handleGetAll);`
* `router.get('/api/v1/:model/:id', handleGetOne);`
* `router.post('/api/v1/:model', handlePost);`
* `router.put('/api/v1/:model/:id', handlePut);`
* `router.delete('/api/v1/:model/:id', handleDelete);`

## Middleware Directory
#### 404.js
* Not Found error handler
#### 500.js
* Internal server error
#### model-finder.js
* Which model to send request to

## Models Directory
### Categories
#### categories-model.js
* Schema
* Class Categories extends Memory-Model
### Players
#### players-models.js
* Class Players extends Mongo-Model
#### players-schema.js
* Mongoose Schema
### Teams
#### teams-models.js
* Class Teams extends Mongo-Model
#### teams-schema.js
* Mongoose Schema
### memory-model.js
* Local memory Model
### mongo-model.js
* MongoDB Model

### Setup
* `npm i`
#### `.env` requirements
* `PORT` - assign a port number
* `MONGODB_URI` - URL to the running mongo instance/db


#### Running the app
* `npm start`
  
#### Tests
* How do you run tests?
  * `npm run test`
  * `npm run lint`
* What assertions were made?
* What assertions need to be / should be made?

#### UML

[UML DIAGRAM](/lab-09-UML.jpg)