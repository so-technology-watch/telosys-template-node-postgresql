# Node.JS PostgreSQL Telosys 3 Template  

This is a Telosys Template for code generation.  
It's purpose is to generate a working NodeJS REST API after having provided a DSL model.  
  
The generated server Application is a NodeJS REST API using PostgreSQL as database. The application is written in JavaScript ES6.  

This repository is a fork of the NodeJS-SQLite template for Telosys 3.  
Therefore, the installation is pretty much similar, the only difference is :   

In the templates telosys-tools.cfg file, add the following line  
```
ProjectVariable.POSTGRE_CONNECT=postgres://user:password@host/database
```  
And edit it with the correct informations. This will make Telosys generator add your database connection parameters in the "config/dbconfig.js" file (or you can directly edit the dbconfig.js file if you want).

Then follow original repository installation guide [here](https://github.com/telosys-templates-v3/javascript-web-rest-nodejs-express/wiki).
