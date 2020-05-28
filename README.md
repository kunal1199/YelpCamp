# YelpCamp

> A Node.js web application project that lets users view campgrounds, upload their own campgrounds, comment and review the campgrounds that will help other users to make a better decision while choosing their camping destinations for a short trip over the weekend. 

## Live Demo

To see the app in action, go to [https://yelpcamp--demo.herokuapp.com/](https://yelpcamp--demo.herokuapp.com/)

## Features

* Authentication:
  
  * User login with username and password

  * New user's sign up

* Authorization:

  * One cannot manage posts and view user profile without being authenticated

  * One cannot edit or delete posts and comments created by other users

* Manage campground posts with basic functionalities:

  * Create, edit and delete posts and comments

  * Upload campground photos
  
  * Search existing campgrounds

* Flash messages responding to users' interaction with the app

* Responsive web design
 
## Getting Started

> This app contains API secrets and passwords that have been hidden deliberately, so the app cannot be run with its features on your local machine. However, feel free to clone this repository if necessary.

### Clone or download this repository

```sh
git clone https://github.com/lucasweng/yelp-camp.git
```

### Install dependencies

```sh
npm install
```

or

```sh
yarn install
```

### Comments in code

Some comments in the source code are course notes and therefore might not seem necessary from a developer's point of view.

## Built with

### Front-end

* [ejs](http://ejs.co/)
* [Bootstrap](https://getbootstrap.com/docs/3.3/)

### Back-end

* [express](https://expressjs.com/)
* [mongoDB](https://www.mongodb.com/)
* [mongoose](http://mongoosejs.com/)
* [passport](http://www.passportjs.org/)
* [passport-local](https://github.com/jaredhanson/passport-local#passport-local)
* [express-session](https://github.com/expressjs/session#express-session)
* [method-override](https://github.com/expressjs/method-override#method-override)
* [connect-flash](https://github.com/jaredhanson/connect-flash#connect-flash)

### Platforms

* [Heroku](https://www.heroku.com/)
* [Cloud9](https://aws.amazon.com/cloud9/?origin=c9io)