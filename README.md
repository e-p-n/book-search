
# Book Search Engine


## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Developer](#questions)
  
## Description
A website for searching Google Books and then adding or removing books from your personal book list. Site is built with:

* General
    * [Node.js](https://nodejs.org/en/)
    * [if-env](https://www.npmjs.com/package/if-env)
    * [concurrently](https://www.npmjs.com/package/concurrently)*
    * [MongoDB](https://www.mongodb.com)
* Server 
    * [Express](https://www.npmjs.com/package/express)
    * [GraphQL.js](https://www.npmjs.com/package/graphql)
    * [Mongoose](https://www.npmjs.com/package/mongoose)
    * [apollo-server-express](https://www.npmjs.com/package/apollo-server-express)
    * [bcrypt](https://www.npmjs.com/package/bcrypt)
    * [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
    * [nodemon](https://www.npmjs.com/package/nodemon)*
* Client
    * [@apollo/react-hooks](https://www.npmjs.com/package/@apollo/react-hooks)
    * [apollo-boost](https://www.npmjs.com/package/apollo-boost) 
    * [bootstrap](https://www.npmjs.com/package/bootstrap)
    * [GraphQL.js](https://www.npmjs.com/package/graphql)
    * [graphql-tag](https://www.npmjs.com/package/graphql-tag)
    * [jwt-decode](https://www.npmjs.com/package/jwt-decode)
    * [React](https://reactjs.org)
    * [react-bootstrap](https://www.npmjs.com/package/react-bootstrap)
    * [react-dom](https://www.npmjs.com/package/react-dom)
    * [react-router-dom](https://www.npmjs.com/package/react-router-dom)
    * [react-scripts](https://www.npmjs.com/package/react-scripts)

*Installed as Dev dependencies


## Installation
You will need to have a local MongoDB and copy of Node.js installed to work with the site locally.

1. Clone the [Github Repository](https://github.com/e-p-n/book-search)
2. From the root directory use the command `npm i` or `npm install` to install the dependencies
3. Run `npm start` from the app's root directory to initiate the database and get started.

## Usage
To try out the site, visit the [Heroku deployment](https://sleepy-hamlet-73644.herokuapp.com/). From there you can search for boooks, login or signup, add books to your list, delete books from your list and visit the Google Books page for the book.

[![](./client/public/screenshot.png)](https://sleepy-hamlet-73644.herokuapp.com/)

## Developer
This website was converted from a REST API to GraphQL with Apollo Server by Eric Normann, a student in the full-stack development program at U of T. If you have questions, please visit my [GitHub](http://github.com/e-p-n) page or [email](mailto:eric.n@me.com?subject=Question%20regarding%20Portfolio) me.  
