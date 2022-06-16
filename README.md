# health-ecommerce

This project is an E-Commerce Web App as a graduation project from the Job Placement Program by Sprints as part of [egFWD scholarship](https://egfwd.com/)

The E-Commerce app has two types of users:

- **User**: can browse products, add to cart and make orders
- **Admin**: can add products, change order status and view bussiness statistics

## How to run the project

### Run the back-end

- You need to have the following installed

  - **MongoDB**
  - **Node.JS**
  - **NPM**

- Create MongoDB cluster and obtain connection string
- Clone this repository
- Create enviornment file `/back-end/src/config/.env.development`
- Inside `.env.development`, add the following enviornment variables:

```
MONGODB_URL={MongoDB connection string}
JWT_SECRET={JWT secret key}
PORT={The port you want the server to run on (typically 3000)}
```

- Navigate to `project/back-end`
- Run the following commands:

```
npm install
npm run start
```

- Server is now running on `http://localhost:{PORT}`

### Run the front-end

- Navigate to `project/front-end`
- Run the following commands:

```
npm install
npm run start
```

- You can now access the app on `http://localhost:3003`

## Built With

- [Node.js](https://nodejs.org/en/) - Runtime environment to help build fast server applications
- [Express.js](https://expressjs.com/) - Backend web framework
- [MongoDB](https://www.mongodb.com/) - Database to store document-based data
- [Mongoose](https://mongoosejs.com/) - Object-modeling tool for Node.js
- [React](https://reactjs.org/) - JavaScript library for building user interfaces
- [Heroku](http://heroku.com/) - Platform to deploy web applications
- [JSON Web Token](https://jwt.io/) - A standard to securely authenticate HTTP requests
