# ernie

Simple template to start `*ERN` type web apps.

```

npm start
cd client
npm start

```

__NOTE__: Vulnerability alerts are from create-react-app, NOT from the Node.js server - [GO TO SECTION](#vulnerabilities)

1. [ernie](#ernie)
   1. [About](#about)
   2. [Package Info](#package-info)
   3. [Usage](#usage)
   4. [Vulnerabilities](#vulnerabilities)

## About

Based on this [freecodecamp.com guide.](https://www.freecodecamp.org/news/how-to-create-a-react-app-with-a-node-backend-the-complete-guide/)

This repo functions as a boilerplate template / quickstart for building an application with a client side GUI using React that communicates with a Node.js API server - All hosted on the same server. Uses all the steps from the [freecodecamp.com guide](https://www.freecodecamp.org/news/how-to-create-a-react-app-with-a-node-backend-the-complete-guide/), up until deploying your API application to Heroku.

This repo stops using the guide at this line:

```
// server/package.json

"engines": {
"node": "your-node-version"
}

```

I named it __ernie__ because it is used by `*ERN` stack apps. 
(MERN, NERN)

- __E__ xpress
- __R__ eact
- __N__ ode

This package can be used with your choice of database, 

## Package Info

1. [Node](https://nodejs.org/en/)
2. [React](https://reactjs.org/)
3. [Express](https://expressjs.com/)
4. [create-react-app](https://create-react-app.dev/)

## Usage

How to start the servers, starting in the root directory:

```

npm start
cd client
npm start

```


1. run `npm start` in the root directory. This starts the Node.js server with API using Express.
   1. Launches on `localhost:3001`
2. cd into client directory
3. run `npm start` inside of `%ROOT_DIR%/client` to start the React app on live server.
   1. Launches on `localhost:3001`
4. Go to `localhost:3001` using a web browser.
5. If you see "Is this thing on?" underneath the React logo, then you are connected to your Node.js API!

## Vulnerabilities

I will try to keep this package up to date, but it is reliant on create-react-app to build the react front end.
- [Resource 1](https://github.com/facebook/create-react-app/issues/11174)
- [Resource 2](https://github.com/facebook/create-react-app/issues/10929)

