# Express.js

# Outline

  1. What Express Is
  2. How to install it
  3. How to create a project with it
  4. It's role in a MEAN stack

# What Express Is

Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.

# Installing Express

You can install Express as an npm dependency

```
$ npm install express --save
```

Or you can install the Express generator with the following command:

```
$ npm install express-generator -g
```

# Create a project with it

Then, build an app named myapp

```
$ express myapp

   create : myapp
   create : myapp/package.json
   create : myapp/app.js
   create : myapp/public
   create : myapp/public/javascripts
   create : myapp/public/images
   create : myapp/routes
   create : myapp/routes/index.js
   create : myapp/routes/users.js
   create : myapp/public/stylesheets
   create : myapp/public/stylesheets/style.css
   create : myapp/views
   create : myapp/views/index.jade
   create : myapp/views/layout.jade
   create : myapp/views/error.jade
   create : myapp/bin
   create : myapp/bin/www
```

Then install dependencies:

```
$ cd myapp
$ npm install
```

# It's role in a MEAN stack

Express is the 'E' in the MEAN stack (Mongo, Express, Angular, Node) and it builds the back end of the app.
