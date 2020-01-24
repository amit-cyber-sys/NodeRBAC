### Role Based Access Control using Nodejs,Mongodb,Express

#### What is RBAC?

Role-based access control (RBAC) is an approach used to restrict access to certain parts of the system to only authorized users. The permissions to perform certain operations are assigned to only specific roles. Users of the system are assigned those roles, and through those assignments, they acquire the permissions needed to perform particular system functions. Since users are not assigned permissions directly, but only acquire them through the roles that have been assigned to them, management of individual user rights becomes a matter of simply assigning appropriate roles to a particular user.

#### Prerequisites

You’ll need to have a basic understanding of NodeJS, Mongodb and Javascript.

#### Packages Used & Their uses
 * This package loads environmental variables from a .env  file into Node’s process.env object.
 * bcrypt : is used to hash user passwords or other sensitive information we don’t want to plainly store in our database.
 * body-parser : is used to parse incoming data from request bodies such as form data and attaches the parsed value to an object which can then be accessed by an express middleware.
 * jsonwebtoken : provides a means of representing claims to be transferred between two parties ensuring that the information transferred has not been tampered with by an unauthorized third party, we’ll see exactly how this works later on.
 * mongoose : is an ODM library for MongoDB, provides features such as schema validation, managing relationships between data, etc…
 * express : makes it easy to build API’s and server-side applications with Node, providing useful features such as routing, middlewares, etc..
 * accesscontrol : provides role and attribute-based access control.

#### Installation

 * git clone <URL>
 * cd folder-name
 * npm install
 * change db name as your choice in server.js
 * node server/server.js
 * Test the application in Postman
 * User url : (localhost:3000/signup)

#### Author
    Amit Kumar Singh