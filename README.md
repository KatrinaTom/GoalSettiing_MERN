# Goal Setting App to learn the MERN Stack

* Mongo
* Express
* React
* Node JS

## Packages
* express (Backend Node.js Framework)
* dotenv (Protect hidden environments)
* mongoose (ODM library for MongoDB and Node.js - manage relationships between data)
* colors (view colours in error handling)
* nodemon (automatic server restart)
* express-async-handler (error handling)
* concurrently (run backend and frontend together)

Note: ODM = Object Data Modelling

## Project Overview
To learn the MERN stack through practice. This project is to build from start to finish a Goal Setting applicaton.
Making use of CRUD operations.

## To run Frontend and Backend



## To run server (Backend) 
package.json was updated

```
{
    scripts: 
    {
        "start": "node backend/server.js",
        "server": nodemon backend/server.js"
    }
}

npm start server

```


## Authentication
To create Register user functionality, the data needs to be encrypted.

Install Bcrypt:

``npm i bcryptjs``

Install JSON Web Tokens:

``npm i jsonwebtoken``

## Redux - Frontend

1. Install redux, the below is for latest, with a template and installing redux.

``npx create-react-app@latest frontend --template redux``


2. Update the backend package.json script to prefix the frontend redux app. 

`` "client": "npm start --prefix frontend"``

![package.json scripts](images/scripts.png)

3. To run the frontend app:

``npm run client``

Example of Redux

![Redux](images/redux.png)

4. Install Extension: Name: ES7+ React/Redux/React-Native snippets

https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets

5. Install router (create routes to react pages)

``npm i react-router-dom``

**Note:** Make sure you are in the Frontend folder

6. Create a components folder > Header.jsx file

This is to keep the components seperate and manageable. (Headers.jsx will allow for navigation)

``npm i react-icons``

**Note:** Make sure you are in the Frontend folder when installing this module.

7. Show alerts and Promise based HTTP client for the browser and node.js.

``npm i axios react-toastify``

**Note:** Make sure you are in the Frontend folder when installing this module.

8. Add a proxy to your frontend package.json file

``"proxy:": "http://localhost:8000",``

## Install Package to run concurrently

``npm i -D concurrently``

A developer dependancy, run Frontend and Backend together.

**Note:** Make sure you are in the root folder when installing this module.

Next add the script to the package.json file.

![concurrently script](images/concurrently.png)

To run

``npm run dev``

Should see Frontend start and then Backend start.

# Progress Snapshot

* Mobile Web Responsive

**DashBoard** 

![Dashboard](images/progress/dashboard.png)

**login**

![Login](images/progress/login.png)

**Register**

![Register](images/progress/register.png)




## Resources
Traversy Media:

Part 1: https://www.youtube.com/watch?v=-0exw-9YJBo

Learn The MERN Stack - JWT Authentication

Part 2: https://www.youtube.com/watch?v=-0exw-9YJBo

Learn the MERN Stack - Frontend Authentication | Redux Toolkit

Part 3: https://www.youtube.com/watch?v=mvfsC66xqj0

Git Repository: https://github.com/bradtraversy/mern-tutorial

Part 4: https://www.youtube.com/watch?v=UXjMo25Nnvc

Learn The MERN Stack - Redux Goals & Deploy


## Important Websites

JWT: https://jwt.io/

Redux: https://redux-toolkit.js.org/

Redux DevTools (Chrome Extension): https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en

Note of interest: https://github.com/pmndrs/zustand
