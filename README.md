# REACT E-commerce

## Description

Built with MERN stack. Overall, the app offers the possibility to perform these actions: 

1. Merchants manage their own brand component
2. Buyers browse the store categories, products and brands
3. Administrators manage and control the entire store components 


* features:
  * Node provides the backend environment for the whole app
  * Express middleware is used to handle requests and routes
  * Mongoose schemas are use to model the application data
  * React for displaying User Interface components
  * Redux to manage application's state
  * Redux Thunk middleware to handle asynchronous redux actions



## Visual

![For E-Commerce](/clientpublic//images/favicon.ico)
Format: ![React E-commerce logo](https://walf-dev.github.io/)


## Install

Some basic Git commands are:

```
$ git clone https://github.com/Walf-dev/react-ecommerce.git
$ cd project
$ npm install
```

## Setup

```
 Create .env file that include:

  * MONGO_URI & JWT_SECRET
  * PORT & BASE_SERVER_URL & BASE_API_URL & BASE_CLIENT_URL
  * MAILCHIMP_KEY & MAILCHIMP_LIST_KEY => Mailchimp configuration
  * MAILGUN_KEY & MAILGUN_DOMAIN & MAILGUN_EMAIL_SENDER => Mailgun configuration
  * GOOGLE_CLIENT_ID & GOOGLE_CLIENT_SECRET & GOOGLE_CALLBACK_URL => Google Auth configuration
  * FACEBOOK_CLIENT_ID & FACEBOOK_CLIENT_SECRET & FACEBOOK_CALLBACK_URL => Facebook Auth configuration
  * AWS_ACCESS_KEY_ID & AWS_SECRET_ACCESS_KEY & AWS_REGION & AWS_BUCKET_NAME => AWS configuration
```

## Heroku Deployment

```
> Create a Procfile in the root directory of your application with the following command **web: npm run start:production**
```


## Simple build for production

```
$ npm run production
```

## Run the application for development

```
$ npm start
```

## Run the application for production

```
$ npm run start:production
```


## Languages & tools

- [Node](https://nodejs.org/en/)

- [Express](https://expressjs.com/)

- [Mongoose](https://mongoosejs.com/)

- [React](https://reactjs.org/)

- [Webpack](https://webpack.js.org/)

