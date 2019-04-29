# React Google Books Search App

This is a web application that enables one to search Google Books for books and then save individual entires to a database for later review. The application consists of two pages, a "Search" page and a "Saved" page.

## Software used

- [Node.js](https://nodejs.org)
- [Express](https://expressjs.com)
- [React](https://reactjs.org/)
- [Axios](https://github.com/axios/axios)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)

Instructions on how to start, develop and deploy the application continue below.

## About This Boilerplate

This setup allows for a Node/Express/React app which can be easily deployed to Heroku.

The front-end React app will auto-reload as it's updated via webpack dev server, and the backend Express app will auto-reload independently with nodemon.

## Starting the app locally

Start by installing front and backend dependencies. While in this directory, run the following command:

```
npm install
```

This should install node modules within the server and the client folder.

After both installations complete, run the following command in your terminal:

```
npm start
```

Your app should now be running on <http://localhost:3000>. The Express server should intercept any AJAX requests from the client.

## Deployment (Heroku)

To deploy, simply add and commit your changes, and push to Heroku. As is, the NPM scripts should take care of the rest.
