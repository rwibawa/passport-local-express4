# passport-local-express4
User Authentication With Passport and Express 4.
[PassportJS](https://github.com/jaredhanson/passport)
[Tutorial](http://mherman.org/blog/2015/09/26/social-authentication-in-node-dot-js-with-passport)
[Tutorial](http://mherman.org/blog/2015/01/31/local-authentication-with-passport-and-express-4/)

## 1. setup with express generator
```bash
$ npm install -g express-generator@4
$ express --version
4.15.5
$ express passport-local-express4

  warning: the default view engine will not be jade in future releases
  warning: use `--view=jade' or `--help' for additional options


   create : passport-local-express4
   create : passport-local-express4/package.json
   create : passport-local-express4/app.js
   create : passport-local-express4/public
   create : passport-local-express4/routes
   create : passport-local-express4/routes/index.js
   create : passport-local-express4/routes/users.js
   create : passport-local-express4/views
   create : passport-local-express4/views/index.jade
   create : passport-local-express4/views/layout.jade
   create : passport-local-express4/views/error.jade
   create : passport-local-express4/bin
   create : passport-local-express4/bin/www
   create : passport-local-express4/public/javascripts
   create : passport-local-express4/public/images
   create : passport-local-express4/public/stylesheets
   create : passport-local-express4/public/stylesheets/style.css

   install dependencies:
     $ cd passport-local-express4 && npm install

   run the app:
     $ DEBUG=passport-local-express4:* npm start
```
