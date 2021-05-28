# Node.js, Express.js, and PostgreSQL: CRUD REST API

This is a short example on how to create a CRUD RESTful API in Node.js enviromentrunning on a Express server and using a PostgreSQL database. 

 This project involves installing PostgreSQL, creating a new user, creating a database, and initializing a table with schema and some data before running 

 ### Connecting to a Postgres database from Node.js
  
Within the queries.js file you should set up the configuration of your PostgreSQL connection, using the node-postgress module.

```
const Pool = require('pg').Pool
const pool = new Pool({
  user: '<database-user>',
  host: '<database-host>',
  database: '<database-name>',
  password: '<database-user',
  port: <database-port>,
})
````