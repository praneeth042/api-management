# Demonstrates the setting up of URI for the REST API


Change Log
==========
October 2019  Converted the code to use MongoDB Cloud
              Updated the package.json with latest versions
              Took care of the depercations
              Updated the index.js for DB parameters setting

December 2017 Updated the DB Connection code
              Data updated for the testing.
              Instead of providing the User/Password now the URI for DB is used in the format: mongodb://<user>:<password>@SERVER:PORT/DB-NAME

Setup
=====
1. Clone this project on local file system
> git clone link-to-project
2. Pre-requisistes
      a. Understanding of node/npm
      b. An instance of MongoDB available either locally or remotely
      c. Import the data available in the repository
3. Run > npm install
      Deploys the packages
          express
          body-parser
          mongoose

4. Switch between branches
> git checkout  errorhandling


Create from scratch
===================
1. create the project
2. git init
3. add .gitignore
4. npm init
5. npm install the packages (express,body-parser,mongoose)

6. create folder = models

<!-- Helpful Links
=============
https://github.com/felixge/node-style-guide
https://blog.risingstack.com/node-js-best-practices/ -->