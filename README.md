# Blog Template using EJS

![GitHub](https://img.shields.io/github/license/efecollins/blog-template-ejs)
![Twitter Follow](https://img.shields.io/twitter/follow/EfeCollins7?color=blue&style=social)

This is an application that serves as a blog template for potential blog creators. Perfect, if you want to create a blog yourself but not from scratch. **Best for developers**.

The application is built with Node.js, Express.js, EJS, Lodash, MongoDB & Mongoose. The said technologies were used for reasons such as speed, efficiency and readability since most developers have a working knowlegde of JavaScript.
The database enables the information on the blog to continuously be available until deleted.

## Installation
- Clone repository with the command `git clone <url>`
```
$ git clone https://github.com/efecollins/blog-template-ejs.git
```

- Run `npm i` in your terminal to install `node_modules` and all dependencies in `package.json`
```
$ npm i
```
- Run `nodemon` in your terminal if installed to start the node server and watch for changes in `app.js`
```
$ nodemon
```

- Or run `node app.js` to start the server if `nodemon` is not installed
```
$ node app.js
```

- The following message should be logged to your console signifying success.

```
Server started on port 3000
```

- To use MongoDB with Mongoose locally, do this:
```
mongoose.connect("mongodb://localhost:27017/blogDB", {useNewUrlParser: true});
```

## More Info
- To compose a new post enter `localhost:3000/compose` in your web browser's search bar.

- To compose a new post in the live site visit [https://cerise-seahorse-vest.cyclic.app/compose](https://cerise-seahorse-vest.cyclic.app/compose)

- Only technical articles are allowed on the live site.
