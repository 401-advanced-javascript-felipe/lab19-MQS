# Lab 19 Message Server

### Author: Felipe Delatorre

### Links and Resources
* [submission PR](http://xyz.com)
* [travis](http://xyz.com)
* [Logger](https://github.com/401-advanced-javascript-felipe/lab19-logger/pull/1)
* [API App](https://github.com/401-advanced-javascript-felipe/lab19-apiServer/pull/1)
* [File Save](https://github.com/401-advanced-javascript-felipe/lab19-fileSave/pull/1)


## Modules
### `server.js`
#### Creates a `file` queue
* Listens for `file-save` events from the `files` queue
* Listens for `error` events from the `files` queue
#### Creates a `database` queue
* Listens for `read` events from the `database` queue
* Listens for `create` events from the `database` queue
* Listens for `update` events from the `database` queue
* Listens for `delete` events from the `database` queue
* Listens for `error` events from the `database` queue

### Setup
#### `.env` requirements
* `PORT` - default values

#### Running the app
* For Success saves `npm start`
* For Errors `npm run startError`
  
#### UML
![](./assets/----.jpg)
