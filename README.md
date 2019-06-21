# Lab 19 Message Server

## Project Name

### Author: Felipe Delatorre

### Links and Resources
* [submission PR](http://xyz.com)
* [travis](http://xyz.com)
* [Logger](http://xyz.com) (when applicable)
* [API App](http://xyz.com) (when applicable)

#### Documentation
* [api docs](http://xyz.com) (API servers)
* [jsdoc](http://xyz.com) (Server assignments)
* [styleguide](http://xyz.com) (React assignments)

## Modules
### `server.js`
#### Creates a `file` queue
* Listens for `save` events from the `files` queue
* Listens for `error` events from the `files` queue
#### Creates a `database` queue
* Listens for `read` events from the `database` queue
* Listens for `create` events from the `database` queue
* Listens for `update` events from the `database` queue
* Listens for `delete` events from the `database` queue
* Listens for `error` events from the `database` queue

### Setup
#### `.env` requirements
* `PORT` - Port Number
* `MONGODB_URI` - URL to the running mongo instance/db

#### Running the app
* `npm start`
* Endpoint: `/foo/bar/`
  * Returns a JSON object with abc in it.
* Endpoint: `/bing/zing/`
  * Returns a JSON object with xyz in it.
  
#### UML
![](./assets/----.jpg)
